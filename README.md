# Terraform Beginner Bootcamp 2023

## 0.1.0
### Sematic versioning :mage:

This project will be using Sematic versioning system.
To know more about semantic versioning click [here](https://semver.org/)

Given a version number **MAJOR.MINOR.PATCH**, increment the: (eg. 1.0.0)

- **MAJOR** version when you make incompatible API changes
- **MINOR** version when you add functionality in a backward compatible manner
- **PATCH** version when you make backward compatible bug fixes
---

## 0.2.0
### Changes with Terraform CLI

Terraform CLI was not installed by default due to a GPG key deprication, It has been fixed by adding a new installation script at `./bin/install_tf_cli.sh`

This was updated on `.gitpod.yml` file under `tasks`

[Terraform CLI installation](https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli)