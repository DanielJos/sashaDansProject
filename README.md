# This is our project

## To get Git on mac
### Check if you already have it
1. Go to "**terminal**" (press CMD-Space, and type terminal)
2. In terminal run: `git version`
3. If you get something back saying:
   ```
    git version 2.25.1
   ```
    (or other versions)
4. If it doesn't work then you'll have to install.

### If you need to install, then do this: 

[Click here for instructions.](https://phoenixnap.com/kb/install-git-on-mac)

^^ in summary:
1. go to [this site](https://git-scm.com/)
2. Download the Mac shit

## To clone to your PC
1. On this [github.com/DanielJos/sashaDansProject](https://github.com/DanielJos/sashaDansProject) site, click on "clone" and copy the https link.
2. In **terminal**:
   1. Navigate to the folder you want to store your project in.
      - Type `ls` (list) to list the folders and files in the folder you are currently in.
      - `cd <directory name>` (change directory) to move to a folder that is listed. `cd ..` to go up a directory
      - `mkdir <directory name>` (make directory) to make a directory.
   2. When you're in the directory (folder) you want to store it in, run:
    ```
    git clone <git_clone_https_address>
    ```
# The Fun Stuff
## To add your changes
1. Make changes to a file and save the file
2. run `git add .`\
   (this will "stage" the files, making them ready to be "committed")
3. run `git commit -m "Your description your changes"`\
   (Committing the files to the git history)
4. run `git push`\
   (this will upload the commits up to the GitHub repository on the internet)
   
## To Receive Changes
1. run `git pull` in the directory of your project (use `cd` and `ls` to navigate) before you start adding things to sync with everyone else's changes 
