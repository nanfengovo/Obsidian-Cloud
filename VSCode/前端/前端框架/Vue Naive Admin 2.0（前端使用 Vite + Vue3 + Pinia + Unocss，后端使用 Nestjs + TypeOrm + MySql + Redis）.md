---
created: 2024-10-10T18:00:37 (UTC +08:00)
tags: []
source: https://mp.weixin.qq.com/s/EI-CPs7UGlzmRveWFfEnIQ
author: 
---

# 一个极致轻量的 Vue3 后台管理，继 1.2k Star

> ## Excerpt
> Vue Naive Admin 从2022年2月开始开源，其简单易上手的特性广受好评，当时发过一篇推文，感兴趣的朋友可以重温一下，Vite+Vue3+Unocss+NaiveUI+Pinia搭建一套优雅的后台管理模板，真香 - 掘金 (juejin.cn)

---
Vue Naive Admin 从2022年2月开始开源，其简单易上手的特性广受好评，当时发过一篇推文，感兴趣的朋友可以重温一下，Vite+Vue3+Unocss+NaiveUI+Pinia搭建一套优雅的后台管理模板，真香 - 掘金 (juejin.cn)

## 回顾开源

Vue Naive Admin 开源一年零十个月，收获了 1.2k Star, gitee 上也有 260+ 的 Star，建了两个微信交流群，总人数 500+，成绩不算优秀，但贵在坚持。

## Vue Naive Admin 2.0 是什么？

源码: vue-naive-admin (github.com)

体验: admin.isme.top

### 简介

Vue Naive Admin 2.0 是一款极简风格的后台管理模板，包含前后端解决方案，前端使用 Vite + Vue3 + Pinia + Unocss，后端使用 Nestjs + TypeOrm + MySql + Redis，简单易用，赏心悦目，历经十几次重构和细节打磨，诚意满满！！

### 设计理念

Vue Naive Admin 2022年2月开始开源，2023年 12月 发布 2.0 版本，从 1.0 到现在的 2.0，一直秉持着`简单即正义`的理念，旨在帮助中小企业、在校大学生及个人开发者快速上手开发后台管理项目，为了降低使用者的学习成本，没有使用当前看似“主流”的 TypeScript（前端），而是使用 `JavaScript`, 这也使得 **Vue Naive Admin** 成为了市面上少有的 `使用 JavaScript 的 Vue3 后台管理模板`，而且还算优秀，得到了大量朋友的认可和喜爱。

这里就不讨论为什么使用 `JavaScript` 而不使用 `TypeScript`了，各自的优缺点大家都清楚，需要 `TypeScript` 版本的可以绕道，使用 `TypeScript` 的后台管理模板现在多如牛毛，请自行在 github 搜索

### 特性

-   🆒 使用 **Vue3** 主流最新技术栈: `Vite + Vue3 + Pinia`
    
-   🍇 使用 **原子CSS**框架: `Unocss`，优雅、轻量、易用
    
-   🍍 集成 `Pinia` 状态管理，支持状态持久化
    
-   🤹 使用主流的 `iconify + unocss` 图标方案，支持自定义图标，支持动态渲染
    
-   🎨 使用 Naive UI，`极致简洁的代码风格和清爽的页面设计`，审美在线，主题轻松定制
    
-   👏 先进且易于理解的文件结构设计，多个模块之间**零耦合**，单个业务模块删除不影响其他模块
    
-   🚀 `扁平化路由`设计，每一个组件都可以是一个页面，告别多级路由 `KeepAlive` 难实现问题
    
-   🍒 `基于权限动态生成路由`，无需额外定义路由，`403和404页面可区分`，而不是无权限也跳404
    
-   🔐 基于Redis集成 `无感刷新`，用户登录态可控，安全与体验缺一不可
    
-   ✨ 基于 Naive UI 封装 `message` 全局工具方法，支持批量提醒，支持跨页面单例模式
    
-   ⚡️ 基于 Naive UI 封装常用的业务组件，包含`Page` 组件、`CRUD` 表格组件及 `Modal`组件等，简单易用，减少大量重复性工作
    

### 极致的性能

Vue Naive Admin 2.0 极致轻量，性能也很优秀

![图片](https://mmbiz.qpic.cn/sz_mmbiz_jpg/T0zd7NEbcXSm87ibqflhjFq5E0L6V9VfibuTTaiaMFyVqHpotUMj1vkzv3vvtc0G4NmTFBJeglQe2DZYg4XODTa6Q/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)![图片](https://mmbiz.qpic.cn/sz_mmbiz_jpg/T0zd7NEbcXSm87ibqflhjFq5E0L6V9Vfib8OeO6icsvDOgeFneM4iakpVnc7rycm3ic0NTsjWy55vRyKGFuqqcqA9iaA/640?wx_fmt=other&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

### 提供对应的后端服务：Isme Nest Serve

Vue Naive Admin 2.0 提供一套后端代码，技术栈使用 Nestjs + TypeOrm + MySql，内置 JWT、RABC及模板所需的一些基础接口。

_后续可能会提供 Java 版和 Go 版的，但由于精力有限，欢迎感兴趣的大佬基于前端提供对接好的后端项目，当然，并不局限于 Java 和 Go，已对接的后端项目会展示到仓库的 README 和 官方文档中_

-   源码-github: isme-nest-serve | github
    
-   源码-gitee: isme-nest-serve | gitee
    

## 为什么会有 2.0 版本?

因为2.0 是基于 1.0 风格从 0 到 1 重新设计的，虽然看着很像，但是代码结构差别很大，在 1.0 版本基础上迭代不合适。另外，2.0 版本是全栈版本，提供了对应后端服务，把后端服务搭建起来就可以直接上手开发，这跟 1.0 版本也是有着根本的不同。

可以这样说，2.0 版本既有 1.0 版本的沉淀， 也在 1.0 版本上做了根本性的突破

## 2.0 和 1.0 区别

-   2.0 是基于 1.0 风格从 0 到 1 重新设计的，虽然看着很像，但是代码结构差别很大。
    
-   1.0 只提供前端，后端使用 Mock 模拟的，而 2.0 是全栈版，提供真实的后端接口。
    
-   2.0 虽然版本高于 1.0，但复杂度却远低于 1.0，虽然 1.0 也很简单。
    
-   2.0 的灵活度远高于 1.0，得益于 `扁平化路由` 的设计，任何一个 `.vue` 文件都可以是一个页面，并且可以放到任意菜单下，甚至你还可以为每个页面单独定制一个 layout。
    

体验1.0 | template.isme.top

体验2.0 | admin.isme.top

## 版权说明

本项目使用 `MIT协议`，默认授权给任何人，被授权人可免费地无限制的使用、复制、修改、合并、发布、发行、再许可、售卖本软件拷贝、并有权向被供应人授予同等的权利，但必须满足以下条件:

-   复制、修改和发行本项目代码需包含原作者的版权及许可信息，包括但不限于文件头注释、协议等
    

简单来说，作者只想保留版权，没有任何其他限制，个人或者企业都可以放心使用。

___

前端源码: vue-naive-admin (github.com)

后端源码: isme-nest-serve (github.com)

文档手册: docs.isme.top

_访问不了 github 的朋友可以打开 文档手册，里面有对应 gitee 仓库的地址_

最后，如果这个项目对您或者贵公司有帮助，请 Star 或者 捐助支持一下，开源不易，您的支持是作者最大的动力~

作者：大脸怪  
链接：https://juejin.cn/post/7309921568493977637  
来源：稀土掘金
