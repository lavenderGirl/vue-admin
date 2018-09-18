**demo**: [https://lavendergirl.github.io/vue-admin/](https://lavendergirl.github.io/vue-admin/dist/#/login)

# To start

This is a project template for [vue-cli](https://github.com/vuejs/vue-cli)

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8081
npm run dev

# build for production with minification
npm run build

```

# Learning channel
* [vue](https://cn.vuejs.org/)
* [Element-基于 Vue 2.0 的桌面端组件库](http://element-cn.eleme.io/#/zh-CN)
* [Mock生成随机数据](http://mockjs.com/) [Mock:语法学习](https://segmentfault.com/a/1190000010211622)
* [webpack-构建您的项目](https://webpack.js.org/)
* [axios-基于 promise 的 HTTP 库](https://github.com/mzabriskie/axios)
    * [axios中文文档](https://www.kancloud.cn/yunye/axios/234845)  

# Folder structure
* build - webpack config files
* config - webpack config files
* dist - build
* src -your app
    * api
    * assets
    * common
    * components - your vue components
    * mock
    * styles
    * views - your pages
    * vuex
    * App.vue
    * main.js - main file
    * routes.js
* static - static assets

# Theme
You can change theme by 
1. Generate theme packages by [https://elementui.github.io/theme-preview/#/](https://elementui.github.io/theme-preview/#/)
2. Put theme packages in src/assets/theme/
3. Edit src/main.js 
``` bash
   import 'element-ui/lib/theme-default/index.css'
   to
   import './assets/theme/your-theme/index.css'
```
4. Edit src/styles/vars.scss

![登录](https://i.loli.net/2018/09/18/5ba05e3161974.png)
![index](https://i.loli.net/2018/09/18/5ba05e661e6de.png)
![echart](https://i.loli.net/2018/09/18/5ba05e838ba49.png)

# Browser support

Modern browsers and IE 10+.

# License
[MIT](http://opensource.org/licenses/MIT)
