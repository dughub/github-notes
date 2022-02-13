# Setup - Git Hub
How to set up github on Ubuntu

# Setup Git
Check that git is installed:<br>
`git --version`<br>
If git is not installed - `apt-get install git`<br>


# git config
Check git is confgured:<br>
`git config --list`<br>
Should show at least a user.name and user.email, otherwise...<br>

`git config --global user.name "John Doe"`<br>
`git config --global user.email john.doe@git.com`<br>
`git config --global core.editor nano`<br>
`git config --global init.defaultBranch main`

## Remove a git config entry (unset)
`git config --global --unset user.name`


# Initialise a Repo
If the code / folder already exists:<br>
cd into the dir<br>
`git init`

To init a new repo in a new folder<br>
`git init MyRepo`

# Create a readme and add to git
`touch readme.md`<br>
`nano readme.md`<br>
`git add readme.md`<br>

# Commit changes
`git commit -m "some message"`

# Creata a Repo on GitHub
Self explanatory


# Create a PAT (Personal Access Token)
On github.com:<br>
Settings => Developer Settings => Personal access tokens

# Push changes to GitHub (and login)
`git remote add origin https:github.com/[username]/[repo].git`<br>
`git push origin [branchname]`<br>
Enter username`<br>
Enter password`<br>

# Resources
[git-scm first time git setup](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)<br>
[howtoforge - install git and github](https://www.howtoforge.com/tutorial/install-git-and-github-on-ubuntu/)<br>
[github - get started quickstart]https://docs.github.com/en/get-started/quickstart/set-up-git)<br>
[github - get started https clone]https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls)<br>
[github - creating a PAT Personal Access Token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)<br>
