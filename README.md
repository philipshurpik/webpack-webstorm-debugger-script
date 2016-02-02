# webpack-webstorm-debugger-script
Script to debug webpack plugins and loaders with WebStorm.

Kind regards to http://blog.assaf.co/debugging-a-webpack-plugin-loader/

#### Usage:
Place webstorm-debugger.js in a folder with your webpack.config
Right click on script and select Debug option

Note: If not works - please install webpack globally `npm install webpack -g`
Note 2: If WebStorm not stops on breakpoints - please setup them directly with `debugger;` command