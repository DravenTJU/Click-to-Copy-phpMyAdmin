# phpMyAdmin一键复制数据表值

这是一个浏览器用户脚本，用于在phpMyAdmin中为数据表单元格添加一键复制功能。

## 功能特点

- 在每个数据表单元格上悬停时显示复制按钮
- 点击即可复制单元格内容到剪贴板
- 支持所有phpMyAdmin版本
- 复制成功时有视觉反馈
- 自动检测数据表切换，无需刷新页面

## 安装方法

1. 首先安装浏览器扩展：
   - Chrome用户：安装[Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
   - Firefox用户：安装[Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/)

2. 点击[这里](./phpmyadmin-click-to-copy.user.js)安装用户脚本

## 使用方法

1. 安装脚本后访问phpMyAdmin
2. 在浏览数据表时，将鼠标悬停在任意单元格上
3. 点击出现的复制按钮即可复制内容

## 更新日志

### v1.1
- 修复切换数据表后复制功能失效的问题
- 添加自动检测数据表变化功能
- 优化按钮初始化逻辑，避免重复
- 改进代码结构和注释

### v1.0
- 初始版本发布
- 实现基础的一键复制功能
- 添加复制成功动画效果

## 贡献

欢迎提交Issue和Pull Request来改进这个脚本。

## 许可证

GPL-2.0 license - 查看 [LICENSE](./LICENSE) 文件了解详情 