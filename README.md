# DomoticASW commitlinst

This action is meant to be used across all the suitable repositories inside the organization.

It automatically checks out the repository and setup Node.

## Requirements:
The repository should have [commitlint](https://commitlint.js.org) installed and configured (you should be able to run `npx commitlint`).

Example:
```yaml
# ...
jobs:
  release:
    name: ...
    runs-on: ...
    steps:
      - name: commitlint
        uses: DomoticASW/commitlint@1.0.0
```
