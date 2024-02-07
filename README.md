# lint-workflows

A collection of lint workflows.

## Description

A collection of lint workflows implemented as Reusable Workflows for GitHub Actions.

## Usage

### GitHub Actions

```yaml
jobs:
  call:
    uses: tmknom/lint-workflows/.github/workflows/github-actions.yml@v0
    permissions:
      contents: read
```

### Composite Action

```yaml
jobs:
  call:
    uses: tmknom/lint-workflows/.github/workflows/composite-action.yml@v0
    permissions:
      contents: read
```

### Reusable Workflows

```yaml
jobs:
  call:
    uses: tmknom/lint-workflows/.github/workflows/reusable-workflows.yml@v0
    permissions:
      contents: read
```

## Related projects

- [configurations](https://github.com/tmknom/configurations): Collection of configurations.
- [template-composite-action](https://github.com/tmknom/template-composite-action): Template repository for Composite Action.
- [template-reusable-workflows](https://github.com/tmknom/template-reusable-workflows): Template repository for Reusable Workflows.
- [cross-yamllint-action](https://github.com/tmknom/cross-yamllint-action): Run [yamllint][yamllint] with configuration shared across repositories.

## Release notes

See [GitHub Releases][releases].

## License

Apache 2 Licensed. See [LICENSE](LICENSE) for full details.

[yamllint]: https://github.com/adrienverge/yamllint
[releases]: https://github.com/tmknom/lint-workflows/releases
