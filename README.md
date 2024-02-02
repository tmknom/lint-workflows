# lint-workflows

Template repository for Reusable Workflows.

## Description

A collection of lint workflows implemented as Reusable Workflows for GitHub Actions.

## Usage

### Reusable Workflows

```yaml
jobs:
  call:
    uses: tmknom/lint-workflows/.github/workflows/reusable-workflows.yml@v0
    permissions:
      contents: read
```

## Release notes

See [Releases](https://github.com/tmknom/lint-workflows/releases).

## License

Apache 2 Licensed. See [LICENSE](/LICENSE) for full details.
