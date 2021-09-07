# style-dictionary-demo
Working example of design token management.

## Install

```shell
yarn && yarn build
```

This will create a `build` folder inside the `example` directory. 

## Files

Inside the `example` directory you’ll see a

-  `tokens` directory that houses the values. These are platform agnostic key/values that are converted into any output you need: SCSS, JavaScript, iOS, Android, etc. 
-  `config.json` determines the platforms that will be output and a number of transformation settings. 
- `build` directory holds the output files. In this case a single SCSS file and two JS files. 

