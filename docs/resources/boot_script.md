---
page_title: "morpheus_boot_script Resource - terraform-provider-morpheus"
subcategory: ""
description: |-
  Provides a Morpheus boot script resource
---

# morpheus_boot_script

Provides a Morpheus boot script resource

## Example Usage

```terraform
resource "morpheus_boot_script" "tf_example_boot_script" {
  name    = "TF Example Boot Script"
  content = "ls"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `name` (String) The name of the boot script

### Optional

- `content` (String) The content of the boot script

### Read-Only

- `id` (String) The ID of the boot script

## Import

Import is supported using the following syntax:

```shell
terraform import morpheus_boot_script.tf_example_boot_script 1
```