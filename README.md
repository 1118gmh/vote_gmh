### vote_gmh

本项目是一个前后端分离的投票的项目，前端使用了html、css、js、zepto，后台使用express以及一些中间件搭建而成。

前端实现的页面：

- 首页
- 注册页
- 登录页
- 详情页
- 参赛页

后台实现的接口：

- 获取参赛人员列表信息 [get]

  `URL:/getMatchList?limit=10&page=1&search=xxx`

- 投票操作 [get]

  `/vote?participantId=12`

- 检测是否已经投递过该人 [get]

  `/checkUser?checkId=0`

- 获取我投过的人员 [get]

  `/getMyVote`

- 获取投票过我的人员 [get]

  `/getVoteMy`

- 注册新用户 [post]

  `/register`

- 用户登录 [post]

  `/login`

- 参与比赛 [post]

  `/match`

- 退出登录 [get]

  `/exitLogin`

- ...

主要实现的功能：

- 用户的注册功能
- 用户的登录功能
- 用户的投票功能
- 用户的搜索功能
- 用户的参赛功能
- ...

项目的部署：

```
将项目部署到本地服务的8686端口
	node server.js
```

预览(preview)

![](.\preview\首页.png)

