**GIT**


## What is a Git ?
Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

#### If you have not installed git on your system then please install git by running command on cmd and terminal:
-  **pip3 install git**.
 
###  commands to check particular status of files and Repository:
 - git status = When you are using Git, you will frequently want to check the status of your repository. To check the status we will use **git status**.

Git has a staging area in which it stores files with changes you want to save that haven't been saved yet. Putting files in the staging area is like putting things in a box, while committing those changes is like putting that box in the mail: you can add more things to the box or take things out as often as you want, but once you put it in the mail, you can't make further changes.

- git diff filename -  In order to compare the file as it currently is to what you last saved, you can use **git diff filename**.
ex: git diff report.txt

### This shows :
- The command used to produce the output (in this case, diff --git). In it, a and b are placeholders meaning "the first version" and "the second version".
- An index line showing keys into Git's internal database of changes. We will explore these in the next chapter.
- --- a/report.txt and +++ b/report.txt, wherein lines being removed are prefixed with - and lines being added are prefixed with +.

#####You commit changes to a Git repository in two steps:
- Add one or more files to the staging area.
- Commit everything in the staging area.
- git add filename: To add a file to the staging area, use **git add filename**.

##### How can I tell what's going to be committed?
- git diff -r HEAD: To compare the state of your files with those in the staging area, you can use **git diff -r HEAD**. 

##### How do I commit changes?
- I can commit using **git commit -m "message"**, if I mistype the message we can change using the given command below:
-- git commit --amend - m "new message"
  





 
 
