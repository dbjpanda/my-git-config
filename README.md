# Configure gitignore globally

```
cd ~

wget https://raw.githubusercontent.com/dbjpanda/global-gitignore/master/.gitignore_global

git config --global core.excludesfile ~/.gitignore_global
```

# Configure gitconfig

```
cd ~
Edit your existing .gitconfig or directly download this file
wget https://raw.githubusercontent.com/dbjpanda/global-gitignore/master/.gitconfig
```

# Available Aliases in .gitconfig

Create a temp branch and apply the PR to that branch
`````
git pr PR_NO
``````
Delete the PR branch and checkout to master branch
`````````
git pr-clean BRANCH_NAME 
`````````
Add all and commit
`````````
git add-commit "your messages"
`````````
Apply a patch from an URL. 
````````
git apply-url http://blah.com/issue.patch [OPTIONAL_GIT_APPLY_ARGS](https://git-scm.com/docs/git-apply)
