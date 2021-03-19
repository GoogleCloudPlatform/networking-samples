# Networking Samples

This repository contains code samples for users of Google Cloud networking
products.

## Compatibility

This module is meant for use with Terraform 0.12. If you haven't
[upgraded](https://www.terraform.io/upgrade-guides/0-12.html) and need a
Terraform 0.11.x-compatible version of this module, the last released
version intended for Terraform 0.11.x is
[0.8.0](https://registry.terraform.io/modules/terraform-google-modules/network/google/0.8.0).

## Usage

Go to the examples in the product folders.

Then perform the following commands on the root folder:

- `terraform init` to get the plugins
- `terraform plan` to see the infrastructure plan
- `terraform apply` to apply the infrastructure build
- `terraform destroy` to destroy the built infrastructure

## Requirements

### Installed Software

- [Terraform](https://www.terraform.io/downloads.html) ~> 0.12.6
- [Terraform Provider for GCP](https://github.com/terraform-providers/terraform-provider-google) ~> 2.19
- [Terraform Provider for GCP Beta](https://github.com/terraform-providers/terraform-provider-google-beta) ~>
  2.19
- [gcloud](https://cloud.google.com/sdk/gcloud/) >243.0.0

### Enable API's

In order to operate with the Service Account you must activate the following API on the project where the Service Account was created:

- Compute Engine API - compute.googleapis.com

## Contributing

Refer to the [contribution guidelines](./CONTRIBUTING.md) for
information on contributing to this module.
