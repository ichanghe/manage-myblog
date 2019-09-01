# manage-myblog
## 博客的后台管理系统
- 前端技术栈:vue admin 管理后台,vue.js,vuex
- 后端技术栈:Koa2,mysql,redis
目前的代码是前端部分代码,后台代码后期会分享出来
## vue-element-admin框架简介

[vue-element-admin](https://panjiachen.github.io/vue-element-admin-site/zh/) 是一个后台前端解决方案，它基于 [vue](https://github.com/vuejs/vue) 和 [element-ui](https://github.com/ElemeFE/element)实现。它使用了最新的前端技术栈，内置了 i18n 国际化解决方案，动态路由，权限验证，提炼了典型的业务模型，提供了丰富的功能组件，它可以帮助你快速搭建企业级中后台产品原型。


## 开发

```bash
# 克隆项目
git clone https://github.com/ichanghe/manage-myblog.git

# 进入项目目录
cd manage-myblog

# 安装依赖
npm install

# 建议不要直接使用 cnpm 安装依赖，会有各种诡异的 bug。可以通过如下操作解决 npm 下载速度慢的问题
npm install --registry=https://registry.npm.taobao.org

# 启动服务
npm run dev
```

浏览器访问 http://localhost:9527
