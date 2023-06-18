# GitHub CLI Cheatsheet

This cheatsheet provides a quick reference for common GitHub CLI commands.

## Installation

Install GitHub CLI by following the instructions provided in the [GitHub CLI documentation](https://cli.github.com/).

## Authentication

Authenticate with your GitHub account by running the following command:

```bash
gh auth login

```

Follow the interactive prompts to complete the authentication process.

## Repository Operations

- **Create a repository**: `gh repo create [repository-name]`
- **Clone a repository**: `gh repo clone [repository-name]`
- **View repository details**: `gh repo view [repository-name]`
- **List repositories**: `gh repo list`

## Pull Request Operations

- **Create a pull request**: `gh pr create`
- **List pull requests**: `gh pr list`
- **View a pull request**: `gh pr view [pull-request-number]`
- **Merge a pull request**: `gh pr merge [pull-request-number]`
- **Close a pull request**: `gh pr close [pull-request-number]`

## Issue Operations

- **Create an issue**: `gh issue create`
- **List issues**: `gh issue list`
- **View an issue**: `gh issue view [issue-number]`
- **Close an issue**: `gh issue close [issue-number]`

## Workflow Operations

- **View workflow runs**: `gh workflow list`
- **View workflow run details**: `gh workflow view [workflow-run-id]`
- **Re-run a workflow**: `gh workflow run [workflow-file]`

- **watch a repository for new pull requests, issues, or other events** `gh run watch [repository-name]`

## Additional Resources

For a complete list of GitHub CLI commands and their usage, refer to the [GitHub CLI documentation](https://cli.github.com/manual/).

## Contributing

Contributions are welcome! If you have any suggestions or improvements for this cheatsheet, feel free to open an issue or submit a pull request.

## License

This cheatsheet is released under the [MIT License](LICENSE).
