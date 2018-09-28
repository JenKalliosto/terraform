## terraform

# terraform - google cloud platform - cloudflare


export the info rows terraform requires:


google acc billing id

export TF_VAR_billing_account=


google cloud platform project name

export TF_VAR_project_name=


location of data centre (europe-north1 = hamina) 

export TF_VAR_region=


size of the virtual device

export TF_VAR_machine_type=


login email to cloudflare

export TF_VAR_cloudflare_email=


cloudflare -> my profile -> api keys -> global api key

export TF_VAR_cloudflare_token=


the domain cloudflare -> overview 

export TF_VAR_cloudflare_zone=


terraform init

terraform plan

terraform apply


-> domain should work now
