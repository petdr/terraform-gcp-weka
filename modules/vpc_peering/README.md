<!-- BEGIN_TF_DOCS -->
## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >=1.3.1 |
| <a name="requirement_google"></a> [google](#requirement\_google) | ~>4.38.0 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_google"></a> [google](#provider\_google) | ~>4.38.0 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [google_compute_network_peering.peering](https://registry.terraform.io/providers/hashicorp/google/latest/docs/resources/compute_network_peering) | resource |
| [google_compute_network.vpc_peering](https://registry.terraform.io/providers/hashicorp/google/latest/docs/data-sources/compute_network) | data source |
| [google_compute_network.vpcs](https://registry.terraform.io/providers/hashicorp/google/latest/docs/data-sources/compute_network) | data source |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_vnets_to_peer_to_deployment_vnet"></a> [vnets\_to\_peer\_to\_deployment\_vnet](#input\_vnets\_to\_peer\_to\_deployment\_vnet) | list of vpcs name to peering | `list(string)` | n/a | yes |
| <a name="input_vpcs_name"></a> [vpcs\_name](#input\_vpcs\_name) | list of backend vpcs name | `list(string)` | n/a | yes |

## Outputs

No outputs.
<!-- END_TF_DOCS -->