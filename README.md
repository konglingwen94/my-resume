# 联系方式

- 手机：16692669622
- 微信号：16692669622
- Email：794430774@qq.com
- Twitter：https://twitter.com/konglingwen94

# 个人信息

- 孔令文/男/1994
- 从事行业：互联网/WEB 独立开发者
- 教育程度：专科/图形图像/2013~2015
- 工作年限：3 年
- 职业经历：4 年
- 目前居住地：郑州

---

- Github：<https://github.com/konglingwen94>
- 技术博客：<https://juejin.cn/user/2154698523818328>
- 学习笔记：<https://konglingwen94.github.io/my-study-notes>
- 期望职位：**中级前端开发工程师**，**WEB 全栈（NodeJs+MongoDB 方向）开发工程师**
- 期望薪资：税前月薪 14k~17k，特别喜欢的公司可例外
- 期望城市：不限

# 职业经历（按照时间线倒叙排列）

## 自由学习（2019 年 9 月~2020 年 12 月）

> 此阶段时间本人学习的主要内容是**加强职业技能**，**实战 web 项目**、**提升前端素养**等方面，主要通过**互联网技术社区 ⇄ 本地电脑**的方式学习

### 开发、上线原创项目（2020 年 4 月~2020 年 12 月）

实战项目期间自己对**web 技术标准和规范**、**项目编码的可读性、维护性**、**代码书写规范**等方面有了更深入的理解和感悟、
并最终在实际开发中得以应用

#### [elm-seller-server](https://github.com/konglingwen94/elm-seller-server)

> 线上预览：<https://konglingwen94.github.io/elm-seller-server>

<details><summary>点击查看项目介绍</summary>

- 目录

```bash
├── model  // 数据库模型
│   ├── administrator.js
│   ├── seller.js
│   ├── rating.js
│   ├── category.js
│   └── food.js
├── helper
│   ├── validatorRules.json  // 参数验证规则
│   ├── mongoose.js  // mongoose连接脚本
│   ├── middleware.js // 项目中间件
│   └── util.js  // 工具函数
├── data // 数据库初始化数据
│   ├── seller.json
│   ├── ratings.json
│   └── goods.json
├── controller  // 控制器
│   ├── administrator.js
│   ├── seller.js
│   ├── rating.js
│   ├── category.js
│   └── food.js
├── config
│   └── config.default.json  // 项目配置文件
├── router
│   └── index.js  // 路由配置
├── scripts/          // 可执行脚本文件
│   ├── init-admin.js
│   └── init-database.js
├── package.json
├── package-lock.json
├── ecosystem.config.js  // pm2 开启服务器的配置文件
├── app.js      // 项目启动入口文件
└── README.md

```

- 技术栈

本项目是以`Koa`为应用框架，使用`mongoose`操作数据库搭建的`node`后端项目

路由管理：`koa-router`

参数校验：`koa-parameter`

参数解析：`koa-bodyparser`

静态资源托管：`koa-static`

请求资源压缩 : `koa-compress`

单页应用路由请求路径回退中间件 : `koa2-connect-histroy-api-fallback`

token 生成 ：`jsonwebtoken`

数据库密码加密 : `bcrypt.js`

</details>

---

#### [vue-seller-admin](https://github.com/konglingwen94/vue-seller-admin)

> 线上预览：<http://123.56.124.33:5000/admin>

<div style="display:flex;justify-content:space-between;">
<div style="width:90%">
<h3>主要功能</h3>
  
- [x] 店铺数据统计
- [x] 店铺配置
- [x] 管理员登录和退出
- [x] 商品的增删改查
- [x] 商品分类的增删改查
- [x] 商品上架/下架
- [x] 评价管理
- [x] 管理员账户的密码修改
- [x] 管理员账户信息修改
- [x] 记录浏览过的页面到应用顶部标签（tab-tag）
- [x] 分等级的多管理员
- [x] 抽屉菜单


</div>
  
<div>
    <h3>技术栈</h3>

本项目主要使用`element-ui`作为应用 UI 的组件库，使用了按需引入的配置方式，缩小了项目最终打包的体积。

其次第三方模块有`axios`,`vue-router` `v-charts`(基于 echart 封装的 vue 组件库)

</div>
</div>

---

#### [vue-elm-seller](https://github.com/konglingwen94/vue-elm-seller)

> 线上预览：<http://123.56.124.33:5000>

<div style="display:flex;justify-content:start;">
<div style="margin-right:30%">
<h3>主要功能</h3>
  
  - 商品菜单联动导航展示
  - 添加移除商品到购物车
  - 购物车商品列表
  - 清空购物车
  - 确认支付提示
  - 查看商品详情
  - 商品评价
  - 店铺综合评论
  - 商家信息展示
  - 商家收藏
  - 商家详情弹窗
  - 商品滚动列表菜单标题吸顶
  - 添加商品到购物车时的动画效果


</div>
  
<div>
    <h3>技术栈</h3>

- `vue`
- `better-scroll`
- `lib-flexible`
- `axios`
- `express`
- `node`
- `javascript`
- `less`
- `css`
- `es6/7`
- `webpack`
- `vue-cli`

</div>
</div>

---

#### [vue-bytedanceJob](https://github.com/konglingwen94/vue-bytedanceJob)

> 线上预览：<http://123.56.124.33:3000>

<div style="display:flex">
<div style="margin-right:40%">
<h3>主要功能</h3>

- [x] 首页
- [x] 公司信息介绍
- [x] 职位关键字搜索
- [x] 城市职位检索
- [x] 职位分类检索
- [x] 职位列表分页展示
- [x] 职位详情
- [x] 产品与服务
- [x] 员工故事
- [x] 校园招聘(外链)
- [x] 邮箱登录
- [x] 退出
- [x] 我的简历
- [x] 简历上传
- [x] 编辑简历
- [x] 保存简历

</div>
  
<div>
    <h3>技术栈</h3>

- `vue`
- `vue-router`
- `vue-cli`
- `less`
- `axios`
- `lodash`
- `es6~7`
- `express`
- `node-fetch`
- `http-proxy-middleware`

</div>
</div>

---

### 技术提升和实践 (2019 年 9 月~2020 年 3 月)

技术提升和实践的内容包括**web 前端开发相关的各种技术类 API 及其类库**、**nodejs 常用的 API 及其生态链**、**mongodb 常用的 API 和类库**等

#### 实战项目

##### [egg-nuxt-blog](https://github.com/konglingwen94/egg-nuxt-blog)（使用 nodejs 的上层框架`egg`和 vue 的上层框架`nuxt`搭建的一个全栈项目，可以作为开发项目技术栈选型参考使用）

<details><summary>点击查看目录结构</summary>

```javascript
 admin/  //管理后台目录
 ├── src/ //源文件
 │   ├── api/ // 请求接口
 │   │   ├── aboutus.js   // 关于我们
 │   │   ├── articles.js   // 文章管理
 │   │   ├── auth.js   //  管理员
 │   │   ├── categories.js   // 分类
 │   │   ├── comments.js   //  文章评论
 │   │   ├── messages.js   // 留言墙
 │   │   ├── request.js   //  Axios请求实例
 │   │   └── tags.js   // 标签
 │   ├── assets/   //  静态资源
 │   │   ├── css/   //  样式
 │   │   │   └── overwrite.css   // 覆盖默认样式
 │   │   └── logo.png   //图片
 │   ├── components/   // 组件
 │   │   ├── CellPopover.vue   //鼠标悬浮文字预览浮窗
 │   │   ├── Header.vue   //页面头部
 │   │   ├── Menu.vue   //左侧菜单
 │   │   ├── Panel.vue   //主体内容面板
 │   │   ├── Pell.vue   //富文本编辑器
 │   │   └── Upload.vue   //资源上传
 │   ├── layouts/   //页面功能布局
 │   │   ├── Basic.vue   //主体布局
 │   │   ├── NotFound.vue   //不存在路由页面展示
 │   │   └── User.vue   //用户登陆
 │   ├── store/   //数据状态
 │   │   ├── aboutus.js   //关于我们数据模块
 │   │   └── index.js   //全局数据模块
 │   ├── utils/   //功能文件
 │   │   ├── element-ui.js   // 按需引入组件
 │   │   ├── global-registration.js   //注册自定义组件
 │   │   └── helper.js   //帮助函数库
 │   ├── views/   //路由页面
 │   │   ├── Article/   //文章
 │   │   │   ├── Editor.vue   //文章编辑
 │   │   │   └── List.vue   //列表展示
 │   │   ├── Author/   //作者
 │   │   │   └── index.vue
 │   │   ├── Carousel/   //轮播图
 │   │   │   └── index.vue
 │   │   ├── Category/   //分类
 │   │   │   └── List.vue
 │   │   ├── Comment/   //文章评论
 │   │   │   └── List.vue
 │   │   ├── Dashboard/   //主面板
 │   │   │   └── index.vue
 │   │   ├── Guestbook/   //留言墙
 │   │   │   └── List.vue
 │   │   ├── Login/   //登陆
 │   │   │   └── index.vue
 │   │   ├── Platform/   //平台
 │   │   │   └── index.vue
 │   │   ├── Security/   //安全
 │   │   │   └── index.vue
 │   │   └── Tag/   //标签
 │   │       └── index.vue
 │   ├── App.vue   //入口组件
 │   ├── main.js   //入口文件
 │   └── router.js   //路由配置文件
 ├── babel.config.js
 ├── package-lock.json
 ├── package.json
 ├── README.md
 ├── vue.config.js
 app/  //服务端源文件
 ├── controller/   //控制器
 │   ├── aboutus.js   //关于我们
 │   ├── admin.js   //管理员
 │   ├── article.js   //文章
 │   ├── category.js   //文章分类
 │   ├── comment.js   //文章评论
 │   ├── guestbook.js   //留言墙
 │   ├── tag.js   //文章标签
 │   └── upload.js   //资源上传
 ├── extend/   //Egg框架功能扩展
 │   ├── context.js   //请求上下文
 │   └── helper.js   //帮助函数
 ├── middleware/   //中间件
 │   ├── adminRequired.js   //管理员是否登陆权限验证
 │   ├── apiRouterParameterValidator.js   //参数全局校验
 │   ├── compress.js   //资源压缩
 │   ├── docs.js   //文档资源托管
 │   ├── errorHandler.js   //错误处理
 │   ├── history.js   //处理vue-router使用history模式
 │   ├── nuxtRender.js   //服务端渲染
 │   ├── platformENV.js   //客户端平台判断
 │   ├── responseHandler.js   //统一数据响应
 │   ├── siteTraffic.js   //文件访问量跟踪（待完善）
 │   └── upload.js   //资源上传
 ├── model/   //数据库集合模型
 │   ├── aboutus.js   //关于我们
 │   ├── admin.js   //管理员
 │   ├── article.js   //文章
 │   ├── category.js   //分类
 │   ├── comment.js   //文章评论
 │   ├── guestbook.js   //留言墙
 │   └── tag.js   //标签
 ├── router/   //接口路由
 │   ├── aboutus.js   //关于我们
 │   ├── admin.js   //管理员
 │   ├── article.js   //文章
 │   ├── category.js   //分类
 │   ├── comment.js   //文章评论
 │   ├── guestbook.js   //留言墙
 │   ├── proxyService.js   //代理第三方数据请求
 │   ├── tag.js   // 标签
 │   └── upload.js   //资源上传
 ├── types/   //字段类型
 │   └── request.js   //请求类型定义
 ├── package.json
 ├── README.md
 config/   //项目配置
 ├── config.default.js   //默认配置
 ├── config.local.js   //本地环境
 ├── config.prod.js   //线上环境
 ├── defaultConfiguration.json   //数据库初始化数据
 ├── plugin.js   //插件
 documentations/   //文档
 ├── api/   //接口
 │   ├── admin.md   //管理员
 │   ├── article.md   //文章
 │   ├── category.md   //分类
 │   ├── comment.md   //文章评论
 │   ├── guestbook.md   //留言墙
 │   ├── README.md   //指南
 │   └── tag.md   //标签
 ├── database/   //数据库字段定义
 │   ├── admin.md   //管理员
 │   ├── article.md   //文章
 │   ├── category.md   //分类
 │   ├── comment.md   //文章评论
 │   ├── guestbook.md   //留言墙
 │   ├── README.md   //指南
 │   └── tag.md   //标签
 ├── configurations.md   //项目配置指南
 ├── README.md   //项目概述
 logs/   //服务器日志
 public/ // 项目打包目录
 run/   //服务器运行状态
 scripts/   //自定义脚本
 ├── init-data.js   //初始化管理员
 web/   //客户端源文件目录
 ├── assets/   //静态资源
 │   └── css/   //样式
 │       ├── global.css   //全局样式
 │       ├── mixin.less   //定义混合样式类
 │       ├── reset.css   //覆盖默认样式
 │       └── page-transition.css   //页面过渡动画
 ├── components/   //自定义组件
 │   ├── ArticleItem.vue   //文章项
 │   ├── ArticleList.vue   //文章列表
 │   ├── Footer.vue   //网站底部
 │   ├── Header.vue   //网站头部
 │   └── Suggestion.vue   //文章相关推荐
 ├── layouts/   //网站布局
 │   ├── Article.vue   //文章布局
 │   └── Public.vue   //公共布局
 ├── middleware/   //中间件
 ├── pages/   //路由页面
 │   ├── aboutus/   //关于我们
 │   │   └── index.vue   //
 │   ├── folders/   //文章分类
 │   │   └── index.vue
 │   ├── articles/
 │   │   ├── index.vue   // 文章首页列表
 │   │   └── _id.vue   //文章详情页
 │   ├── messages   //留言墙
 │   │   └── index.vue   //
 │   └── index.vue   //网站首页
 ├── plugins/   //插件
 │   ├── element-ui.js   //UI组件库
 │   ├── global-components.js   //全局注册自定义组件
 │   ├── init-store.js   //开启数据持久化
 │   └── lib.js  //第三方组件库
 ├── services/   //数据请求
 │   ├── aboutus.js   //关于我们
 │   ├── articles.js   //文章
 │   ├── categories.js   //分类
 │   ├── comments.js   //文章评论
 │   ├── messages.js   //留言墙
 │   ├── request.js   //Axios请求实例
 │   └── tags.js   //标签
 ├── static/   //静态资源
 │   └── favicon.ico   //
 ├── store/   //数据存储
 │   ├── article.js   //文章
 │   ├── configuration.js   //配置
 │   ├── index.js   //模块入口
 │   ├── messages.js   //留言
 │   └── weather.js   //天气
 ├── nuxt.config.js
 ├── package-lock.json
 ├── package.json
 ├── README.md
 app.js   //服务器启动入口文件
 package-lock.json   //
 package.json   //项目信息
 postcss.config.js   //
 README.md   //项目指南
```

</details>

---

##### [vue-blog-admin](https://github.com/konglingwen94/vue-blog-admin)（`vue`+`element-ui`搭建的博客管理后台类项目，可作为模板参考使用）

<details><summary>点击查看项目截图</summary>

![](https://p6-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/a97f99d749d244bd811b1c5424199365~tplv-k3u1fbpfcp-watermark.image)
<br/>

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/30e1f9d0b4ed4a6a97f9c1f448060341~tplv-k3u1fbpfcp-watermark.image)<br/>

![](https://p6-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/26fdfa66d75247cc86ca4c052bd32df3~tplv-k3u1fbpfcp-watermark.image)<br/>

![](https://p9-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/893b12362f5541ddb496169e90c3d82c~tplv-k3u1fbpfcp-watermark.image)<br/>

![](https://p9-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/39ce99806a1948ba8a423107dbab26bd~tplv-k3u1fbpfcp-watermark.image)<br/>

![](https://p6-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/4f67d65089394e1294b2c9d0a7a1fe1b~tplv-k3u1fbpfcp-watermark.image)

</details>

---

#### 造轮子

- [comment-message-editor](https://github.com/konglingwen94/comment-message-editor)（基于 vue 封装的留言信息编辑器组件）
- [message-tree](https://github.com/konglingwen94/message-tree)（基于 vue 封装的留言评论数组件）
- [good-swiper](https://github.com/konglingwen94/good-swiper)（基于 vue 封装的轮播图组件）
- [element-resize-event-polyfill](https://github.com/konglingwen94/element-resize-event-polyfill)（监听浏览器 DOM 元素原生 resize 事件的插件）

## 公司任职（担任前端开发工程师职位）

### 郑州简影网络科技有限公司 （ 2019 年 2 月 ~ 2019 年 8 月 ）

#### 管理后台项目（共四个）

##### 工作内容

在公司任职期间，我独立开发完成了**CSAP 剑桥暑期学生课程小程序**，**九鼎锐创网站**，**930 家庭医生公众号**，**股票众筹网站**对应的 4 个**管理后台项目**，所有项目均采用前后端分离的开发模式完成。在项目开发期间，我负责前端相关的开发工作，开发完页面模板后和后端开发人员进行联合调试，最后在测试人员测试结束后，完成对应用`bug`的修复工作。

在优化完善项目的过程中，对于**成功请求数据接口后刷新页面**的场景需求，我利用 Vue自身 **响应式数据**的特性，通过**更新组件缓存数据**的方法成功实现，最终完成了**加快页面更新速度**，**减少不必要的接口请求**等性能优化工作

##### 使用技术栈和工具

基础技术：`html/html5`,`css/css3`,`js`,`es6/7`、`json`

生产环境使用框架和库：`vue@2.x`,`vue-router`,`vuex`,`element-ui`,`axios`,`pell`、`@antv/g2`等第三方模块

开发中使用工具链：`vue-cli`,`vue-devtools`，`webpack`,`less`,`webpack-dev-server`,`babel`等工具

开发、调试工具和运行平台：`vscode`,`git`,`chrome`,`postman`,`window7`

##### 应用的主要功能

- [x] 页面初始化后以表格展示的方式渲染数据
- [x] 配合 API 接口创建用户提交的数据，并重新渲染页面
- [x] 对页面表格内数据的删除，更新功能
- [x] 在各页面底部提供用户操作分页器来展示数据的功能
- [x] 项目首页以可视化的图表方式显示应用统计的相关数据
- [x] 注册管理员账户和缓存登录的用户信息到浏览器本地存储的功能
- [x] 修改账户名和密码

#### 参与客户端项目开发

在公司任职期间，我参与并局部开发了**CSAP 剑桥暑期学生课程**小程序，[九鼎锐创](http://www.jiudingrc.com/)网站，**930 家庭医生**微信公众号这三个客户端项目。其中**930 家庭医生**公众号由我个人独立开发完成，此应用主要包括**微信登录**、**在线预约**、**支付订单**等功能。

###

---

### 新技术学习 & 接触开源社区（辞职期间，2018 年 9 月~2019 年 1 月）

#### 加入 [Github](https://github.com/konglingwen94) 开源社区并发布首个项目 [vue-music](https://github.com/konglingwen94/vue-music)

<html>
<table border="0">
<tr>
  <th style="width:50%">主要功能</th>
  <th width="50%">技术栈</th>

</tr>

<tr>
<td  style="width:50%">

- 歌手列表
- 歌手详情
- 歌单分类
- 歌单列表
- 歌单详情
- 歌曲列表
- 视频列表
- 视频播放
- 热门搜索
- 搜索历史
- 搜索列表
- 全屏播放器
- 迷你播放器
- 播放控制
- 歌词展示

</td>
<td>

- `vue + vuex + vue-router`
- `express` 搭建服务端 API
- `mint-ui + cube-ui + vux`
- `lyric-parser`把给定的歌词字符串解析成有格式文本的一个插件
- `good-storage` 快速操作 localStorage 的第三方插件
- `vue-lazyload` 一个基于`Vue`的图片懒加载插件
- `lib-flexible` 由淘宝开发的移动端适配方案库
- `sublime` 轻量级的代码编辑器
</td>
</tr>
</table>
</html>

- 加入 [npm](https://www.npmjs.com/~konglingwen) 社区，并发布首个 npm 包 [anydirectory](https://www.npmjs.com/package/anydirectory)

- 初步学习 `nodejs`技术，搭建环境并练习应用常用的`API`

- 学习 `Vue` 框架及其全家桶技术和 `webpack` 前端工程化开发模式

---

### 河南汇国医疗股份有限公司 （ 2018 年 6 月 ~ 2018 年 8 月 ）

#### 河南汇国医疗股份有限公司网站 （包括 PC 端，移动端,微信小程序）

我在[河南汇国医疗股份有限公司](https://www.hgyl120.com "由于离手此项目时间过长，预览效果可能有很大变化")PC 端网站这个项目中，根据设计师提供的 UI 设计稿完成了网站页面的布局和样式。网站是使用”DedeCms“技术为模板在服务端渲染页面的网站。网站的主要功能由**顶部轮播图**，**导航栏切换页面**，**手风琴动效**等包含多个交互功能的页面构成，使用的技术主要有`html`,`css`,`js`,`jquery`,`swiper`,`less`。

**汇国控股**微信小程序使用`web-view`组件引入移动端页面的方式并配合其他组件开发完成，并负责了小程序后期申请上线的工作

# 教育经历

## 自学、入门 WEB 前端开发（2017 年~2018 年）

本阶段主要依靠互联网上的免费学习平台自学 web 开发技术，学习内容有

- html,html5
- css,css3
- javascript
- jquery
- Editplus/Hbuilder

## 从事其他行业（2015 年~2016 年）

## 商丘职业技术学院（2013 年~2014 年）

在校期间本人报选了图形图像专业,学习课程主要有

- photoshop
- coreldraw
- word/excel/ppt
- 计算机基础知识

# 开源项目和作品

## 开源项目

### 应用

- [vue-bytedanceJob](https://github.com/konglingwen94/vue-bytedanceJob)（Vue 仿写字节跳动招聘网站的单页面应用）
- [vue-elm-seller](https://github.com/konglingwen94/vue-elm-seller)（高仿饿了么商家店铺的单页面应用）
- [vue-music](https://github.com/konglingwen94/vue-music)（爬取 QQ 数据的移动端音乐应用）
- [vue-seller-admin](https://github.com/konglingwen94/vue-seller-admin)（Vue + ElementUI 搭建的管理后台系统）
- [elm-seller-server](https://github.com/konglingwen94/elm-seller-server)（Koa+Mongodb 搭建的的外卖商家服务端项目）
- [egg-nuxt-blog](https://github.com/konglingwen94/egg-nuxt-blog)（egg+nuxt 搭建的 WEB 全栈项目，以技术应用为主）
- [vue-blog-admin](https://github.com/konglingwen94/vue-blog-admin)（vue+element-ui 开发的博客管理后台，可作为通用管理后台类项目参考二次开发）

### 轮子

- [comment-message-editor](https://github.com/konglingwen94/comment-message-editor)（基于 vue 封装的留言信息编辑器组件）
- [message-tree](https://github.com/konglingwen94/message-tree)（基于 vue 封装的留言评论数组件）
- [good-swiper](https://github.com/konglingwen94/good-swiper)（基于 vue 封装的轮播图组件）
- [anydirectory](https://github.com/konglingwen94/anydirectory)（基于 node 开发的静态资源托管服务器模块包）
- [element-resize-event-polyfill](https://github.com/konglingwen94/element-resize-event-polyfill)（监听浏览器 DOM 元素原生 resize 事件的插件）

---

## 技术文章

- [Koa+Mongodb 搭建商家店铺服务端项目总结](https://juejin.cn/post/6907803934031609863)
- [Vue+ElementUI 搭建商家店铺管理后台项目总结](https://juejin.cn/post/6906796790390095879/)
- [Vue 全新重构升级字节跳动招聘网站 2.0 总结（下）](https://juejin.cn/post/6868884040029011975)
- [Vue 全新技术栈重构黄老师饿了么商家应用](https://juejin.cn/post/6844904202624303118)
- [Vue 全栈技术重构字节跳动招聘网站总结 ( 上 )](https://juejin.cn/post/6844904199289831432/)
- [如何成为一名卓越的前端工程师（摘抄）](https://juejin.cn/post/6844904130570354701/)
- [深入掌握 javascript 中的 this 能帮助我们做什么？](https://juejin.cn/post/6844904129685356557)
- [如何选择你的数据遍历方式](https://juejin.cn/post/6844904128045400078)
- [封装基于 Vue 的留言评论树组件](https://juejin.cn/post/6844904121821052936)
- [实现 javascript 对象的深拷贝](https://juejin.cn/post/6844904115076595720)
- [封装一个通用的轮播图组件（基于 Vue）](https://juejin.cn/post/6844904113327587335)
- [封装一个基于 Vue 的评论留言编辑器组件](https://juejin.cn/post/6844904103559036936)
- [如何手动实现 DOM 元素的 Resize 事件侦听器](https://juejin.cn/post/6844904100107124744)

# 技能清单

## 开发技术

- Web 开发：HTML/HTML5、CSS/CSS3、Javascript、DOM/BOM、ES6/7/Next、JSON、NodeJs
- 前端框架、库、常用插件：Vue/Nuxt、JQuery、Axios、Lodash
- 前端工具：Webpack、Npm、Less、Babel、Eslint
- Vue 相关：Element-ui、vue-router、vue-devtools、vuex、cube-ui/mint-ui、vue-cli、vuepress、
- NodeJs 类库、管理工具：Koa、Mongoose、Express、Egg、node-inspector、nodemon、PM2
- 数据库、后端工具：MongoDB/MySQL、Postman、Linux 常用命令、SSH 基础命令
- 版本管理、仓库托管、文档和自动化部署工具：Git、Github、Markdown、github-actions、Linux 服务器
- 开发工具和运行平台：VSCode/Sublime，Chrome/Safari、MacBook/Window7

## 职业能力

- 精通`HTML`、`CSS`、`Javascript`技术并能灵活运用
- 精通`VueJs`技术，掌握其运行机制，能封装前端通用组件，并对 VueJs 的**设计思想**、**重要特性实现方式**有深入的理解和研究
- 掌握浏览器运行原理和`HTTP`协议的通信过程 
- 对**面向对象**、**MVVM 架构**、**组件关注点分离**等编程思想有深入的理解和实践
- 对 web 技术标准和规范有深入的理解和体会
- 对 web 应用有一定的架构能力，能够操作项目全栈开发的各个环节和发布流程
- 对前端工程化、组件化、模块化、前后端分离等开发模式有全面的认知及应用
- 突出的学习能力和独立的逻辑思维能力

## 软技能

- 熟练使用 WEB 开发相关的调试工具并快速定位`bug`
- 熟练使用`Git`、`Github`管理代码和项目
- 能阅读英文技术文档
- 熟练使用 Markdown 语言编写 README 文档
- 熟练使用键盘打印中英文字符
- 对互联网产品的**设计**、**功能**有独立的审美和体验
- 熟练操作 Window、Mac 操作系统和其常用的软硬件工具

# 学习过程

自本人从事互联网行业工作以来，掌握的所有知识和技术是通过个人**学习**、**实践**、**积累**、**总结**后所得，其中在公司任职期间积累了项目协作开发的一些经验。目前本人入住的互联网技术社区有 [Github](https://github.com/konglingwen94)、[掘金](https://juejin.cn/user/2154698523818328/)、[Segmentfault](https://segmentfault.com/u/konglingwen94)、 日常工作中解决问题常用的搜索网站有`Google`、`Baidu`、`Github`、`StackOverflow`等

# 自我评价

本人对 WEB 前端开发及其相关的技术拥有浓厚的兴趣，平常善于学习和钻研 web 技术，时常关注行业新技术的发展并能逐渐地学习。在日常的项目开发中，自己对项目的**可维护性**、**架构设计**、**代码书写规范**等方面有严格的要求，在满足项目场景需求的同时善于思考多种解决方案，并能总结出高效优雅的方法积累运用。

## 生活和爱好

电影、篮球、跑步、新闻、互联网

# 致谢

感谢您花时间阅读我的简历，期待能有机会和您共事。
