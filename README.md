- `git init`: initialize current folder as a git repository
- `git clone`: brings the git repo from <URL> to current folder
- `git status`: tells us what we need to know about our repository

- `git add <FILE>`: adds <FILE> to the staging area or index
- `git commit`: open a text editor to write commit message
  - `git commit -m "MESSAGE"`: writes MESSAGE as a commit without a text editor

- `git log`: shows the log (history) of our commits
  - `git log --oneline`: shows the shorted oneline commit

- `git diff`: compare current uncommitted state with last know git state
  - `git diff --staged`: runs diff between the staging area and last known state

- `git diff HEAD~<NUMBER>`: compares HEAD with commit <NUMBER> ago (relative to HEAD)
- `git diff <HASH>`: compares HEAD with the commit in <HASH>
