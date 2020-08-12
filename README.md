# CDAT .github

This repository contains Github Action workflows and custom actions.

# Useful links

- [GitHub actions](https://docs.github.com/en/actions)
- [GitHub actions repo](https://github.com/actions)
- [Using workflow templates](https://docs.github.com/en/actions/configuring-and-managing-workflows/sharing-workflow-templates-within-your-organization#using-a-workflow-template)

# Templates

## First interactions

This workflow will comment on new issue/PR when it's a user's first time contributing.

There are two customizable fields.

- issue-message
- pr-message

### Example
```yaml
issue-message: |
  Thank you for opening this issue.

  Here are some resources:
  - [CDAT](https://cdat.llnl.gov)
```

## Stale issues

This workflow will scan issues and PRs for 30 days of inactivity and label them stale.
