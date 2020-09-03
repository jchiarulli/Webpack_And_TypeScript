# Webpack Installation

- Enter the following commands in the Repository folder which in my case is Webpack_And_TypeScript
  - tsc --init
    - Creates/initializes a new TypeScript project which initializes a tsconfig.json file
    - Inside of the tsconfig file change "target": "es5" to "target": "es6" and change "module": "commonjs to "module": "es2015"
  - npm init
    - Initializes a package.json file to keep track of all of our dependencies
    - Can just hit enter through all of the different questions
  - npm install webpack -D
    - Core Webpack package which will be used to compile and bundle the source code into a single optimized file
  - npm install webpack-cli -D
    - Allows us to interact with Webpack using a command line interface
  - npm install ts-loader -D
    - Teaches Webpack how to compile TypeScript to JavaScript
  - npm install typescript -D
    - Installs TypeScript locally as a dev dependency for Webpack to work with it properly eventhough we have TypeScript installed globally
  - -D saves the packages to the package.json, so we can keep track of the dev dependencies
