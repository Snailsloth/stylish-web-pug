# stylish-web-pug
webpack stylus pug

My adaptation of the repository:
https://github.com/LeeSwagger/webpack-starter
for my needs




### Development mode
```
npm start
```
### Production mode
```
npm run build
```


### Adding pages:
add 
```
new HtmlWebpackPlugin({
    filename: 'anotherpage.html',
    template: './src/anotherpage.pug',
    inject: false
    })
```
to "plugins" in webpack.config.js