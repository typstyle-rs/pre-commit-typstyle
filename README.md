# pre-commit-typstyle

typstyle for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit
For typstyle: see https://github.com/typstyle-rs/typstyle

## Using typstyle with pre-commit

Add this to your `.pre-commit-config.yaml`

```yaml
  - repo: https://github.com/typstyle-rs/pre-commit-typstyle
    rev: ''  # Use the sha / tag you want to point at
    hooks:
      - id: typstyle
```
