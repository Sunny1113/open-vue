# VUE3.0版API

## 功能描述

- [x] 登录、注册
- [x] 信息管理：列表、新增、编辑、删除
- [x] 用户模块：列表、新增、编辑、删除
- [x] 动态路由：菜单权限（根据功能、角色分配）、按钮级权限
- [x] 七牛云图片第三方管理
- [x] vue组件化开发
- [x] axios拦截器
- [x] Elementui二次封装组件
- [x] ....

## 技术栈

- [x] vue
- [x] vuex
- [x] vue-router
- [x] elementUI
- [x] sass
- [x] axios
- [x] qiniu-js
- [x] sha1
- [x] nginx
 构建vue项目、代码仓库管理

### Vuex状态管理仓库、token登录检验

- Vuex、State、Getters、Mutations、菜单导航收起、展开
- cookie存储，sessionStorage存储、localStorage存储、JSON.parse、JSON.stringify
- Vuex的action异步、同步、modules模块管理状态数据
- router.beforeEach路由守卫，检测toKen是否非法进入后台，to、from参数、next方法、Vuex命名空间
- 登录存储token、token存在基础逻辑进入后台
- 退出后台清除token、防止非法进入、GIT代码合并、提交当天开发的代码

### 信息管理功能开发、接口联调

- 信息管理模块，一级分类接口、获取分类接口、onMounted、相关优化
- 信息管理模块，删除接口、修改接口
- 接口封装，vue3.0封装方式，vuex的actions方式，为后期维护方便
- 添加信息接口、获取列表接口、分页处理请求数据、获取分类优化，变量优化
- 单记录、批量删除接口、table组件数据加载优化、formatter属性返回值、日期组件配置数据格式、筛选条件处理
- 信息编辑接口、添加子级分类接口、请求全部分类接口

### 信息管理详情页开发、接口联调

- router路由跳转、5种传参方式、vuex配合HTML5本地储存
- 详细页数据读取、初始化数据、富文本编辑器、vue devTool依赖
- elementui upload组件结合七牛云第三方储存，七牛云建立空间、域名绑定、解析

### 组件化开发模式

- 真正理解vue组件化开发、组件概念、优势、全局组件component、局部组件import、从源头解决BUG
- vue生命周期，组件生命周期，3.0改写2.0组件
- vue3.0生命周期，封装el-table组件
- 封装el-table组件，v-slot插槽3种方式，数据绑定
- 封装el-table组件，数据请求，整合url请求地址，统一api文件夹管理
- elementUI 页码组件、业务逻辑拆分页码，配置项
- vue2.0 mixins混入、按需混入、全局混入

### 用户管理功能

- 省、市、区、街道组件封装、业务逻辑抽离
- 省市区数据返回，el-radio、el-checkbox、获取角色管理API
- 用户添加接口、json对象深拷贝、浅拷贝用法及注意事项
- 组件通讯开始篇.sync、elemntUI Switch组件、用户列表、删除接口联调

### 动态路由开发

- 动态路由开发，以系统分配路由，系统列表接口
- 动态路由开发，以角色分配路由
- 按钮级权限，自定义指令处理

### 缓存、性能、优化

- 组件缓存keep-alive、接口优化避免资源浪费
- BUG修复、监听路由变化、环境变量参数配置
- 404页面问题修复，退出接口联调

### 部署项目，nginx配置

- ECS云服务器购买、nginx安装、端口配置、防火墙
- nginx配置、多项目部署、单项目部署、iptables安装配置
- nginx配置、日志查看，proxy_pass指向配置、调通接口数据、域名解析访问项目



