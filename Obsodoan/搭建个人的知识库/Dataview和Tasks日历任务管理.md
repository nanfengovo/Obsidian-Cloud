---
created: 2024-10-10T18:07:05 (UTC +08:00)
tags: []
source: https://mp.weixin.qq.com/s/qDwBmwln_kvFQUS7RpkHgw
author: 秦吉峰
---

# Obsidian新手41-Dataview和Tasks日历任务管理

> ## Excerpt
> Obsidian插件Dataview和Tasks完成知识库的任务管理和日程管理

---
![图片](https://mmbiz.qpic.cn/mmbiz_png/MjrkNy7Zz9vaSL7QyN9SH9nhxf13poUiadqnZ9yu4YNG7IkOicc2ibvof08QYoaFmPgh9LZdzic9kFPSsicOw89pr6A/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

**想一群人搭建个人知识库的私信“1”联系你加入obsidian共创云股东。  
**

**实际碰到的问题**

如何将任务可以直观显示在日历视图里.如何实现?

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/MjrkNy7Zz9vV6MQrCh4IVSxMkPciaDXWKg5lLa92tIOUdWUoBxlUHvSa7bUTapUKbgnYJYHX7UmLN0QrA6aLyxw/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

___

Obsidian插件Dataview，将Obsidian Vault视为可查询的数据库。它提供了JavaScript API和基于流水线的查询语言，用于从Markdown页面中过滤、排序和提取数据。使用Dataview插件，用户可以通过编写查询语句来获取所需的数据，并以表格、列表或其他形式展示。该插件适用于需要对Vault中的数据进行高级查询和分析的用户，可以帮助用户更高效地管理和利用Markdown页面中的数据。

___

Obsidian插件Tasks是Obsidian知识库的任务管理插件。它可以跟踪整个vault中的任务，支持到期日期、重复任务、完成日期、子任务清单项和过滤功能。用户可以在任何视图或查询中切换任务状态，插件会更新源文件。安装简便，用户可以在Obsidian的社区插件浏览器中搜索“Tasks”并启用。用户可以在Markdown笔记中创建任务，并使用Tasks搜索块查找感兴趣的任务。插件提供了详细的用户文档，包括创建任务和查询任务等操作。插件完全免费，由Clare Macrae开发和支持。

![图片](https://mmbiz.qpic.cn/mmbiz_png/MjrkNy7Zz9vaSL7QyN9SH9nhxf13poUiarW9drW8qtISKQuWpxPKZbu516ib5jBXhvVVHsPKVkP83fV9gDJtq2lA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

实现思路  

主要参考bilibili博主   

> obsidian日历教程 任务视图
> 
> https://www.bilibili.com/video/BV1ELY1eKEZr/?spm\_id\_from=333.337.search-card.all.click&vd\_source=4dabd04541045ae06102e055c81037c5

Tasks插件地址:

https://github.com/obsidian-tasks-group/obsidian-tasks

Dataview插件地址:  

https://github.com/blacksmithgu/obsidian-dataview

博主分享的文件:

https://pan.baidu.com/s/1I\_aR\_6c0YA3FkKw674JIPA?pwd=cfmk

打开后这样的,基本插件和样式文件都有了.

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/MjrkNy7Zz9vV6MQrCh4IVSxMkPciaDXWKgCb9Rj3PYmj5q4IrRicFM51Tv3uYibbQU1DG9QdqGwMWwNHoFoBrf2cA/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

也可参考如下

> 国内插件安装
> 
> 秦吉峰，公众号：莱特纳[Obsidian新手全面入门10-国内安装插件](http://mp.weixin.qq.com/s?__biz=MzkwODI5MjM2OA==&mid=2247484305&idx=1&sn=73f6135e5d44e7d4d0a02e71cbbb5669&chksm=c0cd7beef7baf2f8f8ee5d5ff4503eb4554a6eef743b04a7517c34d2dcef672f2c9a90488796#rd)

准备阶段

首先，确保你已经安装了Dataview插件和Tasks插件,并在你的obsidion软件中启用。

完成后长这样  

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/MjrkNy7Zz9vV6MQrCh4IVSxMkPciaDXWK6Ygox06aXNJpxU6bib68XkkE9n3vU4akd7MqctCldoXl7T96LQ2NNIA/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/MjrkNy7Zz9vV6MQrCh4IVSxMkPciaDXWKmOOicbMLIRAtVgGAJCG3ibiby4TgeH5DPIm1mDOmaMhZia2RaHicuuE8ytg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

![图片](https://mmbiz.qpic.cn/sz_mmbiz_jpg/MjrkNy7Zz9vV6MQrCh4IVSxMkPciaDXWKqQ9zlx7hVIQiabiblRl15HpzdHCB3FzVzXoa6vicQ3DxkdPLSr24ekjRQ/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

直接下载制作好的库  
下载地址：https://www.jianguoyun.com/p/DaAPkpkQg8CdBxisgcQFIAA

> 自己做的库
> 
> 秦吉峰，公众号：莱特纳[Obsidian新手20-开箱即用卢曼卡片盒笔记库](http://mp.weixin.qq.com/s?__biz=MzkwODI5MjM2OA==&mid=2247484429&idx=1&sn=2e13d6d26fbd02ddbabe993e55807df5&chksm=c0cd7c72f7baf564f928172b6dc3d35bd413f8a8af45c7846c0af6a97aab526f37076bcd7b6e#rd)

![图片](https://mmbiz.qpic.cn/mmbiz_png/MjrkNy7Zz9vaSL7QyN9SH9nhxf13poUiaJJc7JNUwPPibYQJdJT15T9x9VLXOZNcs4InPdK9c0vhqTFF3VEwW3ibA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

基本使用——设置界面 已翻译

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/MjrkNy7Zz9vV6MQrCh4IVSxMkPciaDXWKx23YbapZyXK4g7h1QvCxD4YSDgx7jUJXQ8KiceWSWy0ZiaXwEI8KHibkw/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

添加快捷方式

![图片](https://mmbiz.qpic.cn/sz_mmbiz_jpg/MjrkNy7Zz9vV6MQrCh4IVSxMkPciaDXWK3lbhiaLUSciam8RykUhcRxk2f5Q9XPLmNGPsSXPWmlKcaY6YDYvEjjJw/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

![图片](https://mmbiz.qpic.cn/sz_mmbiz_jpg/MjrkNy7Zz9vV6MQrCh4IVSxMkPciaDXWKickCjEGkVc6VY9bhR9HN3BM1ibL7TRvOp8iaVvm1iasEicW9GGSyopZCh1w/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

这个就是todo详细设置了.

插件弄好了就弄日历视图

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/MjrkNy7Zz9vV6MQrCh4IVSxMkPciaDXWKuNMYjcIjqsghf9av6EcCldiaW6CUNXTlt580ATDtPqpqfWePjXPJWkw/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

这几个文件放进你的库里(就是文件夹对应目录即可)

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/MjrkNy7Zz9vV6MQrCh4IVSxMkPciaDXWKTWepYtydxx0RojNOXTDronljCzQ36sRNUk9DG2pIugdQ98xFB9ibLaA/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

我就放在目标这里.  

2打开日历视图如下  

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/MjrkNy7Zz9vV6MQrCh4IVSxMkPciaDXWKjy6DjEtYSMpRPAA8vjRWy4vmSwUQb9nlDg9wFDzlFMkiaFV4Ovf2feA/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

下面就是调整一下视图  

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/MjrkNy7Zz9vV6MQrCh4IVSxMkPciaDXWKUmNlc4AxnNiaslia5mumib4JpxPX88SKZCgvuaDuLlHq23qjm6RbvtQHg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

最后就是美化与界面排序的问题了  

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/MjrkNy7Zz9vV6MQrCh4IVSxMkPciaDXWK2o3Mp9SO4AReicqVAvNXoSvKvicmKBcLLhVS0C6ClLpQ3qITcrprUEFA/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

我自己设定的界面做个参考  

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/MjrkNy7Zz9vV6MQrCh4IVSxMkPciaDXWK2evv7YvJvWOBQlicrYmfnNf6Gkic9S6S5h4UJgWfXkTibvOXfAWPxxvgw/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

![图片](https://mmbiz.qpic.cn/mmbiz_png/MjrkNy7Zz9vaSL7QyN9SH9nhxf13poUiaIREZNkBwwT41JH8PmVCeIJcwVRAoAVdpKInqRJOPxBiblm2ibaia9t4jw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

知行合一  
本质上就是一个markdown文件,你需要加入双向链接一样可以实现链接.

日历视图下的任务管理  

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/MjrkNy7Zz9vV6MQrCh4IVSxMkPciaDXWKg5lLa92tIOUdWUoBxlUHvSa7bUTapUKbgnYJYHX7UmLN0QrA6aLyxw/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

看板工具的任务管理  

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/MjrkNy7Zz9v5IHUJ8libGkuIibujZUkRY8QHcYLuFNKRsquloDHPbygQru2I6RROlernbWiczHpYk9EOtu7hfhLpg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

给大家都做了一次看看那个任务管理合适自己.

