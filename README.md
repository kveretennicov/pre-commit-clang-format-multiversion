# "Batteries included" clang-format pre-commit hook

Example `.pre-commit-config.yaml`:

```yaml
repos:
  - repo: https://github.com/kveretennicov/clang-format-pre-commit-multiversion
    rev: master
    hooks:
      - id: "clang-format:3.8"
        args: ["-i", "-style=file", "-style-fallback=none"]
```

