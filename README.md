# 🎉 v1 版本开发完成啦！2020-10-28 21:32

> 断断续续已经七八个月过去啦，期间拿起、放下，最终还是趁空闲时间，把该项目第一阶段开发完成了，v1版本不久完美，但求能用😄！！

> ❕ 下一阶段主要是整理代码，优化代码逻辑，后端：全系统增加`uuid`作为用户唯一标识！前端：代码解耦，封装，优化！新功能暂时就不开发了～

## 分支介绍
> 本分支是 `react-im` 的客户端 `v1` 版本，对接了 `react-im server` 端，真正可用的前后端分离的 `IM` 应用！

> 🎉 后端代码：[最初版服务端源码](https://github.com/lmsail/react-im-server) | [react-im server v1 服务端](https://github.com/lmsail/react-im-server/tree/v1)

> 🔥 我的小站：[M先生 - 每一次的努力都是看得见的进步！](http://www.lmsail.com)

## 目前功能

- [x] 登录 / 注册
- [x] socket 连接初始化（用户信息，历史会话列表，通讯录列表）
- [x] 用户信息的更改（昵称，地区，手机号码，个性签名）
- [x] 好友备注 / 用户搜索 / 添加好友 / 好友验证等

> 更多功能也正在来的路上～～ 

## 下载安装

```
git clone -b v1 https://github.com/lmsail/react-im.git  
cd react-im
yarn install
yarn start
```