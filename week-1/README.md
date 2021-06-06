### how to setup your machine

* first create a folder
* open command prompt and go to your folder in which you want to create project
* write the following line :  ``` npm init``` this will create package.json file
* once its created then write : ```npm install lite-server --save-dev```
* Next, open package.json in your editor and modify it as shown below. Note the addition of two lines, ```start:"npm run lite``` and ```lite:"lite-server```
```{
  "name": "  ",
  "version": "1.0.0",
  "description": "Node basic learning project",
  "main": "index.html",
  "scripts": {
    "start": "npm run lite",
    "test": "echo \"Error: no test specified\" && exit 1",
    "lite": "lite-server"
  },
  "author": "",
  "license": "ISC",
  "devDependencies": {
    "lite-server": "^2.2.2"
  }
}
```
* Next, start the development server by typing the following at the prompt: ```npm start```
* Next, create a file in your project directory named .gitignore (Note: the name starts with a period)Then, add the following to the .gitignore file ```node_modules```

#### downloading bootstrap
* At the prompt, type the following to fetch Bootstrap files to your project folder: ```npm install bootstrap@4.0.0 --save``` and then type ```npm install jquery@3.3.1 popper.js@1.12.9 --save```
* This will fetch the Bootstrap files and store is in your node_modules folder in a bootstrap folder. The bootstrap->dist folder contains the precompiled Bootstrap CSS and JS files for use within your project.
* Start your lite-server by typing ```npm start``` at the prompt. The index.html file should now be loaded into your default browser.


