<!-- markdownlint-disable -->

## Inputs

| Name | Description | Default | Required |
|------|-------------|---------|----------|
| group-by | Group by query | .stack\_slug \| split("-") \| [.[0], .[2]] \| join("-") | false |
| sort-by | Sort by query | .stack\_slug | false |
| stacks | Stacks list | true | true |


## Outputs

| Name | Description |
|------|-------------|
| result | Matrix unlimited structure |
<!-- markdownlint-restore -->
