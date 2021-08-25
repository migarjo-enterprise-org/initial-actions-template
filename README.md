# Initial Actions for Templates
This is a demo repository for creating Actions that run on a newly-created repository. It contains the following two actions:
- Create first issue: This runs after the first commit on a newly-created repository based on this template. It creates an issue instructing users to perform some first steps
- Customize repo: This is a manually-initiated Action that will clone a repository based on selected inputs, and copy its contents into this repo.

*Note:* Since the "Customize repo" action clones another repository other than this one, it requires an additional Personal Access Token that has access to any repos that need to be cloned. To enable this, create an Actions Secret at the organization level with a PAT scoped to "repo". The key for this token should be `GH_ORG_TOKEN`.

## Actions Documentation:
Actions can be a powerful automation tool to assist your GitHub workflows. Below are some links that will provide you with some references and tutorials to help you get started:
- [Learn GitHub Actions Tutorials](https://docs.github.com/en/actions/learn-github-actions)
  - [Introduction to GitHub Actions](https://docs.github.com/en/actions/learn-github-actions/introduction-to-github-actions)
  - [Essential Features of GitHub Actions](https://docs.github.com/en/actions/learn-github-actions/essential-features-of-github-actions)
  - [Sharing secriets with an organization](https://docs.github.com/en/actions/learn-github-actions/sharing-workflows-with-your-organization#sharing-secrets-within-an-organization)
- [Actions reference material](https://docs.github.com/en/actions)
  - [Workflow Syntax](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions)
  - [Context and Expression Syntax](https://docs.github.com/en/actions/reference/context-and-expression-syntax-for-github-actions)
    - This covers the metadata provided to the Actions environment for use in your automation, as well as syntax for how to use them
  - [Events that trigger workflows](https://docs.github.com/en/actions/reference/events-that-trigger-workflows)

<!-- Add another description here -->
## Description
