# Automation Host Prerequisites
- [Automation Host Prerequisites](#automation-host-prerequisites)
  - [Automation Host Setup](#automation-host-setup)
    - [Terraform](#terraform)
    - [IBM Cloud Terraform Provider](#ibm-cloud-terraform-provider)
    - [PowerVS CLI](#powervs-cli)
    - [Git [*OPTIONAL*]](#git-optional)

## Automation Host Setup

Install the following packages on the automation host. Select the appropriate install binaries based on your automation host platform - Mac/Linux/Windows

### Terraform

**Terraform >= 0.12.2, < 0.13**: Please refer to the [link](https://learn.hashicorp.com/terraform/getting-started/install.html) for instructions on installing Terraform. For validating the version run `terraform version` command after install.

### IBM Cloud Terraform Provider

**IBM Cloud Terraform Provider v1.9.0, < v1.10.0 **: Please refer to the section "Install the IBM Cloud Provider plug-in" from the [link](https://cloud.ibm.com/docs/terraform?topic=terraform-getting-started#install) for instructions on installing the provider plugin. The Terraform provider is for specific versions of Terraform and Terraform 0.12.x requires the use of v1.9.0 of the IBM Cloud Terraform Provider.

### PowerVS CLI

**PowerVS CLI**: Please download and install the CLI by referring to the following [instructions](https://cloud.ibm.com/docs/power-iaas-cli-plugin?topic=power-iaas-cli-plugin-power-iaas-cli-reference). Alternatively, you can use IBM Cloud [shell](https://cloud.ibm.com/shell) directly from the browser itself.

### Git [*OPTIONAL*]

**Git**: Please refer to the [link](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) for instructions on installing Git.
