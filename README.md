# Reactjs-course
This repo contains a forum category covers broader discussion about React.js related topics.

## <a name='toc'>Table of Contents</a>
 1. [Introduction](#intro)
 2. [Setup & Installation](#setup)
 
 
 #### [[⬆]](#toc) <a name='intro'>Introduction:</a>
 
 1. What is React?  
 -  React.js is an efficient and flexible JavaScript library for building user interfaces.  
 -  The main focus is building UI as fast as possible.  
 -  So this is used to Single Page Application.  
 -  Means Complete Website in Single Page.  
 
 2. Why React is fast?  
 -  React uses Virtual Dom  
 -  Virtual Dom update only required list
 -  Real Dom update complete list
 
 3. Why learn react?  
 -  Maintained by Facebook so it will long Term Player in the Market.  
 -  Higher Demand due to fast Speed.  
 -  Large Community for you support.  
 -  Mobile App Development with React-Native.  
 
 #### [[⬆]](#toc) <a name='setup'>Setup & Installation:</a>  
 **You’ll need to have Node 14.0.0 or later version on your local development machine** (but it’s not required on the server). We recommend using the latest    LTS version. You can use nvm (macOS/Linux) or nvm-windows to switch Node versions between different projects.  
 
 To create a new app, you may choose one of the following methods:  
 
 #### npx
 ```
 npx create-react-app my-app
 ```  
 (<a href="https://nodejs.dev/en/learn/the-npx-nodejs-package-runner">npx</a> is a package runner tool that comes with npm 5.2+ and higher.)  
 
 #### npm
 ```
 npm init react-app my-app
 ```  
 _`npm init <initializer>` is available in npm 6+_  
 #### yarn
 ```
 yarn create react-app my-app
 ```  
 
 _<a href="https://classic.yarnpkg.com/en/docs/cli/create/">`yarn create <starter-kit-package>`</a> is available in Yarn 0.25+_  
 
 It will create a directory called `my-app` inside the current folder.
Inside that directory, it will generate the initial project structure and install the transitive dependencies:  

```
my-app
├── README.md
├── node_modules
├── package.json
├── .gitignore
├── public
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
└── src
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── index.css
    ├── index.js
    ├── logo.svg
    └── serviceWorker.js
    └── setupTests.js
```  

No configuration or complicated folder structures, only the files you need to build your app.
Once the installation is done, you can open your project folder:  
```
cd my-app
```  
Inside the newly created project, you can run some built-in commands:  

#### npm start or yarn start  
Runs the app in development mode.
Open http://localhost:3000 to view it in the browser.

The page will automatically reload if you make changes to the code.
You will see the build errors and lint warnings in the console.  

## Other References:  
[How to Create an app](https://github.com/facebook/create-react-app#npx)
