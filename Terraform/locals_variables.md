# Memo

変数定義<br>

- locals
  ローカル変数<br>
  プライベートな変数で外部から変更はできない

```terraform
locals {
    name = "hoge"
    # 変数名 = 変数の値
    # ${locals.name}で参照
}
```

- varialble
  外部から変更可能な変数
  コマンドラインで上書き可能

```terraform
# 変数名
variable "name" {
    # 型
    type = string
    # デフォルト値
    default = "hoge"
    # ${var.name}で参照
}
```
