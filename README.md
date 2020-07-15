# 0511-ES6转ES5
ES6转ES5
1.npm install --save-dev babel-polyfill

2.在main.js文件引入：import 'babel-polyfill'

3.在build文件夹下找到webpack.base.conf.js

修改入口路径：app: ['babel-polyfill', './src/main.js']
