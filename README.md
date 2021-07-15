
# DWS-dev-004

Work with git

## Question1: why we use git version-control?

answer: for control program source and git is a Database for keep source and versioning 

## Question2: What is Repository? What important files does a good repository have?

answer:
 - Repository is a storage for keep commits ,Branches, tags, files and ...


- .gitignore/readme.md/LICENSE


## Question3: What are the parts of a good document?
answer:
- 1. What does the project do and what is it made for?

- 2.How to use the project?

- 3.What should someone do if they want to help with the project?

## Question4: What does the 'git-clone' command do?
answer:
- Used to take a complete sample of the project.

## Question5: What command should be executed if we want to update the local repository with the remote repository?

answer:
- we sould use this command

```git-bash
git pull
```

## Question6: What is deference between 'checkout','revert','reset'?
answer:
- ### checkout :
     for transfer between branches
```git-bash
git checkout <branch-name>
```
- ### revert:
lose changes and add new commit
```git-bash
git revert <commit>
```
- ### reset:
keep changes and just remove commit
```git-bash
git reset <commit>
```

## Question7: What is deference between 'merge' and 'rebase'?
answer:
- ### merge:
     add new commit and merge current changes with specific branch
```git-bash
git merge --no-ff <branch-name1> <branch-name2>
```
- ### rebase:
sort-changes and Stick together.
```git-bash
git rebase
```
## Question8: What command is used to view the history of commits?
answer:

```git-bash
git log
```
## Question9: What command do we use if we want to see changes to a file?
answer:
```git-bash
git diff
```
```git-bash
git show
```

## Question10: What is the use of tag? How to create a tag?
answer:
for get release of after update or after stable project 

```git-bash
git tag
```
## Question11: What is the process to participate in a git-managed project?
answer:
- 1. clone project to our local system
- 2. create local-branch
- 3. add changes
- 4. commit changes
- 5. checkout to dev or master
- 6. merge local-branch with remote branch
- 7. pull from remote branch
- 8. fix conflicts 
- 9. push to remote branch


## Question12: What are the uses of the branches and how can they be integrated?
answer:
for apply specific changes in project

with 2 below command:

```git-bash
git merge
```
```git-bash
git rebase
```

## Author:

sajjad maneshi

[@dwsclass](https://github.com/dwsclass)dws-dev-004-git

