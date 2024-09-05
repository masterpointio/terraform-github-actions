<!-- BEGIN_TF_DOCS -->
<!-- prettier-ignore-start -->

## Requirements

| Name | Version |
|------|---------|
| terraform | >=1.3.0 |
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
| [github_actions_organization_variable.this](https://registry.terraform.io/providers/integrations/github/latest/docs/resources/actions_organization_variable) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| selected_repository_ids | An array of repository ids that can access the organization secret. | `list(string)` | `null` | no |
| value | Value of the variable. | `string` | n/a | yes |
| variable_name | Name of the variable. | `string` | n/a | yes |
| visibility | Configures the access that repositories have to the organization variable. Must be one of `all`, `private`, `selected`. | `string` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| created_at | n/a |
| updated_at | n/a |
| value | n/a |
| variable_name | n/a |


## Contributing

Contributions are welcome and appreciated!

Found an issue or want to request a feature? [Open an issue](TODO)

Want to fix a bug you found or add some functionality? Fork, clone, commit, push, and PR and we'll check it out.

If you have any issues or are waiting a long time for a PR to get merged then feel free to ping us at [hello@masterpoint.io](mailto:hello@masterpoint.io).

## Built By

[![Masterpoint Logo](https://i.imgur.com/RDLnuQO.png)](https://masterpoint.io)

<!-- prettier-ignore-end -->
<!-- END_TF_DOCS -->