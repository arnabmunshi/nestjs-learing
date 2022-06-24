### Installation

```bash
# install nestjs cli
$ npm i -g @nestjs/cli

# create app
$ nest new project-name

# enter into project directory
$ cd project-name

# start app
$ npm run start

# start app and watch
$ npm run start:dev

# create a new branch and enter into the new branch
$ git checkout -b setup

# how delete the current branch?
# 1. checkout to other branch
# suppose we are in <branch_1> branch and checkout to <branch_2>
$ git checkout branch_2
# 2. now we can delete branch-1
$ git branch -d branch_1
# delete the new branch, then rename the old one (and re-push commits):
$ git branch -m branch_1
```

### How to change default branch?

[Changing the default branch](https://docs.github.com/en/enterprise-server@3.1/repositories/configuring-branches-and-merges-in-your-repository/managing-branches-in-your-repository/changing-the-default-branch)

```bash
# delete a branch from remote which is not default branch
$ git push -d origin setup
```

### Git reference

- [How To Create a Git Branch](https://devconnected.com/create-git-branch/)
- [Changing git default branch from master to main](https://superuser.com/questions/1682972/changing-git-default-branch-from-master-to-main-on-command-line-cli)
