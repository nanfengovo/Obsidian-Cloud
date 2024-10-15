---
created: 2024-10-15T08:54:49 (UTC +08:00)
tags: []
source: https://mp.weixin.qq.com/s/zzpotSFZ-1Rm8C5P57GctQ
author: 林三心不学挖掘机
---

# 如何自学成为一名 Vue3 大神？我有话要说！

> ## Excerpt
> 大家好，我是林三心，用最通俗易懂的话讲最难的知识点是我的座右铭，基础是进阶的前提是我的初心~

---
## 前言

大家好，我是林三心，用最通俗易懂的话讲最难的知识点是我的座右铭，基础是进阶的前提是我的初心~

今年以来已经有很多人来问我说想要深度学习 `Vue3`，应该怎么学呢？我的回答都是统一的：**Github 上搜 Vben-Admin**，跟着敲一遍就行了

![图片](https://mmbiz.qpic.cn/mmbiz_png/TZL4BdZpLdiaUT8FiaibmTbP7313eAibt9ssuyHLQ9DvdSQMYNdp7jtbXK6SSj9uqib32OiavqaiaHdKquK4B0XSMNEhA/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

## 为什么推荐 Vben-Admin

很多人问我为什么推荐 `Vben-Admin` ，我想说，我作为一个对比了无数个后台管理系统的过来人，`Vben-Admin`无论是`复杂度、封装性、API使用程度、完整性、技术栈版本` 这些维度上，遥遥领先其他后台管理系统

> 最近 Vben 发布了`5`版本了，之前都是`2`版本，`5` 版本的代码估计会写得比旧版本更好

![图片](https://mmbiz.qpic.cn/mmbiz_png/TZL4BdZpLdiaUT8FiaibmTbP7313eAibt9ssDib3vxtcpWHRW2L7XnOQsXtyUKVzPJlTU3vicA0B5xiaKDwBnofzw7eWA/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

## 能从 Vben-Admin 中学到啥？

> 仓库地址：https://github.com/vbenjs/vue-vben-admin

我列举几个从这个项目中能学到的知识：

-   **Eslint + Stylelint + husky + Prettier**，毫无疑问，项目规范四件套
    
-   **PNPM + Monorepo + Turborepo**，毫无疑问，现今多项目管理的最方案
    
-   **项目换肤 + 语言国际化**，学学人家是怎么做的
    
-   **Vue3 + **Typescript**  深度使用**，基本使用了大部分的 Vue3 API
    
-   **组件封装 + Hooks封装 + 工具函数封装**，虽然复杂，但是能学到很多东西
    
-   **权限管理**，可以说是这个项目比较复杂的一个环节了
    
-   **Vite 插件的编写**，这也是工程化的一部分哦
    
-   **Nestjs 的基本使用**，可以说是现在最火的 Nodejs 框架了
    
-   **编写单元测试**，确保项目健壮性，这是一个加分项
    
-   **多组件库实现**，Vben5 提供了多种组件库实现，甚至还有 Shadcn-UI
    

![图片](https://mmbiz.qpic.cn/mmbiz_png/TZL4BdZpLdiaUT8FiaibmTbP7313eAibt9ssaQia1h54WUcYsBN6oUNpwohefLzIX1fm6h4SPXjAzrq0nFvx3S0ygVQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

## 光看肯定是不行的啦！

首先我说我的看法，我认为光看，除非你很有天赋，不然你真的很难去领悟到代码的精髓，所以我都是推荐从 0 到 1 敲一遍，这是最稳妥的方式，并且可以锻炼自己的自律性，在这个过程中可能你会遇到挫折，但是当你解决了这些问题之后，你会有前所未有的成就感、自信~

接着就有人问我了，跟着敲一遍，应该从哪敲呢？我就分享一下我的经验吧，以下是顺序：

-   1、简单搭建项目，`PNPM + Monorepo + Eslint + Stylelint + husky + Prettier`
    
-   2、先把项目一些通用的、无关页面的东西先封装了，比如 `axios请求封装、国际化封装、换肤的样式`
    
-   3、`封装简单的路由`，比如我一开始只写了一个登录页的路由
    
-   4、`实现登录页`，你会发现你认为简简单单的一个登录页，其实要花你一两个星期的时间，因为牵扯到太多的项目基础搭，`在这个过程中你能学到很多你从来没见过的 Vue3 API + Typescript！！！`
    
-   5、`研究怎么启动项目`，启动项目可不简单，需要写一些`Vite插件、Vite配置`
    
-   6、实现完登录页，估计`国际化、Pinia、换肤、axios请求、常用Hooks、项目搭建`这些都基本完成了
    
-   7、继续完成其他页面，研究实现过程
    

## 好难啊，有没有捷径啊？

没有，除非你很有天赋，不然老老实实学习，如果你最后能实现 Vben 一半的功能页面，你都算是很有毅力了，到时你完全可以把这些东西写到你的简历里，换个名字，这不就是你的项目了吗？

![图片](https://mmbiz.qpic.cn/mmbiz_png/TZL4BdZpLdiaUT8FiaibmTbP7313eAibt9ssgR5HEJ2QWLbkfiaqqG5tkCDe1Z5GVdYBJvHrRE6WpC9I7MKwbr85gkw/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

  

所以，加油吧！！！

## 结语

我是林三心，一个待过**小型toG型外包公司、大型外包公司、小公司、潜力型创业公司、大公司**的作死型前端选手，感谢您的阅读~
