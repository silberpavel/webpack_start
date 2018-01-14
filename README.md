# webpack_start


```
webpack main.js bundle.js  //create build (in console)
```
```
<script src="bundle.js"></script>   // link bundle.js to HTML file
```

### config file

**name must be =>**  webpack.config.js
```
module.exports = {
  entry: './main.js',           // Entry file of our app
  output: {
    filename: 'bundle.js'       // file of the build
    }
}
```
