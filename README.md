# Git Practise
Introductory GitHub lesson

## Git Commands
Here are a lot of commands used in Git and what their purposes are

### Create repositories
- `git init` - this command turns an existing directory into a repository
- `git clone` - this command clones (downloads) a repository that exists on GitHub already onto your local machine

### Make changes
Below are some commands you will often use when making changes to a repository and pushing those changes:

- `git status` - not necessary but useful to spot what files have been changed and what files are ready to be committed
- `git add <file>` - this command prepares snapshots of the file to be committed (we can do this for all files at once with `.` instead of `<file>`)
- `git commit -m "descriptive message"` - records file snapshots permanently (what you make with `git add`) along with a descriptive message of what has been changed
- `git diff` - shows file differences that are not yet staged
- `git push`- Uploads all file commits on your local machine to GitHub

### Branches
Branches are an important part of working with git, allowing you to make changes to your repo without affecting the main branch until ready.
- `git branch <branch-name>` - creates a new branch (note running this command with the `-d` flag deletes the specified branch)
- `git checkout <branch-name>` - switches to the specified branch and updates the working directory (note you can create a branch and immediately switch to it using the `-b` flag)
- `git merge <branch>` - combines the specified branch's history into the current branch.