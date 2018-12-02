* package.json由下面命令产生
```shell
npm init -y
```
* 安装依赖会自动改变package.json的dependencies
```shell
npm install webpack webpack-cli --save-dev
npm install --save lodash
```
* build
```shell
npx webpack --config webpack.config.js
```
