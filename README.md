# pre-commit-configs

A centralized repository to define the pre-commit hooks used across all of my repositories

## Usage

In the root directory of the repository, place the following contents into `.pre-commit-config.yaml`

```yaml
minimum_pre_commit_version: '2.20.0'

repos:
  - repo: https://github.com/bsakdol/pre-commit-hooks
    rev: v0.1.0
    hooks:
      - id: meta-hook
```