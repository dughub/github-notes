# Setup - Git Hub
How to set up github on Ubuntu

# Setup Git
Check that git is installed:
`git --version`
If git is not installed - `apt-get install git`

Check git is confgured:
`git config --list`
Should show at least a user.name and user.email, otherwise...

`git config --global user.name "John Doe"`
`git config --global user.email john.doe@git.com`
`git config --global core.editor nano`
`git config --global init.defaultBranch main`

# Initialise a Repo
If the code / folder already exists:
cd into the dir
`git init`

To init a new repo in a new folder
`git init MyRepo`

# Create a readme and add to git
`touch readme.md`
`nano readme.md`
`git add readme.md`

# Commit changes
git commit -m "some message"

# Creata a Repo on GitHub
Self explanatory

# Push changes to GitHub (and login)
`git remote add origin https:github.com/[username]/[repo].git`
`git push origin [branchname]`


# Resources
https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup
https://www.howtoforge.com/tutorial/install-git-and-github-on-ubuntu/
https://docs.github.com/en/get-started/quickstart/set-up-git
https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls
