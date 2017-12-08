from https://webpack.github.io/docs/tutorials/getting-started/

CD into this directory and run
```
webpack ./entry.js bundle.js --module-bind 'css=style-loader!css-loader'
```

then open index.html in a browser