# GitHub Issue Creator Action

This action creates a new GitHub issue.

## Inputs

### `token`

**Required** GitHub token.

### `title`

**Required** Issue title.

### `body`

Issue body.

### `assignees`

Issue assigness. A formatted multi-line string using the pipe (|) symbol.

## Outputs

### `issue`

The issue as a JSON string.

## Example usage

```yaml
uses: lionelrrivas/github-issue-creator@v1
  with:
    token: ${{ secrets.GITHUB_TOKEN }}
    title: Title
    body: Body
    assignees: |
      lionelrrivas
```
