## Packer useful commands
## packer build <.hcl or json file>

# If incase you have empty var you can pass extra argument to make it dynamic using -var
## packer build -var "infra_env=staging" <with .hcl or json file>

## Validate if packer configuration is correct
## packer validate <.hcl or json file>

## echo for error
## echo $?

# packer.exe validate -var "infra_env=staging" -var "vault_pass=secret"  cloudcasts.json

# -u admin -p LLhS5jrB7ez7vdh 
