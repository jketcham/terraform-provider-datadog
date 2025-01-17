---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "datadog_api_key Resource - terraform-provider-datadog"
subcategory: ""
description: |-
  Provides a Datadog API Key resource. This can be used to create and manage Datadog API Keys.
---

# datadog_api_key (Resource)

Provides a Datadog API Key resource. This can be used to create and manage Datadog API Keys.

## Example Usage

```terraform
# Create a new Datadog API Key
resource "datadog_api_key" "foo" {
  name = "foo-application"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **name** (String) Name for API Key.

### Read-Only

- **id** (String) The ID of this resource.
- **key** (String, Sensitive) The value of the API Key.

## Import

Import is supported using the following syntax:

```shell
terraform import datadog_api_key.foo 11111111-2222-3333-4444-555555555555
```
