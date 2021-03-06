# 简介
本项目是某笔试的答卷，纯粹使用 React JS 实现了一个有一定交互性的侧栏。

# 验收说明
1. `git clone https://github.com/wenatuhs/react-exercise.git`
2. `cd` 到项目根目录下，使用浏览器打开 index.html（较新版本的 Chrome 和 Safari 上测试通过）
3. 在打开的页面上对功能进行逐一验收

# 任务时间分配
大概加起来总共 9 小时？

- 考虑开发方案用时 2 小时左右
	- 我之前较有经验的技术栈是 Meteor + React，所以最开始考虑直接加后端，集成真实数据库（mongo DB）完成项目，但后来觉得测试起来太麻烦，需要本地有 meteor 环境
	- 所以最后选择纯网页实现，测试极为简单，直接打开 html 文件即可
- 重新学习 React 1 小时左右
	- 之前看过 Thinking in React，再加上项目经验，对 React 构造网页 app 的方式其实比较熟，但是之前是把 React 完全当前端框架使用，没怎么用到其 `setState()` 的 reactivity 特性，所以还是仔细学习了 React 的 tutorial
- 调试开发环境 1 小时左右
	- 采用 BBEdit 进行开发
		- 前段时间刚买，正好趁这个机会学习一个
		- 其实这个选择很蛋疼，用 Webstorm 显然更快，but whatever
	- 使用 ES6 语法
		- 没那么多时间配置 babel，就直接把 jsx 代码全写 html 里了
- 开发加起来 5 小时左右
	- 中间断断续续，具体请参考 .git
	- 基本功能初步建立非常快，可能 1 小时不到吧
	- 逆向数据流卡住了一下，可能耗了 1 小时
	- 最后的 checkbox css 自定义耗了些时间，1 小时吧
	- 具体开发时间节点请参考 .git

# TODOS
- 实现侧边栏的按部门展开和收起

# Known issues
暂无
