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


## Gitpod Lifecycle

We need to be careful when using the Init because it will not rerun if we restart an existing workspace.

https://www.gitpod.io/docs/configure/workspaces/tasks

## 0.3.0
## AWS CLI Installation

check if our AWS credentials is configured correctly by running the following AWS CLI command:
```sh
aws sts get-caller-identity
```

If it is succesful you should see a json payload return that looks like this:

```json
{
    "UserId": "AKIAWQDXRGLDFYML9YLR",
    "Account": "123456789012",
    "Arn": "arn:aws:iam::123456789012:user/tf-beginner-bootcamp-2023"
}
```