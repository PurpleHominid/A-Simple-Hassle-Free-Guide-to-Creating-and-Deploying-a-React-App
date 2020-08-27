# A-Simple-Hassle-Free-Guide-to-Creating-and-Deploying-a-React-App


As a starting point - the following should be installed
Git
Node

Install typescript as a node package -
npm install -g typescript

Issues with permissions when attempting to install typescript as a global package:
EACCES: permission denied, access '/usr/local/lib/node_modules'
sudo chown -R $USER /usr/local/lib/node_modules

Ready to set up your application
via a terminal window
change to your project's base folder (cd /Projects)
and execute the command

npx create-react-app demo-application
The team at React setup this simple CLI instruction to automate all the setup tasks in a single command. The result is boilerplate React application in the folder called /demo-application 

---
Use the “npm” tool to install (globally) node packages. 
Use the “npx” tool to execute (and install locally if not found) node packages

Global packages may cause compatibility issues when dealing with multiple project with difference dependencies
---

Change to the new application - 
cd ./demo-application

Launch the node server -
$ node start


Ready to Deploy
inside the demo-application folder there are two hidder files .git and .gitignore
reinitialise git (in the demo application folder) useing: 
git init .

