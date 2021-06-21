Branching allows us to work on multiple versions of our code at once. That means we can safely experiement with code before merging. 

To add a branch use:
git branch add-readme
Spaces are not allowed, so hyphens are used. 

We can list the branches
git branch

At this point, we will still be connected to master

to switch to our new branch, we can type:
git checkout add-readme

A shortcut to create and swith to new branch could be:
git checkout -b add-readme

mac users can create a readme by using the touch command

touch README.md