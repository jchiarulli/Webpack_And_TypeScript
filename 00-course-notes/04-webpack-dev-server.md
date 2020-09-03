# Webpack Dev Server

- npm install webpack-dev-server
  - Allows us to preview our code as we write it in a browser
  - Also, when we make a change to the code and save the change we want Webapck to automatically compile the TypeScript to JavaScript so we can preview any changes
  - To do this we can spin up a live reload local development server

* In the webpack.config.js file we give output a property called publicPath and give it a value of "public" which is the relative path to where the build file is being stored
  - Allows the dev server to know where to serve the code in memory from
