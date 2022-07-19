# terraform-demo

## Basic info

A Terraform provider is a way for developers to programmatically interact with an application via their command line. The Sentry Terraform provider allows your team to configure and update Sentry project parameters, including Projects, Alerts (Issues and Transactions), Dashboards, Teams, and Organizations, using code. This can help your team save time provisioning Sentry while giving you the option to work from an interface you are already familiar with. Please refer to the [documentation](https://registry.terraform.io/providers/jianyuan/sentry/latest/docs) for information on how to get started.


## Setup
1. `terraform init`
2. Either:
 a. `export SENTRY_AUTH_TOKEN = DSN_KEY`
 OR
 b. Follow instructions [here](https://registry.terraform.io/providers/jianyuan/sentry/latest/docs#example-usage)
3. `terraform plan` to check what resources Terraform will create based on the `main.tf` file.

## Run

1. `terraform apply`

## Docs

- Underlying Terraform provider documentation: https://registry.terraform.io/providers/jianyuan/sentry/latest/docs
- Terraform basics: https://www.terraform.io/intro

## GIF example
![sentry_tf_demo](https://user-images.githubusercontent.com/108364755/179266859-7dbcdde9-dcde-4774-b60c-5e1b7f5a123a.gif)


