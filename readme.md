## Create a project folder adn start following [Electron](https://www.electronjs.org/docs/tutorial/development-environment#setting-up-windows)
``` bash 
mkdir electron-app-test
cd electron-app-test
```
## After cloning the repo. 

``` bash
npm  init -y
npm i --save-dev electron
npm start
npx @electron-forge/cli import
npm run make
```
-------------------------
### Encountered Error

If encountered an error on "Making for target: squirrel" 
add this line on package.json 
``` json 
"author": "your-name", 
"description": "your-description"
```
