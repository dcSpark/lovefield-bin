# Lovefield

This is the build generated from [this PR](https://github.com/dcSpark/lovefield/pull/1)

Some notes on how to build:

1. `npm install`
2. `npm run build`
3. replace the end of the generated `lovefield.min.js` file (`}.bind(window))()`) to `try{if(module){module.exports=lf;}}catch(e){}}.bind(window))()`
