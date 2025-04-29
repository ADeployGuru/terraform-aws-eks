# NOTICE

This repository is a fork of the [terraform-aws-modules/terraform-aws-eks](https://github.com/terraform-aws-modules/terraform-aws-eks) module, originally licensed under the Apache License 2.0.

## Changes made in this fork (based on tag `v19.21.0`):

- Added support for `cluster_compute_config` as a new input variable.
- Introduced the following `dynamic` blocks to support Autopilot (Auto Mode) features:
  - `compute_config`
  - `kubernetes_network_config` with conditional `elastic_load_balancing`
  - `storage_config` with `block_storage`

These changes are intended to enable extended cluster configuration for use cases involving GKE Autopilot-style node management.

## Original License

This project retains the original [Apache License 2.0](./LICENSE) provided by the upstream repository.

All original copyright notices from the `terraform-aws-modules/terraform-aws-eks` module are preserved.

