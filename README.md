# 个人信息

- **李浩宇**/男/1996 
- 🏫大专/武汉软件工程职业学院/计算机网络技术
- ⏱️工作年限：4.5年
- 💼 期望职位：**前端工程师**
- 💴 期望薪资：14k
- 🏙 期望城市：武汉

# 联系方式

- 📱手机：17635086965
- 📫Email：lhy0825@outlook.com
- 🌐QQ/微信号：1275416171 微信同手机号

# 技能清单

- 前端基础：HTML/CSS/JavaScript/
- 前端框架：Vue2/Vue3
- 跨端： uni-app
- 小程序： 原生/mpvue/wepy/云开发
- 工程化：TypeScript/Vite/Webpack
- node： express/egg
- 数据库：mongoDB
- 版本管理： git
- 其他：浏览器插件、puppetter、腾讯IM\腾讯云直播开发经验
- 运维：基础liunx命令/pm2/阿里云/宝塔面板

# 工作经历

- 武汉优赛时代科技有限公司  | 2022.6 ~ 2022.12 |  前端组长
- 武汉然诺管理咨询有限公司  | 2019.7 ~ 2022.05 |  前端开发/node开发 
- 福建茶米电子商务有限公司  | 2018.5 ~ 2019.03 |  前端开发

# 教育背景

- 武汉软件工程职业学院 | 2015.9月 ~ 2018.6 | 计算机网络技术

# 项目经历

### 优赛App（app store可下载）uni-app

- 项目简介

  民间足球社区平台app。依托基于**腾讯IM**的社交聊天模块，信息发布模块，解决用户**无队、无处、无赛**的问题。更有**赛程、朋友圈、杯赛、个人虚拟形象**等丰富功能，使用户畅想足球乐趣。

- 工作内容（项目难点）

  - 参与项目需求分析会议，共同制定项目原型；搭建项目基本开发框架；还原设计稿；解决疑难杂症；打包进行测试和发布到应用商店。
  - 因业务特殊需求，每个用户的队伍群需默认置顶，根据用户个人信息中的队伍列表计算生成当前会话列表
  - 使用textarea实现聊天**输入框换行且自动撑开高度**的效果
  - 使用change事件回调中的current参数，**记录当前光标位置**，在**输入emoji表情**的时候，在当前光标位置**插入emoji文本**
  - 使用七牛云**图片瘦身和基本处理**，**减小git表情缩略图尺寸**，提高加载速度，解决切换表情列表时的卡顿问题
  - **封装自定义nvue导航栏**，既实现了丰富的导航栏效果，相比webview自定义导航栏又提高了性能，且支持**自定义事件**
  - 因一些特殊页面情况，自己写了一个**indexed-list（索引列表）组件**，实现右侧索引列表、描点定位效果（支持滑动）、支持全屏、非全屏页面
  - 封装**上拉加载、下拉刷新hook**，提高列表页开发效率
  - 使用createIntersectionObserver的api，实现朋友圈页面视频资源**进入页面中部自动播放、离开显示区域停止播放**
  - ...uniapp问题、特殊需求问题太多了...

### 越位私人运动俱乐部（微信小程序） uni-app

- 项目简介

  会员制足球俱乐部，提供线下足球课程、会员内部比赛、线下会员聚会等活动服务。小程序可进行用户注册、会员购买、参与活动、美女助教查看、查看历史活动照片墙等。

- 工作内容

  - 深度理解使用场景，提出自己的看法，分享类似应用设计风格，**并使上级成功采取了意见**。
    使用uniapp进行小程序快速搭建和开发，**一周时间从开发到上线**。

  - 媒体统一上传在七牛云，**封装七牛云上传方法**，直接返回七牛云完整链接。
  - 使用七牛云的图片瘦身、图片基本处理等功能，**封装图片组件**，实现多图场景下的快速加载、等比缩放、固顶宽度等比缩放（瀑布流），解决照片墙卡顿、白屏等问题，**实现正常网络下照片墙1s内加载**
  - 管理后台支持富文本创建活动详情，使运营人员更加方便的创建、编辑活动，使用display：block；解决图片下方间隙问题。


### 优赛足球（微信小程序） uni-app

- 项目简介

  在优赛app背景下产生的用于**App推广**的衍生小程序，提供了基于微信群**创建赛程、参与赛程、赛后评价**等核心app功能，主要作用是**通过微信来扩散App品牌**，使用户低门槛的体验一些app功能，点击其中的下载app按钮会发送包含下载短链的短信。

### 然诺快投（后台管理端+企业管理端+微信小程序）

- 项目简介：
  然诺招聘会运营系统，为招聘企业、人力资源机构、求职者提供一个实现多方需求的平台。主要场景为人力资源机构或企业举办线下或线上招聘会，企业参会并发布职位，求职者通过小程序投递选择合适的职位进行简历投递，招聘方收取简历，选择合适的人才简历进行面试等操作完成招聘需求。
- 技术栈：
  前端：Vue2.x + vue-router + vuex + ElementUI + axios + echarts等。
  后端：eggjs、mongoDB
- 该项目中分为以下子项目：

>1. 然诺快投后台：用于人力资源机构使用。
>   主要模块有运营概况、招聘会管理、企业库、职位库、人才库、直播管理、系统管理（用户、角色权限、字典、平台配置），连接ATS(本企业另一个项目)等。使用平台权限配置进行版本划分。
>2. 然诺快投小程序：用于求职者使用。
>   技术栈：mpvue+flyapi，之后使用原生小程序写法重构；
>   主要模块有招聘会（查看、签到）、参会企业（vip企业、所有企业）、职位（筛选、投递、海报）、简历(填写、查看、上传文件)、投递记录、根据简历和投递记录推荐职位、职业测评、企业报名参会等功能
>   版本分基础版、高级版、雇主品牌版、租赁版四个版本。
>3. 然诺快投企业后台：用于招聘企业方使用。
>   主要模块有企业注册\登录\认证，职位管理、参会管理、候选人管理、人才库、消息中心等。
>4. 快投部署工具。
>   主要功能有项目管理、系统初始化、权限表管理等
>   方便项目快速部署和版本更新

- 工作内容：
  1．分析和整理需求，负责整个前端项目开发和维护，参与维护后端项目，后期独自负责整个项目的前后端开发、运维部署。
  2．使用vue-cli从0到1完成前端管理系统项目搭建，并沉淀出基本业务组件库。
  3．使用cdn加载外部依赖、资源压缩、图片懒加载等方案提高前端性能，首次加载时间缩短至1s内，优化用户体验。
  4．大文件分片上传提高速度。
  5．超长表单页面性能优化等。
  6．后端托管前端页面并配置路由，解决vue-cli打包的生产环境404的问题。

- 结果：
  1.完成整个项目开发的同时进行维护。为武汉多家人力资源机构、武汉理工大学、武汉科技大学、江汉大学等高校、近千家企业成功举办多次招聘活动。
  2.为湖北华夏、宁波北岸（江北区人社局）等客户部署和使用。
  3.在开发中沉淀出后台管理模板项目，其中包含多个常用业务、开发组件，大大提高了开发效率。


### 然诺ATS招聘流程系统 （后台管理+求职小程序+招聘官小程序+浏览器简历采集插件）

- 项目简介：
  企业招聘流程管理系统，包括首页概况、组织、职位、面试、人才库、职位、数据统计、系统管理等几个主要模块，具备管理后台、企业小程序、招聘官小程序，基于Express、Mongodb、Vue、Element UI、Echarts实现，支持多渠道简历采集，简历解析入库、人才推荐、招聘协同等功能，能满足企业的招聘数字化需求。
- 该项目包括以下子项目：

>1. ATS招聘系统：
>   技术栈
>     前端：Vue2.x + vue-router + vuex + ElementUI + axios + echarts等。
>     后端：express、mongoose、pm2、puppeteer等
>     主要模块有首页概况（数据概览、周面试安排、招聘动态、员工相关、渠道盒子）、面试流程、职位管理、组织管理、员工管理、数据统计（渠道效果、招聘台账）、系统管理（用户、平台配置），连接快投配置(负责项目1)等。
>2. 招聘官小程序：
>   技术栈： wepy1.x
>     人才库（人才详情、储备人才）、面试流程（多个流程状态以及流程操作、简历查看）我的（招聘官认证、组织管理、职位管理、数据中心、人才储备）
>3. 求职者小程序：
>   技术栈：mpvue
>     企业专属官方招聘小程序，关于我们（企业介绍）、加入我们（在招职位、职位列表以及详情）、我的（应聘等级、文件简历上传）
>4. 浏览器简历采集插件：
>   招聘人员可在登录智联、猎聘、51job等网站后进行采集简历信息并录入ATS系统

- 工作内容：
  1．参与ATS产品的设计、实现，负责项目进度与计划、前/后端服务的研发，制定和推进项目进度，以及服务器的部署、运维管理工作。
  2．前端生成简历pdf文件实现在线简历下载，代替后端生成，提高下载速度。
  3．使用定时任务实现面试提前24小时发送邮件提醒候选人和招聘官。
- 结果
  已部署武汉凯晨、武汉天然气、湖北克拉弗特等多个客户，并在内部招聘团队中使用。


### 招聘信息（职位、招聘会）采集工具

- 项目简介：
  在各大主流招聘网站根据职位关键词采集职位信息以及计算和统计职位数据，并可导出结果excel。
  前端技术栈：Vue及其生态、websoket、echarts
  后端技术栈:  express、puppeteer、cherrio、axios、xlsx.js
- 工作内容：
  1.完成整个项目的开发（前后端）
  2.使用websoket实现实时采集进度查看
  3.根据业务需求，制定统计算法，实现不同渠道不同单位的薪资、工作地点、学历、工作年限等统计数据整合
- 结果
  为内部招聘团队提供职位数据支持，提高职位调研效率、准确度。
