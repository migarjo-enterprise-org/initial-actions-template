# Initial Actions for Templates
This is a demo repository for creating Actions that run on a newly-created repository. It contains the following two actions:
- Create first issue: This runs after the first commit on a newly-created repository based on this template. It creates an issue instructing users to perform some first steps
- Customize repo: This is a manually-initiated Action that will clone a repository based on selected inputs, and copy its contents into this repo.

*Note:* Since the "Customize repo" action clones another repository other than this one, it requires an additional Personal Access Token that has access to any repos that need to be cloned. To enable this, create an Actions Secret at the organization level with a PAT scoped to "repo". The key for this token should be `GH_ORG_TOKEN`.

<!-- Add another description here -->
## Description
