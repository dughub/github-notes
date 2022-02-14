# Renaming
How to rename branches etc in git

# Rename a Git Branch
_Note: This will only work after the first commit_
git branch -m oldname newname

## Rename Branch 'master' to 'main'
_Note: This will only work after the first commit_
git branch -m master main
git pull --rebase origin main
git push origin main


# Rename a file
To rename a file that is already commited to the repo:<br>
1. Rename the file e.g., `mv oldname.txt newname.txt`<br>
2. git add both file names (new and old):
```
git add oldname.txt
git add newname.txt
```

# Resources
https://www.git-tower.com/learn/git/faq/git-rename-master-to-main/
