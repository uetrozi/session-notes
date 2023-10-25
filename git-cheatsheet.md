| Git Command             | Git task                                         |
| ----------------------- | ------------------------------------------------ |
| git status              | List all files that have changed and their state |
| git add <filename>      | Add a file to the stage                          |
| git commit -m "add foo" | Create a commit including all staged files       |
| git log --oneline       | Show the commit history                          |
| git push                | Upload content to the remote repository          |
| git pull                | Download content from the remote repository      |
| git remote -v           | shows the origin adress of the git repo          |
| git switch -c <name>    | creates new branch and changes into it   |
| git switch <name>       | changes into named branch                        |


## Connecting your local repository to a new remote repository

The first thing you need to do is create a new empty remote repository on GitHub. You will then see some hints e.g. "...or push an existing repository from the command line". Copy the commands from GitHub and execute them in your local project folder.

Example:

git remote add origin git@github.com:GitHubUsername/repository-name.git
git branch -M main
git push -u origin main
