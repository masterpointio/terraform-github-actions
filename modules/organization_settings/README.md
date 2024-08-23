# github_organization_settings

This module allows setting standard github organization settings for public profile and also for managing permissions.

<!-- BEGIN_TF_DOCS -->
<!-- prettier-ignore-start -->

## Requirements

| Name | Version |
|------|---------|
| terraform | >=1.3 |
| github | >= 6.2.3 |

## Providers

| Name | Version |
|------|---------|
| github | >= 6.2.3 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [github_organization_settings.this](https://registry.terraform.io/providers/integrations/github/latest/docs/resources/organization_settings) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| advanced_security_enabled_for_new_repositories | Whether or not advanced security is enabled for new repositories. Defaults to false. | `bool` | `null` | no |
| billing_email | The billing email address for the organization. | `string` | n/a | yes |
| blog | The blog URL for the organization. | `string` | `null` | no |
| company | The company name for the organization. | `string` | `null` | no |
| default_repository_permission | The default permission for organization members to create new repositories. Can be one of read, write, admin, or none. Defaults to read. | `string` | `null` | no |
| dependabot_alerts_enabled_for_new_repositories | Whether or not dependabot alerts are enabled for new repositories. Defaults to false. | `bool` | `null` | no |
| dependabot_security_updates_enabled_for_new_repositories | Whether or not dependabot security updates are enabled for new repositories. Defaults to false. | `bool` | `null` | no |
| dependency_graph_enabled_for_new_repositories | Whether or not dependency graph is enabled for new repositories. Defaults to false. | `bool` | `null` | no |
| description | The description for the organization. | `string` | `null` | no |
| email | The email address for the organization. | `string` | `null` | no |
| has_organization_projects | Whether or not organization projects are enabled for the organization. | `bool` | `null` | no |
| has_repository_projects | Whether or not repository projects are enabled for the organization. | `bool` | `null` | no |
| location | The location for the organization. | `string` | `null` | no |
| members_can_create_internal_repositories | Whether or not organization members can create new internal repositories. For Enterprise Organizations only. | `bool` | `null` | no |
| members_can_create_pages | Whether or not organization members can create new pages. Defaults to true. | `bool` | `null` | no |
| members_can_create_private_pages | Whether or not organization members can create new private pages. Defaults to true. | `bool` | `null` | no |
| members_can_create_private_repositories | Whether or not organization members can create new private repositories. Defaults to true. | `bool` | `null` | no |
| members_can_create_public_pages | Whether or not organization members can create new public pages. Defaults to true. | `bool` | `null` | no |
| members_can_create_public_repositories | Whether or not organization members can create new public repositories. Defaults to true. | `bool` | `null` | no |
| members_can_create_repositories | Whether or not organization members can create new repositories. Defaults to true. | `bool` | `null` | no |
| members_can_fork_private_repositories | Whether or not organization members can fork private repositories. Defaults to false. | `bool` | `null` | no |
| name | The name for the organization. | `string` | `null` | no |
| secret_scanning_enabled_for_new_repositories | Whether or not secret scanning is enabled for new repositories. Defaults to false. | `bool` | `null` | no |
| secret_scanning_push_protection_enabled_for_new_repositories | Whether or not secret scanning push protection is enabled for new repositories. Defaults to false. | `bool` | `null` | no |
| twitter_username | The Twitter username for the organization. | `string` | `null` | no |
| web_commit_signoff_required | Whether or not commit signatures are required for commits to the organization. Defaults to false. | `bool` | `null` | no |

## Outputs

| Name | Description |
|------|-------------|
| id | The ID of the organization settings. |


## Contributing

Contributions are welcome and appreciated!

Found an issue or want to request a feature? [Open an issue](TODO)

Want to fix a bug you found or add some functionality? Fork, clone, commit, push, and PR and we'll check it out.

If you have any issues or are waiting a long time for a PR to get merged then feel free to ping us at [hello@masterpoint.io](mailto:hello@masterpoint.io).

## Built By

[![Masterpoint Logo](https://i.imgur.com/RDLnuQO.png)](https://masterpoint.io)

<!-- prettier-ignore-end -->
<!-- END_TF_DOCS -->