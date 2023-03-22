# Merge Skipped
Steps that reproduce a skipped merge by git, i faced an issue in a merge, where the changes were not added to master branch, the commit id was present in the pull request but the changes were not showed in the pull request and once the merge was completed the changes were not applied in master branch.

## Steps

- Create the branch and add a new file (generate develop branch from this same branch, this way both branches will share the same initial commit id)
- Add a new line in develop branch and merge that change to master using squash commit (That line will exists in both branches master and develop)
- Remove that same line in develop
- Try to merge to master, the line will not be removed from master but even so both branches will be shown as merged.
