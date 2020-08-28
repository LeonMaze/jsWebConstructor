# jsWebConstructor
JavaScript Web Sites Constructor

Create project folder
```Ruby
mkdir jsconstructor
```
Initialize it
```Ruby
npm init
```
Install modules
```Ruby
 npm i -D webpack webpack-cli webpack-dev-server
```
 Create webpack.config.js file
```Ruby
 touch webpack.config.js  
```
with the code:
```Ruby
const path = require('path');

module.exports = {
    entry: './src/index.js',
    output: {
        filename: 'bundle.js',
        path: path.resolve(__dirname, 'dist')
    }
}
```
 Create src folder and files
```Ruby
  mkdir src
  touch src/index.js && !!:$ src/module.js
```
Install html plugin
```Ruby
npm i -D html-webpack-plugin
```
Create index.html file in /src
  
Install 
```
npm i -D style-loader css-loader
```
