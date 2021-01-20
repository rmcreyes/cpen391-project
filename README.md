# cpen391-project
The master repository for our CPEN 391 project. Contains submodules for our other repositories.

## Getting Started

To clone the repository and have all the submodules' contents included, use the following command:

```bash
git clone https://github.com/rmcreyes/cpen391-project.git --recurse-submodules
```

When making changes to the submodules, make sure to do the following:

1. Merge changes to the submodules in their respective repositories
2. Checkout the updated main branch in the submodule (this will show a diff when you use `git status` in the main repository)
3. Commit and push the change to the reference of the submodule in the main repository
