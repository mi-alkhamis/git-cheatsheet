
# Git cheatsheet
[![](https://img.shields.io/badge/dwclass-dev--004--git-brightgreen&style=plastic)](https://github.com/mi-alkhamis/git-cheatsheet/blob/main/README.md)
[![GitHub stars](https://img.shields.io/github/stars/mi-alkhamis/git-cheatsheet?color=magenta&label=Stars&style=plastic)](https://github.com/mi-alkhamis/git-cheatsheet/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/mi-alkhamis/git-cheatsheet?label=Forks&style=plastic)](https://github.com/mi-alkhamis/git-cheatsheet/network)  [![GitHub license](https://img.shields.io/github/license/mi-alkhamis/git-cheatsheet?color=Green&label=License&style=plastic)](https://github.com/mi-alkhamis/git-cheatsheet/blob/main/LICENSE) 

![git-logo](./images/git-logo.png)

This documents represents most common Git commands discussed in dwclass. 


# TO DO:
   - [ ] Table of contents
   - [ ] Add git cheet sheat with examples
   - [ ] Add some pic to show how git works
     
# Contribute

 All contributions are welcome:

   -  Read the issues, Fork the project and do a Pull Request.
   -  Request a new topic creating a New issue with the enhancement tag.
   -  Find any kind of errors in the cheat sheet and create a New issue with the details or fork the project and do a Pull Request.

## FAQ

### Why Git

Git tracks the changes you make to files, so you have a record of what has been done, and you can revert to specific versions should you ever need to.

### What is the repository and how to orgenize it

Repositories  contain a collection of files of various different versions of a Project. it must contains README.md ,and LICENSE

### Git clone

`$ git clone https://github.com/mi-alkhamis/git-cheatsheet.git`

we use this command to retrieve a copy of a project, in this exmpale  you can get copy of mine :smile:

### How to sync local repo with the remote one

 `$ git pull` 

it gave all change from remote repository  and writte in local repository

### reset vs revert vs checkout

reset:` $ git reset COMMIT-NUM` restore to `COMMIT-NUM`  and remove ahead commits

revert: ` $ git revert COMMIT-NUM` restore to `COMMIT-NUM` and make a commit to remind the path

checkout: `$ git checkout COMMIT-NUM` to change head to  mentioned commit number

### rebase vs merge

rebase: `$ git rebase` order commits by commit number

merge: merge change to make a commit

### how to show history

to show history use `$ git log`

### how to show differnces with head

`$ git diff`

### Tag, how use it

use tag to version the project, to make easy to get release from it

`$ git  tag v1.0`

### how to contribute to any project

first of all, clone it `$ git clone https://github.com/mi-alkhamis/git-cheatsheet.git` after make change push it`git push` 

- NOTE: most of projects have `How to contribute` file, if this file exist, follow owner's rules to pull request

### What is the branch and how to merge it

make a branch when you work on a bugfix, a new feature, or somthing like it, and don't want to effort all project, so make a brach `$ git branch NAME` after making changes merge it `$ git merge`

  
## License
This project is licensed under the GPL-3.0 License  - see the [LICENSE](./LICENSE) file for details.

[@dwsclass](https://github.com/dwsclass) dws-dev-004-git

