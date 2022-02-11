[![Terraform Testing and Release](https://github.com/mtharpe/terraform-manage-credentials-demo/actions/workflows/terraform.yml/badge.svg)](https://github.com/mtharpe/terraform-manage-credentials-demo/actions/workflows/terraform.yml)

## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_tfe"></a> [tfe](#requirement\_tfe) | >= 0.26.0 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_http"></a> [http](#provider\_http) | 2.1.0 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [http_http.tfc_ips](https://registry.terraform.io/providers/hashicorp/http/latest/docs/data-sources/http) | data source |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_oauth_token_id"></a> [oauth\_token\_id](#input\_oauth\_token\_id) | Terraform Enterprise/Cloud VCS oauth token ID (found in settings/VCS) | `any` | n/a | yes |
| <a name="input_org_name"></a> [org\_name](#input\_org\_name) | Terraform Enterprise/Cloud Organization name to create the workspaces in | `any` | n/a | yes |
| <a name="input_tfe_api_key"></a> [tfe\_api\_key](#input\_tfe\_api\_key) | Terraform Enterprise/Cloud API used to connect and configure workspaces | `any` | n/a | yes |

## Outputs

No outputs.
