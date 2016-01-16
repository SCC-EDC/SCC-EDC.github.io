# SCC-EDC.github.io
Landing page for the SCC-EDC

The best way to add your individual page is to clone the repository to your local computer and create your own branch.
navigate to the directory you would like to place the project on your local computerat the command prompt type

git clone https://github.com/SCC-EDC/SCC-EDC.github.io.git

then navigate to the project directory you just cloned.  You will be on the Master branch.type 

git checkout -b yourbranchname

using whatever you would like to call your branch.  This will give you a personal copy of the project to make changes to. 
The name is case sensitive.  to check what branch you are in type git status

To commit the changes to your branch type

git add -A                 This command adds all of your changes to be comitted

git commit -m "Your message to go with the commit"              This commits your changes, you must now push your commit to the
repository

git push origin branchname                      The pushes the changes to the branch you specify.

We will cover Merging branches into the master at a later time. 
