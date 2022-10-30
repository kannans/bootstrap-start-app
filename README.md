### What is in his repo?

A simple `webpack` starter application with Bootstrap UI developement. This repo includes basic bootstrap 5 css, js and depedency plugins.

### How it started?

#### 1. Follow the simple steps and commands
```

mkdir project_name && cd project_name

npm init -y

npm i --save-dev webpack webpack-cli webpack-dev-server #Install webpack

npm i --save bootstrap @popperjs/core #Install bootstrap

npm i --save-dev autoprefixer css-loader postcss-loader sass sass-loader style-loader #Install additional dependencies 


mkdir {dist,src,src/js,src/scss} #Create basic project directory

touch dist/index.html src/js/main.js src/scss/styles.scss webpack.config.js #Create basic files 

```
#### 2. Configure Webpack


### How can we use this starter application

clone this repo

```
npm install 
npm run #Run the application command and open in http://localhost:8080
npm run build # production build, It generate html bundle, just copy and can use any static serving servers.
```

Start change your code from ./src/index.html
