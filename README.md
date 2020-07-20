## 📌 Start with Git and Github
This repo shows how to begin with Git and Github.
**Git** is a version control system that lets you manage and keep track of your source code history. It is designed to handle everything from small to very large projects with speed and efficiency.
**GitHub** is a cloud-based hosting service that lets you manage Git repositories. If you have open-source projects that use Git, then GitHub is designed to help you better manage them.

## 🏃‍♂️ Installing Git
First Install git for your OS. Available for Linux/Unix, Windows and Mac.

## 🛠 Configuring Git
  git config --global user.name "user_name"         (your Github account user_name) 
  git config --global user.email "email@mail.com"     (your Github account mailId)
📁 Creating a new Repository
Create a folder in your system and then initializing it with git.
Open git bash or terminal and then move to that folder and type.
  git init 
Now your folder is initialized with git.
Create a simple file and save it inside that folder.
🏁 Checking status of your repo
Open git bash or terminal and then move to that folder and type.
 git status
➕ Add the files
 git add .
or

 git add -A
🔗 Commiting the files
 git commit -m "commit message"
💫 Connecting it to your repo at Github
Create a new repo on your github. Let's say learn_git.
Copy the repo address - https://github.com/imPGupta/learn_git
Open git bash or terminal and then move to that folder and type.
  git remote add origin https://github.com/imPGupta/learn_git
💥 Uploading to Github
 git push origin master
© Cloning a Git repo
 git clone https://github.com/imPGupta/learn_git
☁ Getting files from a Github repo
git pull origin master
