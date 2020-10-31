# github-collaboration-tutorials
Github协作教程，本项目帮助你提前熟悉在线协作教程，你可以直接参与本项目的协作，防止在工作过程中因为你的误操作导致大项目的严重损失哦😉！

## 0. 必要知识

在参与协作之前请熟悉基础的git操作。关于git教程更多内容可参考[Git教程](https://www.liaoxuefeng.com/wiki/896043488029600)。

## 1. 协作规范

提供以下两种方式，每个协作者可在当前项目下创建目录进行协作：

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

指的是pr规范，每个人以pr形式合入master，合入过程中，管理员会做code review和文档、注视等相关规范进行审查，如果不通过，驳回，否则合入。

每人开发可以自开分支，分支规范如下：

名字/功能

例如：subranium分支完成了拉取数据功能。

```
subranium/getData
```

最后，要经常更新master分支，不要让自己分支存活太久。

## 推荐资源

[1] [Gitkraken](https://www.gitkraken.com/)

[2] [Github团队协作教程（Gitkraken版）](https://www.cnblogs.com/thousfeet/p/7840932.html)

[3] [面向小白详细介绍Git和GitKraken的使用（UP主：wkgl广隶）](https://www.bilibili.com/video/BV1bK4y1t7CD?from=search&amp;seid=15547533998579929746 )