# {{cookiecutter.terraform_name}}

{{cookiecutter.short_description}}

## Usage

```
terraform init -backend-config=backend.conf
terraform plan -var-file={{cookiecutter.var_file}}.tfvars
terraform apply -var-file={{cookiecutter.var_file}}.tfvars
```


LICENSE: 3-clause BSD license.


---
Copyright © {{cookiecutter.release_date.split('-')[0]}}, {{ cookiecutter.full_name }}
