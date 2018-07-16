# Global gitignore

cd ~

wget https://raw.githubusercontent.com/dbjpanda/global-gitignore/master/.gitignore_global

git config --global core.excludesfile ~/.gitignore_global


# Available Aliases in .Gitconfig

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
git apply-url http://blah.com/issue.patch OPTIONAL_GIT_APPLY_ARGS
