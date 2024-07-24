# devops

					GIT_All Concepts
Version Control System (VCS) is a software that helps software developers to work together and maintain a complete history of their work.

Listed below are the functions of a VCS −

•	Allows developers to work simultaneously.

•	Does not allow overwriting each other’s changes.

•	Maintains a history of every version.

Advantages of Git

•	Free and open source

•	Fast and small

•	Easier branching

•	Implicit backup
 
GIT ARCHITECHTURE:

![image](https://github.com/user-attachments/assets/d848cede-de92-4a48-8573-06fecdd1a03f)

 
Local Workspace: this is the space local workspace where it contains all the files, folders and can do all the changes and work on it. Once we do all the changes and sure of having the changes in centralized repository (github) we start with the command git add

Command: git add <file name1> <file name 2> 

 git add . 
 
git add *

git add –A 

git add –a

git add -u  Add all changes to tracked files only and This command stages modifications and deletions, but not new files


Staging/Index:  Once the changes are done and sure with the changes, we save the data in staging or index. We assign a commit id for reference here in staging.

Command: git commit –m “message for reference”

git commit --amend  Changing the Last Commit Message

git commit --amend -m "New commit msg"  Amend the Last Commit Msg with a New Msg (without opening an editor)

git rebase -i HEAD~N  Changing an Older Commit Message

Local Repository: the files here in Local Repository are ready to push github. 

Command: git push
