# Git
![Git logo](https://th.bing.com/th/id/R5c560e139fb603958c1e10433cb8108b?rik=RnFhnuMXfyRKuA&riu=http%3a%2f%2fwww.knowledge7.com%2fwp-content%2fuploads%2f2014%2f06%2f20140619-git-logo.jpg&ehk=4mIvRS2%2fcrHmk4%2bXcgnsPLiPrnfkpIZCXBWOrG6Ww6Q%3d&risl=&pid=ImgRaw)
## what is Git ?
well Git is a version control system that allows you to create something called repository which is a file that contains your code work and allow you to work on it remotely, and also it gives the ability for a group of developers to work on the same project and many other features that i'll talk about some of them in this note...

1. it has GUI tools.
2. it has a Default Text Editor 
3. cloning that allows you to clone your own and other's repo's and work on them.

## the local repository structure 
it has three components 
1. Working Directory: The actual files reside here.
2. Index: The area used for staging
3. Head: Points to the most recent commit.

### repositories are either tracked or untracked
Tracked files can be modified, unmodified, or staged but the untracked files do not currently reside in the staging area.

## The Life Cycle of File Status
* After you edit a file, Git flags it as modified because of changes made after the previous commit.
* You stage the modified file.
* Then, you commit staged changes.

### here's some commands that will help you in Git :
To get help you can use  " git help command "

To clone a repo you can use " git clone https:/ /github[the files link] "

To determine the state of files you can use " git status "
