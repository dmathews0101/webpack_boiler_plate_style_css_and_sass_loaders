Installing webpack

npm i -D webpack@2.2.0
npm -g i webpack@2.2.0

Using webpack through command line

webpack ./src/app.js ./dist/app.bundle.js
webpack ./src/app.js ./dist/app.bundle.js -p
webpack ./src/app.js ./dist/app.bundle.js -p --watch


Using webpack after creating the webpack config file and creating a new script

npm run dev

---------------------------

installing html webpack plugin
Dynamic Title
Scripts injecting

html-webpack-plugin  

npm i html-webpack-plugin --save-dev
npm i html-webpack-plugin@2.26.0 --save-dev

npm run dev

----------------------------
loading css files

npm install css-loader --save-dev
npm install css-loader@0.26.1 --save-dev

npm install style-loader --save-dev
npm install style-loader@0.13.1 --save-dev

npm install sass-loader node-sass --save-dev
npm install sass-loader@4.1.1 node-sass@4.4.0 --save-dev

npm install sass-loader@4.1.1 --save-dev
npm install node-sass@4.4.0 --save-dev

npm install node-sass --save-dev
npm install node-sass@4.14.1 --save-dev

npm install extract-text-webpack-plugin -D

Unmet peer dependency webpack@2.2.0

npm view extract-text-webpack-plugin versions

npm install extract-text-webpack-plugin@2.0.0-rc.0 --save-dev
