
# 联系方式

- 微信号：16692669622
- Gmail：konglingwen94@gmail.com

# 个人信息

- 孔令文/男/1994
- 商丘职业技术学院/图形图像/2013
- 工作年限：4 年

- Github：<https://github.com/konglingwen94>
  - `150 stars`
  - `28 followers`
- 技术博客：<https://juejin.cn/user/2154698523818328>
- 期望职位：WEB 前端/全栈（Node.js + MongoDB 方向）开发工程师

# 职业经历

## 北京讯兔科技有限公司 （ 2021 年 1 月 ~ 2022 年 2 月 ）

### 研发产品

> Mindera 投研管理平台

Mindera 是一个集成了投研知识库、研究工具、投资管理三大模块的投研管理平台。该平台可以一站式完成知识生产(数据、图表、报告、图谱)、知识查看(研报/路演/图表库、个股分析)，投资管理(模拟组合、行业股票管理)等全流程投研工作。

> Alpha 券商服务平台

Alpha 券商服务平台是一个面向券商路演管理和知识管理的一站式服务平台，通过券商服务的线上化和集成化， 提升信息触达、优化供需匹配。

#### 岗位职责

1. 负责投研管理平台 web 前端的框架设计、功能开发和维护
2. 负责前端界面构建、兼容和优化，与产品、设计、开发、测试人员协同配合完成项目从需求评审到功能上线的全流程工作
3. 针对解决项目开发过程中如何处理公共业务和模块的依赖问题上，在经过和项目组开发人员评估研究后，最终选定了以抽离成独立的`npm`依赖包的方式为解决此问题的技术方案。在经过多个内部项目的使用和持续验证后，此方案稳定高效的支撑起了内部项目的落地和生产

#### 项目技术架构

> 产品项目采用以`qiankun`为主框架的微前端技术架构，其运行原理如下

- 由`Packages`提供基础设施的生命周期、核心服务、整体布局、路由鉴权、公共状态管理、公共插件

- 平台父应用读取微应用库暴露的配置清单后，通过`micro-app.js`模块动态注册到主应用路由表

- 微应用向外暴露入口文件`index.js`后，可被独立开发、调试、发布

- 基础设施（Packages）

  - 抽象基类（@packages/base）
  - 核心库（@packages/common）
  - 核心组件库（@packages/component）

- 平台应用（Platform Apps）

  - 子应用注册表（micro-app.js）
  - 用户管理

- 微应用库（Micro Apps）
  - 微应用清单（apps.json）
  - 分析师主页
  - 工作台
  - 路演服务

## 开发、上线原创项目（2020 年 5 月~2020 年 12 月）

> 实战项目期间自己对**web 技术标准和规范**、**项目编码的可读性、维护性**、**代码书写规范**等方面有了更深入的理解和感悟、
> 并最终在实际开发中得以应用

1. ### [elm-seller-server](https://github.com/konglingwen94/elm-seller-server)

> 线上预览：<https://konglingwen94.github.io/elm-seller-server>

#### 技术栈

`Koa`、`koa-router`、`koa-parameter`、`koa-bodyparser`、`koa-static`、`koa-compress`、`koa2-connect-histroy-api-fallback`、`jsonwebtoken`、`bcrypt.js`

---

2. ### [vue-seller-admin](https://github.com/konglingwen94/vue-seller-admin)

> 线上预览：<http://123.57.204.48:5000/admin>

#### 技术栈

本项目主要使用`element-ui`作为应用 UI 的组件库，使用了按需引入的配置方式，缩小了项目最终打包的体积。

其次第三方模块有`axios`,`vue-router` `v-charts`(基于 echart 封装的 vue 组件库)

---

3. ### [vue-elm-seller](https://github.com/konglingwen94/vue-elm-seller)

> 线上预览：<http://123.57.204.48:5000>

#### 技术栈

`vue`、`better-scroll`、`lib-flexible`、`axios`、`express`、`node`、`javascript`、`less`、`css`、`es6/7`、`webpack`、`vue-cli`

---

4. ### [vue-bytedanceJob](https://github.com/konglingwen94/vue-bytedanceJob)

> 线上预览：<http://123.57.204.48:3000>

#### 技术栈

`vue`、 `vue-router`、 `vue-cli`、 `less`、 `axios`、 `lodash`、 `es6~7`、 `express`、 `node-fetch`、 `http-proxy-middleware`

## 技术提升和实践 (2020 年 1 月~2020 年 4 月)

> 技术提升和实践的内容包括**Web 前端开发相关的各种技术类 API 及其类库**、**NodeJs 常用的 API 及其生态链工具**、**MongoDB 常用的 API 和类库**等

### 实战项目

1. #### [egg-nuxt-blog](https://github.com/konglingwen94/egg-nuxt-blog)（使用 nodejs 的上层框架`egg`和 vue 的上层框架`nuxt`搭建的一个全栈项目，可以作为开发项目技术栈选型参考使用）

- 项目访问地址：[https://github.com/konglingwen94/egg-nuxt-blog](https://github.com/konglingwen94/egg-nuxt-blog)
- 客户端线上地址：<http://123.57.204.48:7001>
- 管理后台线上地址：<http://123.57.204.48:7001/admin>
- 服务端文档地址：<https://konglingwen94.github.io/egg-nuxt-blog/index.html>

- 技术栈

  `egg`、`nuxt`、`axios`、`bcryptjs`、`egg-cors`、`egg-mongoose`、`egg-router-plus`、`egg-scripts`、`egg-validate`、`element-ui`、`gravatar`、`inflected`、`jsonwebtoken`、`koa-compress`、`koa-multer`、`koa2-connect-history-api-fallback`、`message-tree`、`mongoose`、`normalize.css`、、`pell`、`vue-weather-component`

---

2. #### [vue-blog-admin](https://github.com/konglingwen94/vue-blog-admin)（`vue`+`element-ui`搭建的博客管理后台类项目，可作为模板参考使用）

- 项目访问地址：[https://github.com/konglingwen94/vue-blog-admin](https://github.com/konglingwen94/vue-blog-admin)
- 线上地址: <https://konglingwen94.github.io/vue-blog-admin>

#### 技术栈

`axios`、`element-ui`、`normalize.css`、`pell`、`vue"`、`vue-router`、`vuex`

---

### 造轮子

> 访问地址：<https://github.com/konglingwen94>

1. [comment-message-editor](https://github.com/konglingwen94/comment-message-editor)（基于 vue 封装的留言信息编辑器组件）
2. [message-tree](https://github.com/konglingwen94/message-tree)（基于 vue 封装的留言评论树组件）
3. [good-swiper](https://github.com/konglingwen94/good-swiper)（基于 vue 封装的轮播图组件）
4. [element-resize-event-polyfill](https://github.com/konglingwen94/element-resize-event-polyfill)（监听浏览器 DOM 元素原生 resize 事件的插件）

## 新技术学习 & 加入开源社区（2018 年 7 月~2018 年 10 月）

### 在 [Github](https://github.com/konglingwen94) 开源社区发布首个项目 [vue-music](https://github.com/konglingwen94/vue-music)

> 线上地址: <http://123.57.204.48:4000>

#### 技术栈

`vue `、 `vuex`、 `vue-router`、`express` 、`mint-ui` 、`cube-ui`、`vux`、`lyric-parser`、`good-storage`、`vue-lazyload`、`lib-flexible` 、`sublime`

---

### 技术学习

- 加入 [npm](https://www.npmjs.com/~konglingwen) 社区，并发布首个 npm 包 [anydirectory](https://www.npmjs.com/package/anydirectory)

- 初步学习 `nodejs`技术，搭建开发环境并练习使用常用`API`

- 学习 `Vue` 框架及其全家桶技术和 `webpack` 前端工程化开发模式

## 郑州简影网络科技有限公司 （ 2018 年 11 月 ~ 2020 年 1 月 ）

### 管理后台项目（共四个）

#### 工作内容

在公司任职期间，我独立开发完成了**CSAP 剑桥暑期学生课程小程序**，**九鼎锐创网站**，**930 家庭医生公众号**，**股票众筹网站**对应的 4 个**管理后台项目**，所有项目均采用前后端分离的开发模式完成。在项目开发期间，我负责前端相关的开发工作，开发完页面模板后和后端开发人员进行联合调试，最后在测试人员测试结束后，完成对应用`bug`的修复工作。

在优化完善项目的过程中，对于**成功请求数据接口后需要刷新页面**的场景需求，我利用 Vue 自身 **响应式数据**的特性，通过**更新组件缓存数据**的方法成功实现，最终完成了**加快页面更新速度**，**减少不必要的接口请求**等性能优化工作

#### 使用技术栈和工具

基础技术：`html/html5`,`css/css3`,`js`,`es6/7`、`json`

生产环境使用框架和库：`vue@2.x`,`vue-router`,`vuex`,`element-ui`,`axios`,`pell`、`@antv/g2`等第三方模块

开发中使用工具链：`vue-cli`,`vue-devtools`，`webpack`,`less`,`webpack-dev-server`,`babel`等工具

开发、调试工具和运行平台：`vscode`,`git`,`chrome`,`postman`,`window7`

#### 应用的主要功能

- [x] 页面初始化后以表格展示的方式渲染数据
- [x] 创建用户提交的表单数据并和服务端 API 接口完成对接
- [x] 对页面内表格数据的删除，更新功能
- [x] 分页展示数据的功能
- [x] 首页数据可视化展示
- [x] 管理员登录和 token 本地存储
- [x] 修改账户名和密码

### 参与客户端项目开发

在公司任职期间，我参与开发了**CSAP 剑桥暑期学生课程**小程序，[九鼎锐创](http://www.jiudingrc.com/)网站，**930 家庭医生**微信公众号这三个客户端项目的局部功能。我个人独立开发完成的项目是**930 家庭医生**公众号，此应用包含了**微信登录**、**在线预约**、**支付订单**等功能。

---

## 河南汇国医疗股份有限公司 （ 2018 年 1 月 ~ 2018 年 6 月 ）

### 河南汇国医疗股份有限公司网站 （包括 PC 端，移动端,微信小程序）

此应用全部由我个人开发完成，工作的主要内容是**根据设计稿编写前端页面样式**、**根据产品需求实现页面交互功能**、**渲染数据生成静态页面**、**部署静态资源到服务器**。网站包含了数十个功能丰富的页面，其中主要的交互功能有**轮播图**、**一级/二级导航菜单**、**手风琴动效**、**抽屉菜单**等。应用使用的开发技术有`html`,`css`,`js`,`jquery`,`swiper`,`less`,`dedecms`,`svn`。

**汇国控股**微信小程序使用`web-view`组件内嵌移动端应用的方式开发完成，然后完成小程序上线的工作

## 自学、入门 WEB 前端开发（2017 年）

本阶段在互联网开放平台自学 web 开发技术，学习内容有

- html,html5
- css,css3
- javascript
- jquery
- Editplus/Hbuilder

# 开源项目和作品

## WEB 应用

> 访问地址：<https://github.com/konglingwen94>

- [vue-bytedanceJob](https://github.com/konglingwen94/vue-bytedanceJob)（Vue 仿写字节跳动招聘网站的单页面应用）**76 stars**, **17 forks**
- [vue-elm-seller](https://github.com/konglingwen94/vue-elm-seller)（高仿饿了么商家店铺的单页面应用）**18 stars** **, 12 forks**
- [vue-music](https://github.com/konglingwen94/vue-music)（爬取 QQ 数据的移动端音乐应用）**6 stars**, **2 fork**
- [vue-seller-admin](https://github.com/konglingwen94/vue-seller-admin)（Vue + ElementUI 搭建的管理后台系统）**6 stars**, **4 forks**
- [elm-seller-server](https://github.com/konglingwen94/elm-seller-server)（Koa+Mongodb 搭建的的外卖商家服务端项目）**3 stars**, **2 fork**
- [egg-nuxt-blog](https://github.com/konglingwen94/egg-nuxt-blog)（egg+nuxt 搭建的 WEB 全栈项目，以技术应用为主）**15 stars**, **2 forks**
- [vue-blog-admin](https://github.com/konglingwen94/vue-blog-admin)（vue+element-ui 开发的博客管理后台，可作为通用管理后台类项目参考二次开发）

## 封装的可复用插件

> 访问地址：<https://github.com/konglingwen94>

- [comment-message-editor](https://github.com/konglingwen94/comment-message-editor)（基于 vue 封装的留言信息编辑器组件）**12 stars**, **8 forks**, **73 used by**
- [message-tree](https://github.com/konglingwen94/message-tree)（基于 vue 封装的留言评论树组件）**8 stars**, **2 fork**, **7 used by**
- [good-swiper](https://github.com/konglingwen94/good-swiper)（基于 vue 封装的轮播图组件）**1 fork**
- [element-resize-event-polyfill](https://github.com/konglingwen94/element-resize-event-polyfill)（监听浏览器 DOM 元素原生 resize 事件的插件）**2 stars**
- [anydirectory](https://github.com/konglingwen94/anydirectory)（基于 Node.js 实现的资源托管服务器）**1 stars**

## 技术文章

> 访问地址： <https://juejin.cn/user/2154698523818328>

- [Koa+Mongodb 搭建商家店铺服务端项目总结](https://juejin.cn/post/6907803934031609863)
- [Vue+ElementUI 搭建商家店铺管理后台项目总结](https://juejin.cn/post/6906796790390095879/)
- [Vue 全新重构升级字节跳动招聘网站总结（下）](https://juejin.cn/post/6868884040029011975)
- [Vue 全新技术栈重构饿了么商家应用](https://juejin.cn/post/6844904202624303118)
- [Vue 全栈技术重构字节跳动招聘网站总结 ( 上 )](https://juejin.cn/post/6844904199289831432/)

# 综合能力

## 技能清单

- Web 开发：HTML/HTML5、CSS/CSS3、Javascript、DOM/BOM、ES6/7/Next、Ajax、JSON、NodeJs
- 前端框架、库、常用插件：Vue/Nuxt、JQuery、Axios、Lodash
- 前端工具：Webpack、Npm、Less、Babel、Eslint
- Vue 相关：Element-ui、vue-router、vue-devtools、vuex、cube-ui/mint-ui、vue-cli、vuepress、
- NodeJs 类库、管理工具：Koa、Mongoose、Express、Egg、Node 生态常用模块
- 数据库、后端工具：MongoDB/MySQL、Postman、Linux 常用命令、SSH 常用命令
- 版本管理、仓库托管、文档和自动化部署工具：Git、Github、Markdown、Linux 服务器
- 开发工具和运行平台：VSCode/Sublime，Chrome/Safari、MacBook/Window

## 职业能力

- 精通`HTML`、`CSS`、`Javascript`技术并能灵活运用
- 精通`Vue.js`技术，掌握其运行机制，并能封装前端通用组件，对 Vue.js 的**设计思想**、**重要特性实现方式**有深入的理解和研究
- 掌握浏览器运行原理和`HTTP`协议的通信过程
- 对**面向对象**、**MVVM 架构**、**关注点分离**等编程思想有深入的理解和实践
- 对 web 技术标准和规范有深入的理解和体会
- 对 web 应用有一定的架构能力，能够操作、把控全栈项目开发流程的每个环节和持续集成工作
- 对前端工程化、组件化、模块化、前后端分离等开发模式有全面的认知及应用

- 对互联网产品的**界面设计**、**功能特点**等方面有独立的审美和体验
- 突出的学习能力和独立的逻辑思维能力
- 能够阅读英文技术文档

## 学习经历

自从事互联网行业工作以来，本人所掌握的知识和技术是通过自己不断的**学习**、**实践**、**积累**、**总结**这些过程后所得，其中在公司任职期间熟练掌握了团队项目开发的工作流程并积累了相关的经验。目前入住的互联网技术社区有 [Github](https://github.com/konglingwen94)、[掘金](https://juejin.cn/user/2154698523818328/)、[Segmentfault](https://segmentfault.com/u/konglingwen94)、 日常工作中解决问题常用的搜索网站有`Google`、`Baidu`、`Github`、[StackOverflow](https://stackoverflow.com/users/15162382/%E5%AD%94%E4%BB%A4%E6%96%87)等

## 自我评价

对 WEB 前端开发及其相关的技术拥有浓厚的兴趣和热情，在 web 开发领域有全面完整的技术和知识体系。平时能自我驱动的学习、钻研 web 技术，善于关注行业前沿技术并能逐步地学习。在日常的项目开发中，能够脱离第三方类库手写逻辑代码，并对项目的**可读性**、**可维护性**、**架构设计**、**代码书写规范**等方面有严格的自我要求。工作中在实现产品需求的同时善于思考多种技术解决方案，并能总结出高效优雅的方案积累、运用。

## 生活和爱好

电影、篮球、运动、新闻、互联网社区交流

## 致谢

感谢您花时间阅读我的简历，期待能有机会和您共事。
