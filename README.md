# git basics

- `git init`: initialize git repository in current working directory
- `git status`: gives you the status
- `git add <FILE>`: adds <FILE> to the staging area
- `git commit`: creates a commit, you provide message

- `git log`: shows you the log of your commits
    - `git log --oneline`: shows you the one line version of log

- `HEAD`: where you currently are (the version of the files on your computer)
- `git diff HEAD~<NUM> <FILE>`: compares current file to file <NUM> ago
    - `git diff <HASH> <FILE>`: compares current file to <HASH> version

- Use `git status` to help you find the commands to unstage or restore file
- `git checkout <HASH> <FILE>`: restore <FILE> to version in <HASH>`
    - if you run `git checkout <HASH>` without the <FILE>
    - You can fix this by running `git checkout main`
