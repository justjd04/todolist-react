<h1>Todolist Using React</h1>

<h2>The Published Todolist App:</h2>

<p>https://justjd04.github.io/todolist-react/</p>

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

<p>cmd:</p>
<p>git remote add origin https://github.com/justjd04/todolist-react</p>
<p>git remote set-url origin https://github.com/justjd04/todolist-react</p>
<p>npm run build</p>
<p>npm run deploy</p>
<p>(ERR! gh-pages is not recognized Solution:npm install gh-pages --save-dev)</p>

<h2>Push using Git Bash:</h2>

<p>cd todolist</p>
<p>git remote add origin https://github.com/justjd04/todolist-react.git</p>
<p>git remote</p>
<p>git status</p>
<p>git add .</p>
<p>git commit -m "initial commit"</p>
<p>git push -u origin master</p>
