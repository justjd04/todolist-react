<h1>Todolist Using React</h1>

<p>Published: https://justjd04.github.io/todolist-react/</p>

<h2>Commands to create-react-app:</h2>

<p>npx create-react-app todolist</p>
<p>cd todolist</p>
<p>code .</p>
<p>npm start</p>

<h2>Commands used to install Font Awesome:</h2>

<p>$ npm i --save @fortawesome/fontawesome-svg-core</p>
<p>$ npm i --save @fortawesome/free-solid-svg-icons</p>
<p>$ npm i --save @fortawesome/react-fontawesome</p>

<h2>Commands used to publish react files in github:</h2>

<p>Go to package.json</p>
<p>Add:"homepage": "https://justjd04.github.io/todolist",</p>
<p>Format:https://UserName.github.io/Project-name</p>

<p>Under scripts</p>
<p>Add:</p>
<p>"predeploy": "npm run build",</p>
<p>"deploy": "gh-pages -d build",</p>


<p>git remote add origin https://github.com/justjd04/todolist-react</p>
<p>git remote set-url origin https://github.com/justjd04/todolist-react</p>
<p>npm run build</p>
<p>npm run deploy</p>
<p>(ERR! gh-pages is not recognized Solution:npm install gh-pages --save-dev)</p>

<h2>Push using Git Bash:</h2>

<p>cd todolist</p>
<p>git remote</p>
<p>git remote add origin https://github.com/justjd04/todolist-react.git</p>
<p>git remote</p>
<p>git status</p>
<p>git add .</p>
<p>git commit -m "initial commit"</p>
<p>git push -u origin master</p>

<!-- some notes
git init - initialize a local git repo
git add  - add file to index/staging area
git status  - check status of working tree/in staging area
git commit  - commit changes in staging area to remote repo
git push  - push to remote repo
git pull - pull latest from remote repo
git clone - clone repo into new directory/download to machine

touch index.html
touch app.js
git init

git config  --global user.name 'Jan Dohinog'
git config  --global user.email 'janreydohinog@gmail.com'

git add index.html

git status - tell us that index file has changes to be commited and can add to staging area, red one is untracked app.js

if want to remove git rm --cached index.html

git add *.  - will add any html file to staging area

git add .  - add everything

edit a file and git status
tells the file that was modified telling to add it

git add . now green back in staging area

git commit
click i to go insert mode - esc then esc :wq Enter

or git commit -m "initial commit"

git status -it now says nothing to commit

clear

touch .gitignore -file dont want to ignore
log.txt   -file type or put on git ignore file, you dont want to include
/dir1    -folder type on git ignore to not include
*.txt   -all txt file

git branch login  -create branch say example adding login to project
log in is name of branch

git checkout login  -to switch from master to branch
will not show file like login.html

git checkout master -to switch back to master

git merge login - merge do it in master
will now show file like login.html

open editor type i comment added login
esc :w2 Enter

git remote  - say nothing

git remote add origin https://github.com/myapp.git

git remote - will now say origin

git push -u origin master

touch README.md  -create readme but not necessary

git add .

git push

copy link in download or click download to clone


git clone paste link

git pull  -pull everything down
-->
