### What is in this repo?

A simple `webpack` starter boiler plate app for UI markup development. This repo includes basic bootstrap5 CSS, JS and depedency plugins.

### How this repo started?

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
Update the boiler plate configuration at `webpack.common.js` and `webpack.dev.js`files for developent.

### How can we use this starter application in development?

#### 1. Clone this repo `git clone git@github.com:kannans/bootstrap-start-app.git`

```
npm install #Make sure machine has node v16+
npm start #Run the application command and open in http://localhost:8080

```

#### 2. Where to make the code change?
   from `./src/index.html`


#### 3. How to use this at production ready?
 Production build, It generate static app html bundle at dist folder, just copy the dist folder 
 use at any static serving servers.
```
npm run build  #generate static build

```
