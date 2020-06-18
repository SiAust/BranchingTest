## Some useful tips for Git and Github

#### Working with a remote repository from terminal
- `git remote` Shows the remote references
- `git remote show <name>` Shows more info about the specific
reference.
- `git remote remove <name>` if you make an error in the URL you can remove
reference and add the correct address using `git remote origin <URL>`
- `git add *.java` adds all java files in the current working directory
to the staging area ready to be committed.
- `git clone <URL>` copies (clones) a repository from a URL.
- In console commands use the command name followed by `-help` to
see the options.
- `[]` elements are optional
- `<>` elements are required
- `git branch -m <oldname> <newname>` to rename a local branch
- `git branch -m <newname>` rename current branch
- `git branch` shows all branches and currently active branch
- `git push -d origin <branchname>` delete a remote branch
- `git branch -d <branchname>` delete a local branch
`-d == --delete` and `-D == --delete --force` deletes the local 
branch irrespective of merge status.
- `git merge`
- `git fetch`
- `git pull` pulls the latest commit of the current branch
- Branch names should use lowercase and words separated by a "/". I.e.
`test/branch`, `wip`, `feat/json`
- `git checkout <branch name>` checkout into a branch.

#### Misc.
- `git log` Shows info about recent commits, including their hash
identifier
- `git status` Shows any tracked files which have been altered since
last commit. The text will be red if not added to the
staging area, yellow if staged ready for commit.