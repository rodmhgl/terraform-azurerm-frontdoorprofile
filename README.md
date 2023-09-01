## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >= 1.5.6 |
| <a name="requirement_azurerm"></a> [azurerm](#requirement\_azurerm) | >= 3.71.0 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_azurerm"></a> [azurerm](#provider\_azurerm) | >= 3.71.0 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [azurerm_cdn_frontdoor_profile.this](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/cdn_frontdoor_profile) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_name"></a> [name](#input\_name) | The name of the Front Door Profile. | `string` | n/a | yes |
| <a name="input_resource_group_name"></a> [resource\_group\_name](#input\_resource\_group\_name) | The name of the resource group in which to create the Front Door Profile. | `string` | n/a | yes |
| <a name="input_response_timeout_seconds"></a> [response\_timeout\_seconds](#input\_response\_timeout\_seconds) | The maximum response timeout in seconds (16-240). Defaults to 120. | `number` | `120` | no |
| <a name="input_sku_name"></a> [sku\_name](#input\_sku\_name) | The name of the SKU used for this Front Door Profile. | `string` | `"Standard_AzureFrontDoor"` | no |
| <a name="input_tags"></a> [tags](#input\_tags) | (Required) map of tags for the deployment | `map(any)` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_frontdoor_profile_id"></a> [frontdoor\_profile\_id](#output\_frontdoor\_profile\_id) | n/a |
| <a name="output_frontdoor_profile_name"></a> [frontdoor\_profile\_name](#output\_frontdoor\_profile\_name) | n/a |
| <a name="output_frontdoor_profile_resource_guid"></a> [frontdoor\_profile\_resource\_guid](#output\_frontdoor\_profile\_resource\_guid) | n/a |
