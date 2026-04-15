# gersemi-pre-commit

This repository provides [pre-commit](https://pre-commit.com/) hook definition for [gersemi](https://github.com/BlankSpruce/gersemi) and a dummy package that allows installing gersemi based on wheels available on PyPI.

## [pre-commit](https://pre-commit.com/) hook

You can use gersemi with a pre-commit hook by adding the following to `.pre-commit-config.yaml` of your repository:

```yaml
repos:
- repo: https://github.com/BlankSpruce/gersemi-pre-commit
  rev: 0.20.0
  hooks:
  - id: gersemi
```
