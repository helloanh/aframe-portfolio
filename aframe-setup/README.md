# Setting Up Webpack 4

```js
mkdir project  && cd project  
npm init -y  
npm i webpack --save-dev  
npm i webpack-cli --save-dev  
touch index.js index.html bundle.js  
```

Index.html  

```html

#add script at the end  
<script src"bundle.js"></script>
```

```js  
#add script in package.json
"scripts": {
  "build": "webpack"
}

# run npm 
npm run build
```

### Notice the default webpack config    
```
The concept of zero configuration in webpack 4 applies to:  

the entry point. Default to ./src/index.js  
the output. Default to ./dist/main.js  
production and development mode (no need to create 2 separate confs for production and development)  

```



Source: https://www.valentinog.com/blog/webpack-4-tutorial/  

