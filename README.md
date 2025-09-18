# research_methods_2025




# some basic linux commands

`ls` - show the contents of the current directory

`pwd` - show the current path (i.e. where you are in the file structure)

`cd <directory_name>` - change directory into `<directory_name>`

`cd ..` - change directory up one level

`cd` - change into your home directory

`cp <file_name> <new_file_name>` - make a copy of the file `<file_name>` called `<new_file_name>`

`mkdir <directory_name>` - make a directory called `<directory_name>`

Also remember you can use the up arrow to see previous commands entered, and the tab key to do tab completion on commands you start typing.

# how to run on linux

The first time you want to run you need to get the code from github.  You can start by making and changing directory into the area you want to work in, and then do the following:

On this page click on the green "code" button to get the repository address then do:

`git clone https://github.com/abbeywaldron/research_methods_2025.git`

Now you can change into the directory and look around to check you successfully got the files:

`cd research_methods_2025`

`ls`

IMPORTANT TIP: rename your notebooks when you start running them so that if you pull from the git repository later they have no chance of being over-written.


To update your repository to get the new exercises each week, first remember to rename and save all your files!  Then do:

`git pull`