# git-learning
This is the notes from version control course from Coursera: https://www.coursera.org/learn/introduction-to-version-control/

## Git Commands

1. `git log (—pretty=oneline)`: Shows the commit history in one line format.
2. `git stash`: This command temporarily saves changes that are not ready to be committed, allowing you to switch branches without committing your changes. It takes your modified tracked files and staged changes, saves them away for later use, and then reverts them to the latest commit.
3. `git stash pop`: This command retrieves the changes stored in the stash and applies them to your current working directory, deleting them from the stash.
4. `git stash drop`: This command removes a single stashed state from the stash list.
5. `git stash list`: This command lists all stashed changes.
6. `git blame (-L) (start line, end line) [file name]`: Shows what revision and author last modified each line of a file.
7. `git remote add [alias] [url]`: Adds a remote repository.
8. `git status`: Checks the status of your repository.
9. `git push [alias] [branch]`: Pushes your changes to a remote repository.
10. `git diff`: Shows differences between your working directory and the index.
11. `git branch [branch name]`: This command creates a new branch with the specified name.
12. `git checkout -b [branch name]`: Creates a new branch and switches to it.
13. `git add .`: Adds all new and changed files to the staging area.
14. `git pull`: Fetches and downloads content from the remote repository and immediately updates the local repository to match that content.
15.  `git rebase`: Moves or combines a sequence of commits to a new base commit. It's used to integrate changes from one branch into another.
16.   `git commit -m`: Commits staged changes with a message.
17. `git merge [alias]/[branch]`: Merges changes from the specified branch.
18. 
19. `gh repo clone [url]`: Clones a repository from the specified URL using GitHub CLI.
20. `gh auth login`: Logs in to GitHub CLI.


## Here are some commonly used Unix commands:

1. `cd`: Change directory (`~` for home directory, `/` for root directory)
2. `touch`: Create a new file
3. `mkdir`: Make a new directory
4. `code`: Open a file in VSCode
5. `man`: Manual (e.g., `man ls`)
6. `ls`: List files in the current directory (`l` for long format, `a` for all files including hidden)
7. `pwd`: Print full path
8. `cp`: Copy files or directories
9. `mv`: Move or rename files
10. `rm`: Remove a file or directory
11. `cat`: Read or concatenate files
12. `less`: Display the content of a file one page at a time
13. `vim`: Edit file in bash
14. `chmod`: Change mode (e.g., `chmod 755 filename`)
15. `cat`: Print the content of a file
16. `wc`: Word count (`-w` for words)
17. `|`: Pipe output of one command as input to another
18. `>`: Redirect output to a file (e.g., `ls -l > output.txt`)
19. `<`: Take input from a file
20. `less`: Check the content of a file
21. `2>`: Redirect error output (`2>&1` to redirect both stdout and stderr)
22. `grep`: Search for a pattern in a file or output (`i` for case insensitive, `w` for exact match)
