# Reading-notes-3
Class 3

## Git is a version control system that lets multiple people work on the same code
Good for cohessivness in collabs

Commits represent each succesive version of a file(s), creating a timeline
HEAD is label meaning you are here
You can assign messages to commits with -m (like a caption of your commit)

Github uses Git to help manage your teams work
version tracking
review changes
keep changes seperate until you want to add them

with git (version control) and github (online code storage), you can
-have lots of people work together on the same files without messing each other up

repository is a collection of files that youve told git to pay attention to
usually one project=one repository

Put your repo on cpu by cloning it
protocal=rules/guidelines
git clone
made new folder
new folder in sync with github

git status
use "git status" to determine the state of files
now that files are in repo we need to take a comit
reiew current status by typng git status
-m=message
use gitpush to move your local file to github
open current file in editor "code ."
tell git what changes to commit
-done by     git add (filename)
use git commit (shudder button to make snapshot of changes to a file)
git commit -a to commit all changes
git commit -m "your message goes here"
git push origin master     syncs code to repo on github
then verify on github

tracked files are from most recent commit
untracked are files from previous versions

track all files with git add *
track single file with git ad filename

use git stash to stash changes without comiting them
use "git stash apply" to retrieve stashed changes

By running the "git remote" command, you can view the short names, such as “origin,” of all specified remote handles.
By using "git remote -v", you can view all the remote URLs next to their corresponding short names.
