## 📌 Start with Git and Github
This repo shows how to begin with Git and Github.<br>
**Git** is a version control system that lets you manage and keep track of your source code history. It is designed to handle everything from small to very large projects with speed and efficiency.<br>
**GitHub** is a cloud-based hosting service that lets you manage Git repositories. If you have open-source projects that use Git, then GitHub is designed to help you better manage them.

## 🏃‍♂️ Installing Git
- First Install git for your OS. Available for Linux/Unix, Windows and Mac.

## 🛠 Configuring Git
```
  git config --global user.name "user_name"         (your Github account user_name) 
```
```
  git config --global user.email "email@mail.com"     (your Github account mailId)
```
<img src="https://github.com/imPGupta/learn_git/blob/master/Img/1.%20Configuring%20Git.png" width="75%" >

## 📁 Creating a new Repository
- Create a folder in your system and then initializing it with git.
- Open git bash or terminal and then move to that folder and type.
```  
  git init 
```
<img src="https://github.com/imPGupta/learn_git/blob/master/Img/2.%20Creating%20a%20new%20repo.png" width="75%" >

- Now your folder is initialized with git.
- Create a simple file and save it inside that folder.

## 🏁 Checking status of your repo
- Open git bash or terminal and then move to that folder and type.
``` 
 git status
```
<img src="https://github.com/imPGupta/learn_git/blob/master/Img/3.%20Checking%20status.png" width="75%" >

 
## ➕ Add the files
``` 
 git add .
```
 or
```
 git add -A
```
<img src="https://github.com/imPGupta/learn_git/blob/master/Img/4.%20Add%20the%20files.png" width="75%" >


## 🔗 Commiting the files
``` 
 git commit -m "commit message"
```
<img src="https://github.com/imPGupta/learn_git/blob/master/Img/5.%20Commiting%20the%20files.png" width="75%" >


## 💫 Connecting it to your repo at Github
- Create a new repo on your github. Let's say learn_git.
- Copy the repo address - https://github.com/imPGupta/learn_git
- Open git bash or terminal and then move to that folder and type.
```  
  git remote add origin https://github.com/imPGupta/learn_git
```
<img src="https://github.com/imPGupta/learn_git/blob/master/Img/6.%20Connecting%20it%20Github.png" width="75%" >


## 💥 Uploading to Github
``` 
 git push origin master
```
<img src="https://github.com/imPGupta/learn_git/blob/master/Img/7.%20Uploading%20to%20Github.png" width="75%" >

**Remove Error If Occurs**

<img src="https://github.com/imPGupta/learn_git/blob/master/Img/8.%20Uploading%20to%20Github.png" width="75%" >


## © Cloning a Git repo
``` 
 git clone https://github.com/imPGupta/learn_git
```

## ☁ Getting files from a Github repo
```
git pull origin master
```
<img src="https://github.com/imPGupta/learn_git/blob/master/Img/9.%20Getting%20files%20from%20Github.png" width="75%" >

