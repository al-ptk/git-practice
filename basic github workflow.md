The basic git workflow could be something like this:

- Create a new branch, a new file and a new commit.
- Make a change, commit it and push the new branch to the repository
  - You can set a new upstream branch with the command `git push -u origin HEAD`. This command will take the current branch and push it to upstream. If the branch doesn't exists, it creates one.
