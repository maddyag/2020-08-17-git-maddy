#2020-08-17-git-maddy
- `git init`
- `git config --global user.name "Maddy Grupper"`
- `git config --global user.email "maddyag@vt.edu"`

- `nano README.md` // write whatever you want in this mini file, for us we wrote our steps
- `git add <FILE>`// places <FILE> into staging area. must do every time all steps
	- `git add README.md`
- `git status`: tells you what is going on in your repository
- `git commit`: commits files in the staging area //to edit what you did and add lines
	- `git commit -m "MESSAGE" : allows you to write notes in commit in one line and one step
	- if you've opened this in VI(M): <ESC> `:q!`
	- `git config --global core.editor "nano -w"`

- `git log` : shows you yuour history
	- `git log --oneline`: shows you your history in one line

- `HEAD` : tells you where you are looking at in history

- `git diff` :shows you current state with last known state differences
	- `git diff --staged` : shows difference from staging area with las t known
	- you can use `git log --oneline`to specify different versions in history

- `git log`

- `git remote add origin <URL>`: adds <URL> with the name origin
- `git push origin master` : pushes the master branch to the origin remote
- `git pull origin master` : pulls the master branch from origin to a local computer
	
- You can make changes to differernt parts of a file and it will 
