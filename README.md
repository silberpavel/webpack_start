# webpack_start

* webpack main.js bundle.js  //create build
* <script src="bundle.js"...    // link to HTML file

### config file

* name must be => webpack.config.js
module.exports = {
  entry: './main.js',           // Entry file of our app
  output: {
    filename: 'bundle.js'       // file of the build
    }
}
