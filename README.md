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
- `git push`- Uploads all file commits on your local machine to GitHub

