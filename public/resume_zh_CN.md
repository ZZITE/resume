## 📧 联系方式

- 手机：+86 176 0607 5892
- 邮箱：zziteqaq@163.com
- 微信：linchengy1
- github：[https://github.com/ZZITE](https://github.com/ZZITE)

## 🧑‍💻 个人信息

- 姓名：林成艺
- 工作经验：5年
- 学历：本科

## 🛠 技能清单

- TypeScript / ReScript /  Rust
- React / Angular / Vue
- Recoil / Jotai / Redux / MobX
- Ramda / Lodash /  fp-ts
- pnpm / yarn / npm
- Git
- Jest / Enzyme / Testing Library

## 工作经历

### 杭州数建科技（2020.08-2023.01）前端小组长

#### mate-build 元筑

该工具实现了离线化的工程项目进度计划管理。软件分为`计划编制`、`物资管理`和`清单管理`三大模块，以量化、可视化的形式，让用户通过编制、填报、绘制等操作形式对工程行业的施工情况进行管理。软件基于`Local First`的思想，支持本地化编辑。

我在这个项目中作为`物资管理`模块的负责人，主要完成的工作有：

- 参与了软件整体的技术选型，以Electron、React作为主要的技术栈。使用Jotai配合RxDB本地存储来提升 Local First 的体验
- 设计了物资模块的整体数据结构，数据库表结构。封装提供了基于双向链表结构的一些基础操作方法来操作数据，用于实现如插入删除、复制粘贴、批量操作等功能，提升了团队的开发效率，减少了大量重复代码
- 需求分析和开发的进度把控，需要对每个迭代周期的任务做拆解分配。协助小组成员完成任务，做code review和功能验收
- 设计 UndoManager 用来管理状态历史，从而实现 undo redo 功能。它和状态管理能够有机结合，提供的 useUndoCallback 与 useAtomCallback 保持 100% 一致的 API，这使得使用者没有学习成本，能够快速应用到项目中
- 使用 Jotai 来管理全局状态，原子化更新 UI，减少组件不必要的 rerender，提升 App 性能
- 使用 framer-motion react-spring FLIP 等动效技术来提升用户体验
- 封装常用的 Hook 和 Component

#### 中钢集团图纸管理

从零搭建一个中钢集团内部使用的图纸类文件管理平台。功能涵盖图纸的上传、识别分类、签章审批、查阅等。

- TODO...

#### 北京城建工程管理平台

服务于北京城建机关及其下属项目的工程管理平台。主要功能涵盖：项目进度、人员、物料、日志、文件和报表管理。通过可视化技术展示各个模块总览概况。