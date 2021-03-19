#  Custom mode network

This example configures a single simple custom mode VPC network inside of a project.

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| network\_name | The name of the VPC network being created | `any` | n/a | yes |
| project\_id | The project ID to host the network in | `any` | n/a | yes |


## Outputs

| Name | Description |
|------|-------------|
| auto | The value of the auto mode setting |
| network\_name | The name of the VPC being created |
| network\_self\_link | The URI of the VPC being created |
| project\_id | VPC project id |