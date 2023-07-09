# Memo

Terraform の構成内容は HCL2（HasiCorpLanguage2）で記述する。<br>

JSON に似ているがちょっと違う。

```terraform
# コメントがかける
variable message{
    # 「:」ではなく「=」で指定
    type = Strgin
    # 　ヒアドキュメントが記述可能
    default = <<EOF
Hello World!
EOF
}
```
