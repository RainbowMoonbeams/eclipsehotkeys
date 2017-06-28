# GitHub!

-------------------------------------------------------------------------------------------------

### Uploading to a New Repository

-------------------------------------------------------------------------------------------------

Create (or copy & paste from a previous file) the .gitignore file into the file you want to upload.

command | explanation
--------|--------
cd .. | change directory into parent folder (steps back a folder)
cd default-workspace | finds the folder // dunno what this means? [BTF]
cd **name of your folder** | change directory into a folder
git add **name of your folder** | adds a folder to staging (changes to be committed)
git init | initialize a local git repository in the current folder
git add . | adds all the files in the current folder to staging (changes to be committed)
git commit -m "write a message" | commit to local repository with notes to yourself about changes

* Open your GitHub & make a new repository.

* Name your new repository the same name as your project.

* Copy the link in "…or push an existing repository from the command line".

* Paste the link in GitBash by using Crtl + Shift + v

command | explanation
--------|--------
git push | pushes your local changes (commits) to GitHub
git status | should return "working tree clean" (everything worked as expected)

Refresh your GitHub page and you'll see the files you uploaded.

-------------------------------------------------------------------------------------------------

### Uploading to an Established Repository

-------------------------------------------------------------------------------------------------

command | explanation
--------|--------
cd .. | change directory (steps back a folder)
cd default-workspace | finds the folder
git init | gets into the folder
cd **name of your folder** | adds your folder
git init | gets into the folder
git add . | adds all the files in the folder
git commit -m "write a message" | notes to yourself about changes
git push | pushes the file upto GitHub
git status | should return "working tree clean" (everything worked as expected)

Refresh your GitHub page and you'll see the files you uploaded.
