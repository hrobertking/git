# git
An example gitconfig file with aliases I have found useful over the years. These aliases are provided not only as useful tools but also as a simple learning device so that others may learn how to do things using the git command line.

Aliases:
- **authored**: Displays changes in a branch, e.g., `git authored` or `git author "Robert King"`.
- **created**: Shows the date and time the specified branch was created in ISO format. If no branch is specified, all branches are listed in alphabetical order (default) or by date-created order when the `--by-date argument` is passed.
- **delta**: Identifies files modified in the specified commit.
- **mkbranch**: Makes a branch using a parent branch, e.g., `git mkbranch issue-999 release-0.0.1`. This alias assumes your remotes are named 'upstream' and 'origin'.
- **mvbranch**: Moves a branch, e.g., `git mvbranch old-branch-name new-branch-name`. This alias assumes your remote is named 'origin'.
- **rmbranch**: Removes a branch, e.g., `git rmbranch issue-999`. This alias assumes your remote is named 'origin' and that you have a 'master' branch.
- **rollback**: Rolls changes back to the specified commit and optionally does a force push, e.g., `git rollback 12345abcde`.
- **unapply**: Unapplies a stash, e.g., `git unapply` or `git unapply 3`. If no stash index is specified, the last stash is unapplied.
- **unstash**: Applies work previously stashed and drops the stashed work, e.g. `git unstash` or `git unstash 3`. If no stash index is specified, the last stash is applied and dropped.
- **update**: Updates a branch to a new upstream remote.
- **workon**: Switches branches given a partial branch name. If all changes in the current branch are staged, this will automatically stash them; however, if there are unstaged changes in the current branch, an error message is given.
