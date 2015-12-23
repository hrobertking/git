# git
An example gitconfig file with aliases I have found useful over the years. These aliases are provided not only as useful tools but also as a simple learning device so that others may learn how to do things using the git command line.

Aliases:
- **authored**: Displays changes in a branch. Usage examples: `git authored` or `git authored "John Doe"`.
- **created**: Shows the date and time the specified branch was created in ISO format. If no branch is specified, all branches are listed in alphabetical order (default) or by date-created order when the `--by-date argument` is passed. Usage examples: `git created` or `git created --by-date`
- **delta**: Identifies files modified in the specified commit. Usage examples: `git delta 12345abcd`
- **mkbranch**: Makes a branch using a parent branch. This alias assumes your remotes are named 'upstream' and 'origin'. Usage examples: `git mkbranch issue-999 release-0.0.1`
- **mvbranch**: Moves (renames) a branch. This alias assumes your remote is named 'origin'. Usage examples: `git mvbranch old-branch-name new-branch-name`
- **rmbranch**: Removes a branch. This alias assumes your remote is named 'origin' and that you have a 'master' branch. Usage examples: `git rmbranch issue-999`
- **rollback**: Rolls changes back to the specified commit and optionally does a force push. Usage examples: `git rollback 12345abcde`
- **unapply**: Unapplies a stash that was previously applied. If no stash index is specified, the last stash is unapplied. Usage examples: `git unapply` or `git unapply 3`
- **unstash**: Applies work previously stashed and drops the stashed work. If no stash index is specified, the last stash is applied and dropped. Usage examples: `git unstash` or `git unstash 3`
- **update**: Updates a branch to a new upstream remote. Usage examples: `git update my-branch next-release-push`
- **workon**: Switches branches given a partial branch name. If all changes in the current branch are staged, this will automatically stash them; however, if there are unstaged changes in the current branch, an error message is given. Usage examples: `git workon issue-123`
