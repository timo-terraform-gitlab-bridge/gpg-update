---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "gpgupdate_data_source Data Source - terraform-provider-gpgupdate"
subcategory: ""
description: |-
  Sample data source in the Terraform provider gpgupdate.
---

# gpgupdate_data_source (Data Source)

Sample data source in the Terraform provider gpgupdate.

## Example Usage

```terraform
data "gpgupdate_data_source" "example" {
  sample_attribute = "foo"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `sample_attribute` (String) Sample attribute.

### Read-Only

- `id` (String) The ID of this resource.

