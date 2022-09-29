# Добрый день, уважаемые студенты! 
  При выполнении данной работы от вас требуется дополнить мой репозиторий, добавив в него свой файл с инструкцией по работе с git. Помните, что добавление файла - такой же процесс изменения репозитория, как и изменения внутри конкретных файлов и не пугайтесь этого :)

  P.S. Называйте добавляемые файлы своими фамилиями(только на английской раскладке), чтобы мне было проще их идентифицировать. И не забудьте сделать скрин окна с pullrequest, на сайт GB необходимо отослать именно этот скрин, чтобы работа была окончательно завершена.

  P.P.S. Не забывайте, что отправляем на pullrequest мы побочные ветки!

  # Instruction for using GIT. Main functions 

## Setting and configuration

* _git config_ - command that helps you query/set/replace/unset options. 
For example, using *git config --global user.name "your mame"* helps to create username (option *--global* means that these settings need to be done only once).

* _git help_ - command serves to display help information for all Git commands. For example, *git help "command name"* will give a full list of all command parameters.

## Copying and creating projects

* _git init_ - helps to initialize repository where you can control file versions.

* _git clone_ - command that creates a new folder, navigates to it and runs the *git init* command to create empty Git repository.

## State fixation

* _git add_ - command that moves from the working folder to the indexing area the content destined for the next commit.

* _git status_ - command shows the status of files in the working folder and area of indexation.

* _git diff_ - command used to calculate the difference between any two trees.

* _git difftool_ - command that launches an external display tool
difference between two trees.

* _git commit_ - command that takes all the contents of the files indexed with *git add* commands, and writes a new permanent snapshot to the database, and then shifts the branch pointer to that snapshot.

* _git reset_ - command is used to undo an action

* _git rm_ - command used to remove files from the indexing area, or
working folder, it indexes data that will be deleted on the next commit.

* _git mv_ - command used as a file moving tool

* _git clean_ - command is used to remove unnecessary files from the working folder.

## Branches and merging 

* *git branch* - used to list all existing branches 

* *git branch new_branch_name_* - used to create new branches. For example, *git branch "new branch name"*

* *git checkout branch_name*- used to move between branches.

* *git merge* - used for merging branches. For example, *git merge branche_to_merge* will merge *branch_to_merge* branch and current branch.

## Verification and comparison

* *git show* - command that displays Git objects on the screen in a simple and understandable way for users.

* *git shortlog* - command that briefly reproduces the output of the git log command. It does not list all commits, but only their brief description, grouped by authors.

* *git describe* - command that works on anything that can be treated as a commit, outputting a readable, immutable string, creates a commit description.

## Fixes

* *git cherry-pick* - command that takes the changes made by a single commit and tries reapply them as a new commit in the current branch. _This opportunity
useful in a situation where you need to take one or two commits from a branch, rather than merge entire branch with all changes made to it_

* *git rebase* - command that defines a set of commits and fetches data from them one by one, as if moving the branch to a new place.

* *git revert* - command that creates a new commit that acts diametrically opposite to the target commit, reverting all changes made by the last one.

## Debugging

* *git bisect* - commant that allows to find a commit, where the problem first arose.

* *git blame* - command that opens file notes indicating when and by whom
each line was last edited.

* *git grep* - command that makes it easy to find a string in any code file, including older versions of the project.

## Service commands

* *ls-remote* - used to view links on the server.

* *rev-parse* - command that allows to turn almost any string into a SHA-object.

## Work with remoted repositories

* *git clone* - used to copy remoted repository on GitHub to local repositoty.

* *git pull*- used to pull changes from remoted repository to local.

* *git push* - used to push changes from local repositoty to remoted repository on GitHub.

* *pull request* - used to make a request for editing someone else's remoted repository.

* *fork* - used to copy any full repository to yours on GitHub for further editing.