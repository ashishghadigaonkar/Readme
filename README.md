# Readme
# Step 1: Initialize Git
git init

# Step 2: Configure Git
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

# Step 3: Check Git status
git status

# Step 4: Stage and commit files
git add .
git commit -m "Initial commit"

# Step 5: Add a remote repository
git remote add origin https://github.com/yourusername/repositoryname.git

# Step 6: Push to the remote repository
git push -u origin master/main

# Step 7: Check git log for commit history
git log

# Step 8: Create and switch to a new branch
git checkout -b new-branch-name

# Step 9: Pull changes from remote
git pull origin master/main   # Use the correct branch if not 'master'

# Step 10: Push to remote from a different branch
git push -u origin new-branch-name

# Step 11: List branches
git branch


Ashish@LAPTOP-LES056GN MINGW64 ~/Python-Game-Arcade (main)
$ git remote add upstream https://github.com/Sujay-85/Python-Game-Arcade.git



Ashish@LAPTOP-LES056GN MINGW64 ~/Python-Game-Arcade (main)

$ git fetch upstream

From https://github.com/Sujay-85/Python-Game-Arcade
 * [new branch]      main       -> upstream/main

Ashish@LAPTOP-LES056GN MINGW64 ~/Python-Game-Arcade (main)

$ git checkout main

Already on 'main'
Your branch is up to date with 'origin/main'.

Ashish@LAPTOP-LES056GN MINGW64 ~/Python-Game-Arcade (main)

$ git merge upstream/main

Already up to date.

Ashish@LAPTOP-LES056GN MINGW64 ~/Python-Game-Arcade (main)

$ git push origin main

Everything up-to-date

