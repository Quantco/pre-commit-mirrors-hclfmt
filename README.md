# hclfmt mirror

Mirror of hclfmt for pre-commit with conda as a language.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For hclfmt: see [here](https://github.com/hashicorp/hcl/tree/main/cmd/hclfmt)

## Using hclfmt with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-hclfmt
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: hclfmt-conda
```
