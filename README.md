<<<<<<< HEAD
# web
123
=======
### 初始化 packeage.json
> npm init  或者  npm init -y  , 其中-y表示默认

### 安装webpack webpack-cli
> npm i webpack webpack-cli -D  或者 npm i webpack webpack-cli --save-dev
> --save-dev 的简写 -D

### 创建webpack配置文件
> touch webpack.config.js

### 在package.json文件的script写入打包命令
```javascript
"script": {
  "build": "webpack --config=webpack.config.js"
}
```

### loader处理css
> npm i style-loader css-loader -D

### loader处理less
> npm i style-loader css-loader less-loader less -D

### 分离css
> npm i mini-css-extract-plugin -D

### 处理图片
> npm i file-loader url-loader -D

### 处理模板html
> npm i html-webpack-plugin -D


### 处理html模板的图片
> npm i html-withimg-loader -D
>>>>>>> c9e9e5c130d4c26ef25577f2d1de8a226a8a6de6
