# github-collaboration-tutorials
Github协作教程，本项目帮助你提前熟悉在线协作教程，你可以直接参与本项目的协作，防止在工作过程中因为你的误操作导致大项目的严重损失哦😉！

## 0. 必要知识

在参与协作之前请熟悉基础的git操作。关于git教程更多内容可参考[Git教程](https://www.liaoxuefeng.com/wiki/896043488029600)/[learnGitBranching](https://learngitbranching.js.org/?locale=zh_CN)。

## 1. 协作规范

提供以下两种方式，每个协作者可在当前项目下创建自己的目录进行协作：

- 提交issue请求将你的账号添加为协作者，直接操作本项目
- fork该项目后提交pull request

### commit规范

提交规范如下：

- 常规提交

```
git commit -m "normal: 功能 --creator=名字"
```

注意功能与冒号有个空格，功能与`--`有个空格，提交的时候更改功能为自己的提交内容即可，名字替换为自己名字。

例如：subranium增加了登录模块

```
git commit -m "normal: add login in --creator=subranium"
```

- bug修复

```
git commit -m "bugfix: 功能 --creator=名字"
```

将上述的normal替换为bugfix即可。

例如：subranium修复了图片不展示问题

```
git commit -m "bugfix: pic show --creator=subranium"
```

### pr规范

指的是pr规范，每个人以pr形式合入master，合入过程中，管理员会做code review和文档、注释等相关规范进行审查，如果不通过，驳回，否则合入。

每人开发可以自开分支，分支规范如下：

名字/功能

例如：subranium分支完成了拉取数据功能。

```
subranium/getData
```

最后，要经常更新master分支，不要让自己分支存活太久。

## 推荐资源

[1] [GitHub基本概念理解（微信公众号：知识沉淀部落）](https://mp.weixin.qq.com/s?__biz=MzAwODUyMjk1NQ==&mid=2247483661&idx=1&sn=7ffe3e4685e1ac3e2310a5c6f11f6730&chksm=9b6cdca9ac1b55bfdfd721e082b323bedc72e4ea052b3a9e1291eee8303ca78dbf9abe6d1f4d&scene=126&sessionid=1596346457&key=ebb412db45555e1dc815665ca63509ec822a4fa5e02496552e9831c278df66b8a3fe94fadd8d2deace387921f0f7e091999d05dc8f7cf9f89b72235b31c25ca3c19c40ea89f75be98e3531b7b3d0678b86cbe43e771b6546b3fb38e2434691be7a71eb05e8b4d8c5060cf202c6b18ba61d743e5995f393807e240dd15613eef0&ascene=1&uin=MTcyNTMxODQzOA%3D%3D&devicetype=Windows+10+x64&version=6300002f&lang=zh_CN&exportkey=AxRqDshfuvTyWnnLz4QeQhk%3D&pass_ticket=fifDZE3OhWi02qbAUsFNOGkF%2BW0W5Tdb39TbhqFaJsZAcgJ7R5MfebbmfE4ml%2F1E&wx_header=0)

[2] [Gitkraken](https://www.gitkraken.com/)

[3] [Github团队协作教程（Gitkraken版）](https://www.cnblogs.com/thousfeet/p/7840932.html)

[4] [面向小白详细介绍Git和GitKraken的使用（UP主：wkgl广隶）](https://www.bilibili.com/video/BV1bK4y1t7CD?from=search&amp;seid=15547533998579929746 )

[5] [How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/)

modify:2021.04.13
nmbmnbj
xxx
rwq3tw4ye5ur6
\oidursyerdtu\
'oiursyhxfcjgvkhhii
guffxjcgkhvlughioj
puyfiufxdhfjghuih'o
piipoguyficfxjgkhu;ih'o
pi[igpofi]