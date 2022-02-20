# Mistakes

## Fix incorrect remote url
`git remote set-url [new-url]`


## Squashing Commits
From git-tower.com:<br>
To "squash" in Git means to combine multiple commits into one. 
You can do this at any point in time (by using Git's "Interactive Rebase" feature), 
though it is most often done when merging branches.

Please note that there is no such thing as a stand-alone git squash command. 
Instead, squashing is rather an option when performing other Git commands like interactive rebase or merge.


## Undo git add
If you decided a file should not be part of a commit you can remove it from staging with this command:<br>
`git restore --staged [filename]`

# Resources
[stackoverflow - "How to change the URI (URL) for a remote Git repository?"](https://stackoverflow.com/questions/2432764/how-to-change-the-uri-url-for-a-remote-git-repository)
[git tower - How to Undo git add](https://www.git-tower.com/learn/git/faq/undo-git-add/)
[stackoverflow -  rebase my last n commits](https://stackoverflow.com/questions/5189560/squash-my-last-x-commits-together-using-git)
[git manual rebase](https://git-scm.com/docs/git-rebase#_interactive_mode)
[git tower - git squash](https://www.git-tower.com/learn/git/faq/git-squash/)
[git tower - first aid kit for git](https://www.git-tower.com/learn/git/first-aid-kit)
