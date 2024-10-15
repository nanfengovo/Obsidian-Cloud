---
created: 2024-10-09T11:04:05 (UTC +08:00)
tags: []
source: https://mp.weixin.qq.com/s/yOiBrFNLiZMwEUE5pzW5_Q
author: 大姚
---

# 一个适用于 ASP.NET Core 的轻量级插件框架

> ## Excerpt
> PluginCore 是一个基于 ASP.NET Core 的轻量级插件框架，旨在简化插件的集成与管理。通过最少的配置，开发者可以快速集成并专注于业务逻辑的开发。它支持动态 WebAPI、插件隔离与共享、前后端分离、热插拔等特性！！

---
![图片](https://mmbiz.qpic.cn/mmbiz_png/ufWcjcomw8b6Lib0A0eic09h7UM0oewibib4JBPLkw1Mvb2p6sOzeHRtSHexOpy15TTJxdbibwBu97iamYXeGnEAfibOw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

## 前言

今天大姚给大家分享一个适用于 ASP.NET Core 的轻量级插件框架，简单配置，开箱即用：PluginCore。

## 项目概述

PluginCore 是一个基于 ASP.NET Core 的轻量级插件框架，旨在简化插件的集成与管理。通过最少的配置，开发者可以快速集成并专注于业务逻辑的开发。它支持动态 WebAPI、插件隔离与共享、前后端分离、热插拔等特性，非常适合需要高度模块化与可扩展性的应用场景。

## 主要特性

![图片](https://mmbiz.qpic.cn/mmbiz_png/Vtf2wZNabHAFmDd9ic2WwrKSZNtmBzRYXT3kGd0rxtbSUmUt0ztGTDEBZY6ia0M9wGSF9hbuLeZdiavKyUiapDiaOrA/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

## 项目技术栈

-   后端：.NET/C#，包括 .NET Standard、.NET Core、.NET 及 ASP.NET Core。
    
-   前端：Vue.js、vue-i18n、Vue Router、Vuex、Element UI，以及 babel、mockjs、sass、autoprefixer、eslint、axios、npm 等工具。
    

## 项目源代码

![图片](https://mmbiz.qpic.cn/mmbiz_png/Vtf2wZNabHAFmDd9ic2WwrKSZNtmBzRYXRsEXXK9SAVFOicwq5defVZ6GichphXJbbNw6MD0hYjBGeLDgNKFoVELQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

## 在 ASP.NET Core 项目中集成

推荐使用 NuGet 在 ASP.NET Core 项目中安装 PluginCore。在项目的根目录下执行以下命令：

```
<span data-style="display: block; background: url(&quot;https://mmbiz.qpic.cn/mmbiz_svg/9M0PhLTmTIfnJACqtiacDtrKtPHo4mH5MlXicVnicpZ2ibm1ooicNISC2WrE1bYk7uhHESkdqticrtX6ALABzlypjrH2aSIS8BP7cu/640?wx_fmt=svg&amp;from=appmsg&quot;) 10px 10px / 40px no-repeat rgb(40, 44, 52); height: 30px; width: 100%; margin-bottom: -7px; border-radius: 5px;"></span><code data-style="overflow-x: auto; padding: 15px 16px 16px; color: rgb(171, 178, 191); background: rgb(40, 44, 52); border-radius: 5px; display: -webkit-box; font-family: Consolas, Monaco, Menlo, monospace; font-size: 12px;">Install-Package&nbsp;PluginCore.AspNetCore<br><br></code>
```

或在 Visual Studio 的 管理 NuGet 程序包中搜索安装：

![图片](https://mmbiz.qpic.cn/mmbiz_png/Vtf2wZNabHAFmDd9ic2WwrKSZNtmBzRYX77tsFMIfeMkANACKy3Kav3vZxxECiad0Y3iaa5nEHxrvAxQeny5AibOgw/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

## 在 ASP.NET Core 应用程序中修改代码

修改 Startup.cs：

```
<span data-style="display: block; background: url(&quot;https://mmbiz.qpic.cn/mmbiz_svg/9M0PhLTmTIfnJACqtiacDtrKtPHo4mH5MlXicVnicpZ2ibm1ooicNISC2WrE1bYk7uhHESkdqticrtX6ALABzlypjrH2aSIS8BP7cu/640?wx_fmt=svg&amp;from=appmsg&quot;) 10px 10px / 40px no-repeat rgb(40, 44, 52); height: 30px; width: 100%; margin-bottom: -7px; border-radius: 5px;"></span><code data-style="overflow-x: auto; padding: 15px 16px 16px; color: rgb(171, 178, 191); background: rgb(40, 44, 52); border-radius: 5px; display: -webkit-box; font-family: Consolas, Monaco, Menlo, monospace; font-size: 12px;">using&nbsp;PluginCore.AspNetCore.Extensions;<br><br>public&nbsp;void&nbsp;ConfigureServices(IServiceCollection&nbsp;services)<br>{<br>&nbsp;&nbsp;&nbsp;&nbsp;services.AddControllers();<br>&nbsp;&nbsp;&nbsp;&nbsp;services.AddPluginCore();&nbsp;//&nbsp;添加&nbsp;PluginCore<br>}<br><br>public&nbsp;void&nbsp;Configure(IApplicationBuilder&nbsp;app,&nbsp;IWebHostEnvironment&nbsp;env)<br>{<br>&nbsp;&nbsp;&nbsp;&nbsp;<span>if</span>&nbsp;(env.IsDevelopment())<br>&nbsp;&nbsp;&nbsp;&nbsp;{<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;app.UseDeveloperExceptionPage();<br>&nbsp;&nbsp;&nbsp;&nbsp;}<br><br>&nbsp;&nbsp;&nbsp;&nbsp;app.UseHttpsRedirection();<br>&nbsp;&nbsp;&nbsp;&nbsp;app.UseRouting();<br>&nbsp;&nbsp;&nbsp;&nbsp;app.UsePluginCore();&nbsp;//&nbsp;使用&nbsp;PluginCore<br>&nbsp;&nbsp;&nbsp;&nbsp;app.UseAuthorization();<br><br>&nbsp;&nbsp;&nbsp;&nbsp;app.UseEndpoints(endpoints&nbsp;=&gt;<br>&nbsp;&nbsp;&nbsp;&nbsp;{<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;endpoints.MapControllers();<br>&nbsp;&nbsp;&nbsp;&nbsp;});<br>}<br></code>
```

## 访问管理界面

-   访问 https://localhost:5001/PluginCore/Admin 进入 PluginCore 管理界面（注意将端口替换为你的实际端口）。
    

## 界面演示截图

![图片](https://mmbiz.qpic.cn/mmbiz_png/Vtf2wZNabHAFmDd9ic2WwrKSZNtmBzRYX98sV4VxcCWLzTBdxG1u5zQL5E2RpWv2NjfqBTkOzqcIdgySkicAJqMQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

![图片](https://mmbiz.qpic.cn/mmbiz_png/Vtf2wZNabHAFmDd9ic2WwrKSZNtmBzRYXmaiahx0nPcibbGnMvYib8yAljVGVia2H918EAsmHSgicFKUnZalzFMibe5cQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

![图片](https://mmbiz.qpic.cn/mmbiz_png/Vtf2wZNabHAFmDd9ic2WwrKSZNtmBzRYXhGVEYQ7urPDUp5NMfwAZUMFEwPVKFV7vChmu3s1fVf2iaCvOBGCKXIg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

## 项目源码地址

更多项目实用功能和特性欢迎前往项目开源地址查看👀，别忘了给项目一个Star支持💖。

-   开源地址：https://github.com/yiyungent/PluginCore
    
-   在线文档：https://yiyungent.github.io/PluginCore/zh
    

## 优秀项目和框架精选

该项目已收录到C#/.NET/.NET Core优秀项目和框架精选中，关注优秀项目和框架精选能让你及时了解C#、.NET和.NET Core领域的最新动态和最佳实践，提高开发工作效率和质量。坑已挖，欢迎大家踊跃提交PR推荐或自荐（让优秀的项目和框架不被埋没🤞）。

-   GitHub开源地址：https://github.com/YSGStudyHards/DotNetGuide/blob/main/docs/DotNet/DotNetProjectPicks.md
    
-   Gitee开源地址：https://gitee.com/ysgdaydayup/DotNetGuide/blob/main/docs/DotNet/DotNetProjectPicks.md
    

![图片](https://mmbiz.qpic.cn/mmbiz_gif/Ljib4So7yuWgtu32lo8txTia7urcjBx8VnHePPpZ8xSbEdsS8Hou17v7epnoibWWkIuHjVEd19ZWn0SibXEfvPPIxA/640?wx_fmt=gif&tp=webp&wxfrom=5&wx_lazy=1)

-   ## [免费开源的程序员简历模板](http://mp.weixin.qq.com/s?__biz=MzIxMTUzNzM5Ng==&mid=2247497295&idx=1&sn=c0497b6bb472ecadbdeea68735562275&chksm=97516ad4a026e3c27f4fc0f5bd2a7e29f3e8c8be44bb770ab10f210ffa732486ee80f9c2bc2f&scene=21#wechat_redirect)  
    
-   ## [了解作者&获取更多学习资料](http://mp.weixin.qq.com/s?__biz=MzIxMTUzNzM5Ng==&mid=2247485948&idx=1&sn=afa4d107bb5b102d5d29054216b14af8&chksm=97529567a0251c71db5395776cbb942570b306e77d6c7de009390aece8739fe64f220dae8300&scene=21#wechat_redirect)
    
-   ## [程序员常用的开发工具软件推荐](http://mp.weixin.qq.com/s?__biz=MzIxMTUzNzM5Ng==&mid=2247487776&idx=1&sn=f3a8ba9d8e293312bce8bbf9eeca3983&chksm=97528dbba02504ad612f40cbad3c3296c1ad9b91c014875068cb9f197b05765406bf3bd16cde&scene=21#wechat_redirect)
    
-   ## [加入DotNetGuide技术社区交流群](http://mp.weixin.qq.com/s?__biz=MzIxMTUzNzM5Ng==&mid=2247500959&idx=2&sn=6842e8d254cff911f7a06b255d1303e8&chksm=97515804a026d112afc0f535e3dbfc1572b1c71abe93e988ac1b9015c7c446947d1a379e452e&scene=21#wechat_redirect)
    
-   [C#/.NET/.NET Core推荐学习书籍](http://mp.weixin.qq.com/s?__biz=MzIxMTUzNzM5Ng==&mid=2247494103&idx=1&sn=322cbe4a48cf3f7054b4122c04af91e4&chksm=9751754ca026fc5ac0b5a1e37a8cdfdeb59a1952af4190e48edca120f90ede763f389180c520&scene=21#wechat_redirect)  
    
-   [C#/.NET/.NET Core学习视频汇总](http://mp.weixin.qq.com/s?__biz=MzIxMTUzNzM5Ng==&mid=2247487746&idx=1&sn=d2d5d8b309cef1ba72026d502cc71c4a&chksm=97528d99a025048f7c4ef3421478e186728284f03f8c755d8a851472dbf1c319e75babd356a9&scene=21#wechat_redirect)
    
-   ## [.NET/.NET Core ORM框架资源汇总](http://mp.weixin.qq.com/s?__biz=MzIxMTUzNzM5Ng==&mid=2247493672&idx=1&sn=5105ef0a229e3fbc9caf0f8fae0d99bb&chksm=975174b3a026fda53788936eb6ce130d4f689e1f6f02da98f5349c91ee11c66a5430e4488646&scene=21#wechat_redirect)
    
-   ## [](http://mp.weixin.qq.com/s?__biz=MzIxMTUzNzM5Ng==&mid=2247486354&idx=1&sn=d636dfbef5faea3821c095e0d7640f64&chksm=97529709a0251e1f9eaf86e2248015460de260700d74ff6923fc2e656f70db728a878f1b9599&scene=21#wechat_redirect)[ASP.NET Core开发者学习指南路线图](http://mp.weixin.qq.com/s?__biz=MzIxMTUzNzM5Ng==&mid=2247487740&idx=1&sn=11e5387dca381b2597be348279ebd626&chksm=97528c67a02505712f0f180ffd4af0971fe74ab37f88df44018c9a3ad4f814770877a002a634&scene=21#wechat_redirect)
    
-   [C#/.NET/.NET Core面试宝典（基础版）](http://mp.weixin.qq.com/s?__biz=MzIxMTUzNzM5Ng==&mid=2247490975&idx=1&sn=c1e47f1c253a60c67984d6ee01a49803&chksm=97528104a0250812edeccf2ceaaa6fdbddd04f98ed46d8a826f4e77a6ca5e631356b6bfe04c8&scene=21#wechat_redirect)
    
-   [C#/.NET/.NET Core优秀项目和框架推荐](http://mp.weixin.qq.com/s?__biz=MzIxMTUzNzM5Ng==&mid=2247485418&idx=1&sn=408a44210c21d0ab739ba3108a3f635c&chksm=97529b71a02512679710c370ac85d2deb8b8b5f9298208c69358336445f29a520350b4057c0e&scene=21#wechat_redirect)
    
-   [C#/.NET/.NET Core学习、工作、面试指南](http://mp.weixin.qq.com/s?__biz=MzIxMTUzNzM5Ng==&mid=2247496760&idx=1&sn=7d3cfef5455980a88667a6d2d607647c&chksm=975168a3a026e1b511c87862eb1efe76cb46f1a503ecba0c5f7989f485481c6d8a7d4af6385f&scene=21#wechat_redirect)
    

![图片](https://mmbiz.qpic.cn/mmbiz_gif/hjqLMibiaFS0sxrWqicJWNIomzmcPaGfQ59UqkibS2BqnMLSxe3vO21OaHrB4RJ7UeRBzGjfyicVHDnB8ibspuAUxibnA/640?wx_fmt=gif&tp=webp&wxfrom=5&wx_lazy=1)

**学习是一个永无止境的过程，你知道的越多，你不知道的也会越多，在有限的时间内坚持每天多学一点，你一定能成为你想要成为的那个人。不积跬步无以至千里，不积小流无以成江海！**

![图片](https://mmbiz.qpic.cn/mmbiz_gif/Zxmz2vibxicFJUs3WfYfk2eDHlllAEfaZBSDYcJhf1SCovVSvfPV7awNknJRG5WKq52FGibPicU7CokA8ASoicAYchQ/640?wx_fmt=gif&wxfrom=5&wx_lazy=1&tp=webp)
