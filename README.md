# hello-world
Hello World repository for Git tutorial
This is an example repository for the Git tutoial on https://www.w3schools.com
This Tutoial focuses mainly on Git and using Github as its remote

This repository is built step by step in the tutorial.

It now includes steps in Github.

## omit 'git' as the head:
### ***and the steps***:

Tell who u r
1. config user.name "HIT0638"
2. config user.email "156294753@qq.com"

Enter your local repitory
// command of this part has no 'git' head
3. cd e:
4. cd myproject

Because this repo has been init
So just add or creat the file u want into it
After this ,there are some function u shoule remember:
+ status  // check the status of this repo
+ add filename
+ add --all // State file so could wait to be commited
+ commit -m ***merge*** // commit file with merge to explain the operation or reason
+ branch **new branck name** // create new branch
+ checkout **branch name**  // enter specific branch
+ checkout -b **emergency branch name**
+ merge **branch name** // merge branches

Command above are commands in Git,
Now add Github 

First u shoule connect the github, use command:
1. remote add origin **URL of repitory**

Pull file from Github:
_*fetch*_、_*merge*_
AND **pull** is a combination of above two

+ fetch origin //updates to see what has changed on GitHub
+ log **origin/name** // show the notes of commit
+ diff **origin/name** // show the differences between local master and origin/master
+ merge **origin/name** // combines the current branch, with a specified branch.
