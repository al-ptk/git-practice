The basic git workflow could be something like this:

- Create a new branch, a new file and a new commit.
- Make a change, commit it and push the new branch to the repository
  - You can set a new upstream branch with the command `git push -u origin HEAD`. This command will take the current branch and push it to upstream. If the branch doesn't exists, it creates one. [Source is stack overflow](https://stackoverflow.com/questions/6089294/why-do-i-need-to-do-set-upstream-all-the-time)
- Then, a message on the repo's github page saying that the new branch had pushes, and a button saying 'Compare and pull request' will show up. 
- A pull request is a procedure to verify and merge different branches to the main codebase.
- If you click that button, you get redirected to the 'Open a pull request page.' In that page, you get to entitle and describe the pull request.
- Once you open a pull request, it will be availabe to change reviews and approval. In this state, you can still make and push changes.
- Once you merge the branch to main at github, you go back to the main branch and do a `git pull origin main` to update your local main branch.