## 📧 联系方式

- 手机：+86 176 0607 5892
- 邮箱：zziteqaq@163.com
- 微信：linchengy1
- github：[https://github.com/ZZITE](https://github.com/ZZITE)

## 🧑‍💻 个人信息

- 姓名：林成艺
- 工作经验：5 年+
- 学历：全日制本科
- 专业：电子信息工程

## 🛠 技能清单

- HTML / CSS / JavaScript / TypeScript / ReScript
- React / Angular / Vue
- Recoil / Jotai / Redux
- Ramda / Lodash / fp-ts
- Tailwind CSS / CSS-in-JS / Sass
- pnpm / yarn / npm
- GraphQL / RESTful
- Git
- Jest / Testing Library

## 🌈 工作经历

- ### 杭州数建科技（2020.08-2023.01）前端小组长

  #### mate-build 元筑

  该工具实现了离线化的工程项目进度计划管理。软件分为 **计划编制**、**物资管理** 和 **清单管理** 三大模块，以量化、可视化的形式，让用户通过编制、填报、绘制等操作形式对工程行业的施工情况进行管理。软件基于 **Local First** 的思想，支持本地化编辑。（如果您在线访问该简历，这里提供一张[物资模块主要界面截图](https://imgloc.com/i/xtBxN)作为参考）

  我在这个项目中作为 **物资管理** 模块的负责人，主要完成的工作有：

  - 参与了软件整体的技术选型，以`Electron`、`React`作为主要的技术栈。使用`Jotai` `react-query` 配合 `RxDB` 本地存储来提升 **Local First** 的体验
  - 针对本项目所用到技术栈的分享，团队成员的 onboarding 测试
  - 设计了物资模块的基础数据结构，数据库表结构。封装提供了基于 **双向链表** 结构的一些基础操作方法来操作数据，用于快速实现如插入删除、复制粘贴、批量操作等功能，提升了团队的 **开发效率**，减少了大量 **重复代码**
  - 需求分析和开发的进度把控，需要对每个迭代周期的任务做拆解分配。协助小组成员完成任务，做 **code review** 和 **功能验收**
  - 编写完成物资模块主要的业务代码
  - 设计 `UndoManager` 用来管理工具的操作状态历史，从而实现 `undo` `redo` 功能。它和状态管理能够有机结合，提供的 `useUndoCallback` 与 `useAtomCallback` 保持 **100%** 一致的 API，这使得使用者没有学习成本，能够**快速应用**到项目中
  - 使用 `Jotai` 来管理全局状态，原子化更新 UI，减少组件不必要的 re-render，**提升应用性能**
  - 使用 `framer-motion` `react-spring` `FLIP` 等动效技术来**提升用户体验**
  - 封装常用的 Hook 和 Component

  #### 中钢集团图纸管理

  作为该项目的主要负责人，从零搭建一个中钢集团内部使用的图纸类文件管理平台。功能涵盖中钢集团内部图纸的上传、识别分类、审批签章、查阅归档等。已交付部署上线使用。

  - 使用 `vite` 构建项目
  - 使用 `GraphQL codegen` 搭配 `react-query` ，在开发过程中仅需编写`.graphql`文件，即可通过脚本自动生成所有带类型的`Queries`和`Mutations` `hooks`，极大程度的减少了数据传输层面的代码量，提升了开发体验和效率
  - UI 框架上选用了 `chakra-ui` ，在快速构建 UI 的同时，更加易于自定义组件样式
  - 使用 `recoil` 作为全局状态管理
  - 使用 `framer-motion` 构建动画交互，提升用户使用体验

  #### 北京城建工程管理平台

  服务于北京城建机关及其下属项目部的工程管理平台。主要功能涵盖：项目进度、人员资料、物料、日志、文件和报表管理等。通过可视化技术展示各个模块总览概况。
  主要涉及的技术栈有：`React` `GraphQL` `UmiJS` `Ant Design` `Ant Design Pro` `styled-components` `bizcharts` `Lodash` 等。

  - 负责了平台多个模块的业务开发
  - 负责内部组件库的开发
  - 对原有代码的重构，**性能优化**等

- ### 厦门多快好省科技有限公司 （2018.03-2020.05）前端开发

  #### 基金决策宝

  服务于正规挂牌机构的基金交易平台。功能包含基金的开户买卖，选基推荐，智能诊断，操作分析等。
  可使用移动端设备访问网页[https://www.dkhs.com/](https://www.dkhs.com/)查看项目。

  - 项目主要使用早期的 `AngularJS` 进行开发。我负责了该项目 web 端的正常周期迭代，以及在移动端 APP 中一些涉及各类活动，资讯，广播等 webview 内容的开发
  - 使用`D3.js`封装绘制如**K 线图**、**收益走势图**等图表
  - 负责开发了基金工具中，现金宝、秒懂基金、智能助手、基金 PK、风险测评等主要功能
  - 重构了量化选基模块。基于 `AST` 数据结构，重新设计了高级表单复杂筛选，无需定制开发各种筛选功能，减少了原有的 **大量冗余代码**，提升了**开发效率**，也更利于后续的**功能扩展**

  #### 期货捕猎者

  **微信小程序**项目。期货的模拟盘，历史盘，实盘交易。期货交易的竞赛活动等。

- ### 厦门火马科技有限公司 （2017.07-2018.01）前端开发

  使用 `Vue` 生态构建的跨境电商商城网站

## ❤️ 参与过的开源项目

- [floating-ui](https://github.com/floating-ui/floating-ui)
- [AppFlowy](https://github.com/AppFlowy-IO/AppFlowy)

## 📖 阅读清单

- [x] _you don't know js_
- [x] _Head First Design Patterns_
- [x] _The Rust Programming Language_
- [ ] _The Cathedral & the Bazaar_
- [ ] _Clean Code: A Handbook of Agile Software Craftsmanship_
- [ ] _Algorithms_
