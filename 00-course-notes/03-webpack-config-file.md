# Webpack Config File

- Create the following file in the Repository folder
  - webpack.config.js
  - Note: this must be the name of the file
- Then we export a file using the Node.js system because Webpack is ultimately going to be read using Node.js

* The entry file is the first file Webpack looks at and compiles, and it will then look at the dependencies that are being implemented in the index.js file and the dependencies of those files

* Dependency Tree Example

  - app.js
    - form.js
      - val.js
      - error.js
    - db.js

* The ouput requires the name for the bundled output file and an absolute path to the ouput file

  - To determine the absolute path we need to require the path module from Node.js

  * \_\_dirname finds the absolute path to the webpack.config.js file on the computer or server
  * Then we add on the public folder

* The module specifys that we want to compile the TypeScript files to a JavaScript file
