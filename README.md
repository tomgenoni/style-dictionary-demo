# style-dictionary-demo
Working example of design token management using Amazon’s [style-dictionary](https://amzn.github.io/style-dictionary/#/). This library makes it easy to manage variables in an agnostic way with comments and other metadata and generate variables for many different output targets.

## Install

```shell
yarn && yarn build
```

This will create a `build` folder inside the `example` directory. 

## Files

Inside the `example` directory you’ll see:

-  `tokens` directory that houses the values. These are simple key/values that are converted into any output you need: SCSS, JavaScript, iOS, Android, etc. 
-  `config.json` file determines the platforms that will be output and a number of transformation settings. 
-  `build` directory holds the output files. In this case 
   - a single SCSS file with SCSS variables
   - a single CSS file with CSS variables 
   - two JS files with variable exports

