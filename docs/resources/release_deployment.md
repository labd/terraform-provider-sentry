---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "sentry_release_deployment Resource - terraform-provider-sentry"
subcategory: ""
description: |-
  
---

# sentry_release_deployment (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `environment` (String) The environment this deployment is for.
- `organization` (String) The slug of the organization the deploy belongs to.
- `version` (String) The version identifier of the release.

### Optional

- `name` (String) The optional name of the deploy.
- `projects` (List of String) The optional list of projects to deploy.
- `url` (String) The optional URL that points to the deploy.

### Read-Only

- `id` (String) The ID of this resource.


