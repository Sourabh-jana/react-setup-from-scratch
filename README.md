### 1. Initialize Your Project

    npm init -y

### 2. Install core `react` libraries

    npm install react react-dom

### 3. Install `webpack` for bundling and development server

    npm install --save-dev webpack webpack-cli webpack-dev-server html-webpack-plugin

### 4. Install `babel` for transpiling JSX and modern JavaScript.

    npm install --save-dev babel-loader @babel/core @babel/preset-env @babel/preset-react

### 5. Create a `webpack.config.js`

    $ touch webpack.config.js

### 6. Create files

    $ mkdir public src
    $ touch public/index.html
    $ touch src/index.js src/App.jsx

### 7. Build and Start the Development Server

    npx webpack serve --mode development
