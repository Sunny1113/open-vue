# 腾讯公益·开放平台 (vuejs重构)

## src 目录结构
目录 | 说明 | 备注
---- | ---- | ----
assets | 图片，字体，sass资源文件 |
components | 组件 |
config | 配置文件 |
page | webpack页面入口 |
util | 工具集 |
views | 单页面路由业务组件 |

## src 目录外的文件说明
文件 | 说明 | 备注
---- | ---- | ----
[vue.config.js](https://cli.vuejs.org/zh/guide/webpack.html#%E7%AE%80%E5%8D%95%E7%9A%84%E9%85%8D%E7%BD%AE%E6%96%B9%E5%BC%8F) | webpack配置相关 |
[public](https://cli.vuejs.org/zh/guide/html-and-static-assets.html#public-%E6%96%87%E4%BB%B6%E5%A4%B9) | | HTML和静态资源
.browserslistrc | 浏览器兼容 | 

## 规范
1，公共组件就写在components, 页面组件写在页面的文件夹里components


## 第三方库

  * [弹层用layer](https://www.layui.com/doc/modules/layer.html)
  * 图标 [tnpm i font-awesome@4.6.3 -S]
  * [图片裁剪](http://tnpm.oa.com/package/cropperjs) 模块引入：tnpm i cropperjs -S
  * [日期选择器]
  <!-- * [tooltip](https://v3.bootcss.com/javascript/#tooltips)
  * [popover](https://v3.bootcss.com/javascript/#popovers) -->
  * [tree](http://tnpm.oa.com/package/bootstrap-treeview) v1.2.0
  * [分页]
  * [表格] bootstrap-table模块暂时只用了样式

## process.env.NODE_ENV 
windows: set NODE_ENV=dev && otherCommand

linux:  NODE_ENV=dev otherCommand
加了这个导致编译之后没有压缩

## 浏览器兼容
  Vue 不支持 IE8 及以下版本，因为 Vue 使用了 IE8 无法模拟的 ECMAScript 5 特性。但它支持所有兼容 ECMAScript 5 的浏览器

## 组件分类的
- 已补充的文档
  - 基本
    - button  [button、button-group]    按钮
    - icon  [icon、glyphicon]    图标
    - badge    标记
    - tag    标签
    - alert 警告

  - form
    - checkbox  [checkbox、checkbox-group]    多选框
    - form  [form、form-item]    表单
    - input    输入框
    - select            选择器
    - radio  [radio、radio-button、radio-group]    单选框
    - switch  开关

  - 第三方
    - cropper        图片裁剪

  - 其他
    - pagination          分页
    - collapse [collapse、collapse-item]    手风琴
    - panel    面板
    - step  [step、step-item]    步骤条
    - tab  [tab、tab-panel]    标签页
    - table  [table、table-column]  表格

  - transition (vue 动画 or 过渡)
    - collapse.js    手风琴的动画
    - transition.scss     这里定义自定义的transition class

  - 未补充的文档
    - tree    树

    - loading 加载
    - notify 通知
    - modal    
    - dialog   对话框
    - 动画
    - dropdown
      

  今日任务：
    2，table文档，table checkbox， 以及 sort排序

?isajax=1