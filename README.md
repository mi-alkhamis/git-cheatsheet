
# Git cheatsheet

[![GitHub license](https://img.shields.io/github/license/mi-alkhamis/git-cheatsheet?color=Green&label=License&style=plastic)](https://github.com/mi-alkhamis/git-cheatsheet/blob/main/LICENSE)

This documents represents most common Git commands with examples. 



# Table OF Contents

# FAQ

### Why Git

Git tracks the changes you make to files, so you have a record of what has been done, and you can revert to specific versions should you ever need to.

### What is the repository and how to orgenize it

Repositories  contain a collection of files of various different versions of a Project. it must contains README.md ,and LICENSE

## Git clone

`$ git clone https://github.com/mi-alkhamis/git-cheatsheet.git`

we use this command to retrieve a copy of a project, in this exmpale  you can get copy of mine :smile:

## How to sync local repo with the remote one

 `$ git pull` 

it gave all change from remote repository  and writte in local repository

## reset vs revert vs checkout

reset:` $ git reset COMMIT-NUM` restore to `COMMIT-NUM`  and remove ahead commits

revert: ` $ git revert COMMIT-NUM` restore to `COMMIT-NUM` and make a commit to remind the path

checkout: `$ git checkout COMMIT-NUM` to change head to  mentioned commit number

## rebase vs merge

rebase: `$ git rebase` order commits by commit number

merge: merge change to make a commit

## how to show history

to show history use `$ git log`

## how to show differnces with head

`$ git diff`

## Tag, how use it

use tag to version the project, to make easy to get release from it

`$ git  tag v1.0`

## how to contribute to any project

first of all, clone it `$ git clone https://github.com/mi-alkhamis/git-cheatsheet.git` after make change push it`git push` 

- NOTE: most of projects have `How to contribute` file, if this file exist, follow owner's rules to pull request

## What is the branch and how to merge it

make a branch when you work on a bugfix, a new feature, or somthing like it, and don't want to effort all project, so make a brach `$ git branch NAME` after making changes merge it `$ git merge`


## License
This project is licensed under the GPL-3.0 License  - see the [LICENSE](./LICENSE) file for details.

[@dwsclass](https://github.com/dwsclass) dws-dev-004-git

