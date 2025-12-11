# devops-netology
### Мои изменения
Это моё первое редактирование для задания.
## Игнорируемые файлы (terraform/.gitignore)

- Все папки с именем `.terraform` и всё внутри них  
  → `**/.terraform/*`

- Все файлы с расширением `.tfstate` и `.tfstate.*`  
  → `*.tfstate` и `*.tfstate.*`

- Файл `crash.log` и все файлы вида `crash.*.log`  
  → `crash.log` и `crash.*.log`

- Все файлы с расширением `.tfvars` и `.tfvars.json`  
  → `*.tfvars` и `*.tfvars.json`

- Файлы `override.tf`, `override.tf.json`, а также любые файлы, заканчивающиеся на `_override.tf` или `_override.tf.json`  
  → `override.tf`, `override.tf.json`, `*_override.tf`, `*_override.tf.json`

- Файл `.terraform.tfstate.lock.info`  
  → `.terraform.tfstate.lock.info`

- Файлы `.terraformrc` и `terraform.rc`  
  → `.terraformrc` и `terraform.rc`
