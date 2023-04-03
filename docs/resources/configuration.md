---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "kaleido_configuration Resource - terraform-provider-kaleido"
subcategory: ""
description: |-
  
---

# kaleido_configuration (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `consortium_id` (String)
- `environment_id` (String)
- `membership_id` (String)
- `name` (String)
- `type` (String)

### Optional

- `details` (Map of String)
- `details_json` (String)
- `timeouts` (Block, Optional) (see [below for nested schema](#nestedblock--timeouts))

### Read-Only

- `id` (String) The ID of this resource.
- `last_updated` (Number)

<a id="nestedblock--timeouts"></a>
### Nested Schema for `timeouts`

Optional:

- `create` (String)
- `delete` (String)
- `update` (String)

