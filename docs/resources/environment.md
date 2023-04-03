---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "kaleido_environment Resource - terraform-provider-kaleido"
subcategory: ""
description: |-
  
---

# kaleido_environment (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `consensus_type` (String)
- `consortium_id` (String)
- `env_type` (String)
- `name` (String)

### Optional

- `block_period` (Number)
- `chain_id` (Number)
- `description` (String)
- `multi_region` (Boolean)
- `prefunded_accounts` (Map of String)
- `release_id` (String)
- `shared_deployment` (Boolean) The decentralized nature of Kaleido means an environment might be shared with other accounts. When true only create if name does not exist, and delete becomes a no-op.
- `test_features_json` (String)

### Read-Only

- `id` (String) The ID of this resource.

