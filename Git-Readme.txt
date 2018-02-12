
New Repository -> public -> init with readme
Get Clone with https url
> git clone [https url]  -> this will create project in local desktop with .git folder

Commands:
> git status
> git add [filename or .]
> git commit -m ["insert message here"]
> git push -> update repo
> git pull -> get most recent update from repo
> git branch -> list repo 
> git branch [branch name] -> create a branch
> git checkout [branch name]
> git push  --set-upstream origin [branch name]
> git merge master 

Refresh repo page and check commits.


NPM:
- Download latest LTS NPM
- Comes with Node with v8 engine which allows you to run JS outside of the browser.
> npm -v 
> node -v 
> npm init -> Will create package.json file in your directory
	package name:
	version:
	description:
	entry point:
	test command:
	git repository:
	keywords:
	author:
	liscense:

- all you need in git repo is the package.json file to recreate node packages.
> npm install
> npm run [name] --> runs command [name] defined in package.json under "Scripts"
  -ie: "build": "browserify script.js > bundle.js && live-server"
        > npm run build
	
- install live-server
	> npm install -g live-server  -> global
	> live-server  -> run from working directory

- install lodash
	> npm -i --save lodash	 -> local to working directory
	or 
	> npm install lodash --> doesn't save it to your computer
	- creates node_modules folder
	> npm install -g browserify
	> browserify script.js > bundle.js --> creates bundle.js file with a js file that browser understands
	- replace script.js in html with bundle.js



React:
- Components
- Virtual DOM

- create-react-app 
	- this tool is a global package that you want to install from NPM.
	- it creates a starter project that contains
		Babel
		Webpack
		latest JS features
		lint
		debugging
		etc...
> npm install -g create-react-app  --> install the app
> create-react-app robofriends --> creat app called robofriends
	Success! Created robofriends at \react\robofriends
	Inside that directory, you can run several commands:

	  npm start
	    Starts the development server.

	  npm run build
	    Bundles the app into static files for production.

	  npm test
	    Starts the test runner.

	  npm run eject
	    Removes this tool and copies build dependencies, configuration files
	    and scripts into the app directory. If you do this, you can’t go back!

	  We suggest that you begin by typing:

		  cd robofriends
		  npm start

> npm install tachyons  --> css classes like bootstrap