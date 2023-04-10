# 直播粉丝数据统计

## 项目介绍

本项目是一款专门为直播平台用户设计的粉丝数据统计工具。它可以帮助用户快速查看直播间粉丝数据，包括等级、停留时间、抖音id、当前排名等信息，以便更好地进行粉丝运营。

## 功能介绍

- 查看直播间粉丝数据，包括等级、停留时间、抖音id、当前排名等信息
- 统计粉丝在直播间的停留时长
- 分析粉丝行为，如互动情况、送礼情况等
- 提供多种统计报表，方便用户查看直播数据

## 效果展示

| 粉丝ID  | 等级 | 停留时间 | 当前排名 |
| ------- | --- | -------- | -------- |
| 123456  | 3   | 20分钟  | 1        |
| 654321  | 1   | 5分钟   | 2        |


[![ppq39dP.md.png](https://s1.ax1x.com/2023/04/10/ppq39dP.md.png)](https://imgse.com/i/ppq39dP)
[![ppq3CIf.md.png](https://s1.ax1x.com/2023/04/10/ppq3CIf.md.png)](https://imgse.com/i/ppq3CIf)
[![ppq3pZt.md.png](https://s1.ax1x.com/2023/04/10/ppq3pZt.md.png)](https://imgse.com/i/ppq3pZt)
[![ppq1zqI.md.png](https://s1.ax1x.com/2023/04/10/ppq1zqI.md.png)](https://imgse.com/i/ppq1zqI)


## 功能限制

| 功能              | 限制                                |
| ----------------- | ----------------------------------- |
| 查看抖音粉丝      | 支持                             |
| 如何获取粉丝数据 | 需要授权直播平台账号                |
| 直播间粉丝详细信息 | 部分信息需要授权直播平台账号        |

## 技术栈

- 前端：Vue.js、Element UI、ECharts
- 后端：Spring Boot、MyBatis、Redis
- 数据库：MySQL、MongoDB
- 直播平台API、非api数据

## 技术实现方案

前端使用 Vue.js 框架，通过 Element UI 组件库构建用户界面，使用 ECharts 组件实现统计图表展示。
后端使用 Spring Boot 框架，采用 RESTful API 风格，与前端通过 HTTP 协议交互，使用 MyBatis 框架操作MySQL数据库和Redis缓存，使用MongoDB存储粉丝行为数据。

## 联系方式

QQ: 80258153

## 免责声明

本项目仅为直播平台用户提供粉丝数据统计服务，不承担任何法律责任。使用本项目时，请遵守直播平台的相关规定，不得进行任何违法行为。
