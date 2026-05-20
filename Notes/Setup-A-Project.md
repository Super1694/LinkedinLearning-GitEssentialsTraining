Notes on how to setup a project in GIT.

Overview:
    1- Create github repo
    2a- Create local folder
    2b- Local Folder -> Create (initialize) local repo
    3- Connect local repo (tied to the folder) and connect to GitHub repo
    4- first commit & push of the local repo

Note: GitHub will give some suggestions on how to do this, so that's a good reference.

Full description

**Create Github repo**
TECHNICAL STEPS:
- Using a web browser go onto GitHub. Login.
- Create new repo. Choose a good name!
CONVENTION NOTES: Names should be lowercase with hyphen. eg. good-name

**Create Local Folder**
- you can do it in powershell via VS Code, or just in windows explorer.
- Once it is created, then name 

**Initialize Local Repo**
1. inside the code folder use bash command `git init`
2. `git add .`
3. `git status` to check the main branch name. It should be named 'Main'
4. (if necessary) `git branch -M main` 
5. `git remote add origin https://....`
6. git push