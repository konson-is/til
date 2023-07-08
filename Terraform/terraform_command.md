# Memo

- 現状のソースコードを元に実行計画を確認

```shell
terraform plan -var KEY=VALUE -var-file FILE
# var 変数の指定
# var-file 変数ファイルの指定
```

- ソースコードに従って変更を適用

```shell
terraform apply  -auto-approve -var KEY=VALUE -var-file FILE
# var 変数の指定
# var-file 変数ファイルの指定
# auto-approve 実行計画の確認なしで適用
```

- Terraform 管理のインフラ環境を削除

```shell
terraform destroy  -auto-approve
# auto-approve 実行計画の確認なしで適用
```
