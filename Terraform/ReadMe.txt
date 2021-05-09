Благодаря файлу Terraform.gitignore будут игнорироваться следующие файлы:
1) Файлы с расширением .terraform любой вложенности
2) Файлы в расширении которых присутствует .tfstate
3) Файл crash.log
4) Файлы с расширением .tfvars
5) Файлы с названием override.tf и override.tf.json и любые файлы в которых присутствует *_override.tf *_override.tf.json
6) Файлы с расширением .terraformrc и файл terraform.rc
