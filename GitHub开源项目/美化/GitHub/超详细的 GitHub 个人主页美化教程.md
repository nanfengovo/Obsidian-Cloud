---
created: 2024-10-14T22:18:30 (UTC +08:00)
tags: 
source: https://mp.weixin.qq.com/s/BFjikQlU20FWZNnXscy5bw
author: 晓林
---

# 超详细的 GitHub 个人主页美化教程

> ## Excerpt
> 让你的 GitHub 主页变的酷炫起来！

---
Guthub 个人主页 （官方称呼是 profile）可以展示很多有用的信息，例如添加一个首页被访问次数的计数器，一个被 Star 与 Commit 的概览信息，以及各种技能标签，设备标签等，还可以利用 wakatime 显示你最近编码各类语言的使用时长，甚至你最近 Steam 游戏游玩排行榜...

## 默认主页

默认情况下，GitHub 个人主页会显示其仓库信息、提交信息，例如 Linux 之父 Linus 的 GitHub 主页 长这样：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGoYPbm4ZHuqwlUTAc3ZniaYDa92LXPpOgxTqShBg4yFe6sqDia3rFwRsRg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



但是，这个主页是可以定制的。GitHub 支持这个功能，并且有相关的文档说明：Setting up and managing your GitHub profile - GitHub Docs。

例如有的长这样：Luo Lei

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGo8pbIxBNhHJcXNe8u537WJzjTzOcwcUrn6py8kPwVMiaW6YSxia1V4vUg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

这就远比默认主页好看不少，令人印象深刻。



## 原理

自定义主页很简单。我们首先在 GitHub 上新建一个仓库，仓库名和自己 Github 用户名相同，然后添加一个 README.md 自述文件，在该文件里添加信息即可。

例如，我创建的仓库：github.com/Peter-JXL/Peter-JXL

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGovmPoaPDxsLQgp1paiaRiabbEsbkJTPqAVtQqhdQOFYcxJS3MiaHU4UuFQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

可以看到右上角有个提示：

> **Peter-JXL/Peter-JXL** is a special repository.
> 
> Its `README.md` will appear on your public profile.
> 
> 翻译：
> 
> 这是一个特殊的仓库。
> 
> 它的 `README.md` 会出现在你的首页中。



## 侧边栏

在讲解如何定制之前，我们先关注下左侧也有个人信息展示：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGot2icYCu4LEricZWzzPWAEsxwaUmicZv9P73dMjI18ib4OxARRAyVjRafJQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)





这个可以直接在个人首页上，点击左侧的 Edit profile 进行编辑：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGo2ibZyicnKZH2XgtobwGNWibFR9PAwKEI37Id9G9DjnpvuColm0dedAia3w/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)





可以修改名字、签名（Bio）、公司、地点、邮箱、网站.......... 按需修改即可。

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGoe5YmZ6SOHCZmYo1yXQUibNSJjmafsfUjeSc3rNCkaTxZFTCm2xJ4m5A/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



接下来讲讲如何定制右侧。



## 新建仓库

新建一个同名仓库，并添加一个自述文件（README.md），确认：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGoHGRLhkleWl4BvGM08aoAdmibT4Wzb6q2OuHicfytFBsd8NPAR8VFibKfA/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)







GitHub 默认为此文件添加了一行字：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGonSEep5rg7ic45iaH9byl37EeXF69ueyiaFg3cuS5R3R34JCavjkzgZ8pQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)





此时我们的首页也会跟着变：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGoYgTMNNP3hgUtUJTMg3DnE1Lpu7SqxAOkLSbCrsTEdRf41L9ibuKTK4w/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



## 如何定制

接下来，你就可以通过修改 README.md 来定制主页了。由于是 Markdown 文件，扩展性很高，并且全面支持 emoji。

此外，人的创造力有限，如何短时间内拥有一个酷炫的个人主页呢？

答案是 `ctrl+c`，`ctrl+v`。看到好看的模板，可以直接 fork，修改下相关变量即可。

此外 GitHub 上也有不少人收集优秀案例：

-   awesome-github-profile-readme
    
-   awesome-github-profiles
    
-   beautify-github-profile
    

文末也会贴出我的 GitHub 地址，方便大家抄作业😀

接下来讲讲一些优秀的信息展示卡片。



### GitHub 统计卡片

官网：github.com/anuraghazra/github-readme-stats

效果：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGo9w5KHQMle3ZfFPZTdRbrsGXHPvITe5UUzxwxOJFdkyibTer5BCxvz3A/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)





使用方法很简单，将如下代码复制到你的 markdown 文件中，更改 `?username=` 的值为你的 GitHub 用户名：

```
<section><span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 96, 92);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 189, 68);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(0, 202, 78);"></span></span><span> </span></section><pre data-title="true"><code data-line="141"><span><span><span>!</span>[<span>Anurag's GitHub stats</span>](<span>https://github-readme-stats.vercel.app/api?username=anuraghazra</span>)</span><br></span></code></pre>
```



这个是默认样式，很简陋，可以配置显示图标、主题样式等，具体请看官网文档。







### GitHub 使用语言统计

官网：github.com/anuraghazra/github-readme-stats

效果：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGoUqAytzvJMbQb69h5AXjtQefDyGusMrJap5SIz2T1YC0qhUQWdU98tg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)





使用方法同上，复制如下代码，更改 `?username=` 的值：

```
<section><span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 96, 92);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 189, 68);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(0, 202, 78);"></span></span><span> </span></section><pre data-title="true"><code data-line="169"><span><span><span>!</span>[<span>Top Langs</span>](<span>https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra</span>)</span><br></span></code></pre>
```



同理，这个也可以配置主题和布局（参考文档）。



### Metrics 统计信息

会展示 GitHub 上的一些统计信息，效果：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGopYq1uiaIPibkm6zMyqtW1HzWT9uZqxCLu87Nvgh9Af8GfCiaeQuMAiaLUg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



我们可以去官网演示下：输入你的 GitHub 用户名，然后点击按钮：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGonM0AlgnhyWnicPg0oEeialjiahu9L0LicMGC2el8dMcuTKic2wOp32MqKzg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

> PS：这个项目也是开源在 GitHub 上的：github.com/lowlighter/metrics，并且还有其他的功能（后续会讲到）。





就能看到效果如下：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGoRjSzfkfuPAEWdXoyuEk92j0iaQRzwKIWmPibWrnjxcuj6mZX1dtyDuBw/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)





这个配置起来稍微复杂一点点。根据官网文档，使用该功能的方式之一是使用 GitHub Action。

首先我们得创建一个 GitHub personal token，位置：右上角个人头像 →  settings → Developer settings → Personal access tokens：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGobLoMfqS3ibiaAI6QB9UHLMmQoQBkXNXgK6DicEucxrnVfaZjyazhgKFiaA/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



接下来就是勾选 scopes（可以理解为权限，这个就根据不同插件的要求来勾选了，具体得看文档）：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGow6ZNJ6LC47OJwDc8AcLYtVJZod7icVOtWSXibfQuJbg0YU1qPgIciblPw/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)





然后会生成 token，只展示一次，注意好好保管：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGoREzj4XJxIr1P6wQAKdvT8lrVFHH7GaBb0jEJUayubwqktnOARibickBQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



然后去到个人项目里的 settings 页面，将刚刚生成的 token 作为一个密钥（先创建一个环境，名字为 production；然后再创建一个名字为 METRICS\_TOKEN 的 secret，值为刚刚生成的 token）：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGoLH7LTLndFIbjgJXKLST5oAhwvzTy0hkHQ4PH56pBjKMabPjMPtwyJA/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)





第三步，生成一个 Action，其实 metrics 已经帮我们生成了一个 Action：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGo9crS34q81yn4O2PowK2iccjaUfK9c0TUicPjDH8QcHiaSLSicejDvR0ncQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)





内容如下（建议自行核对下，例如我这边在第 9 行加了个 environment 变量）：

```
<section><span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 96, 92);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 189, 68);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(0, 202, 78);"></span></span><span> </span></section><pre data-title="true"><code data-line="276"><span><span>name</span><span data-style="color: rgb(214, 176, 7);">:</span> Metrics<br></span><span><span>on</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>  <span># Schedule updates (each hour)</span><br></span><span>  <span>schedule</span><span data-style="color: rgb(214, 176, 7);">:</span> <span data-style="color: rgb(214, 176, 7);">[</span><span data-style="color: rgb(214, 176, 7);">{</span><span>cron</span><span data-style="color: rgb(214, 176, 7);">:</span> <span data-style="color: rgb(73, 198, 236);">"0 * * * *"</span><span data-style="color: rgb(214, 176, 7);">}</span><span data-style="color: rgb(214, 176, 7);">]</span><br></span><span>  <span># Lines below let you run workflow manually and on each commit</span><br></span><span>  <span>workflow_dispatch</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>  <span>push</span><span data-style="color: rgb(214, 176, 7);">:</span> <span data-style="color: rgb(214, 176, 7);">{</span><span>branches</span><span data-style="color: rgb(214, 176, 7);">:</span> <span data-style="color: rgb(214, 176, 7);">[</span><span data-style="color: rgb(73, 198, 236);">"master"</span><span data-style="color: rgb(214, 176, 7);">,</span> <span data-style="color: rgb(73, 198, 236);">"main"</span><span data-style="color: rgb(214, 176, 7);">]</span><span data-style="color: rgb(214, 176, 7);">}</span><br></span><span><span>jobs</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>  <span>github-metrics</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>    <span>runs-on</span><span data-style="color: rgb(214, 176, 7);">:</span> ubuntu<span data-style="color: rgb(214, 176, 7);">-</span>latest<br></span><span>    <span>environment</span><span data-style="color: rgb(214, 176, 7);">:</span> <br></span><span>      <span>name</span><span data-style="color: rgb(214, 176, 7);">:</span> production<br></span><span>    <span>permissions</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>      <span>contents</span><span data-style="color: rgb(214, 176, 7);">:</span> write<br></span><span>    <span>steps</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>      <span data-style="color: rgb(214, 176, 7);">-</span> <span>uses</span><span data-style="color: rgb(214, 176, 7);">:</span> lowlighter/metrics@latest<br></span><span>        <span>with</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>          <span># Your GitHub token</span><br></span><span>          <span># The following scopes are required:</span><br></span><span>          <span>#  - public_access (default scope)</span><br></span><span>          <span># The following additional scopes may be required:</span><br></span><span>          <span>#  - read:org      (for organization related metrics)</span><br></span><span>          <span>#  - read:user     (for user related data)</span><br></span><span>          <span>#  - read:packages (for some packages related data)</span><br></span><span>          <span>#  - repo          (optional, if you want to include private repositories)</span><br></span><span>          <span>token</span><span data-style="color: rgb(214, 176, 7);">:</span> $<span data-style="color: rgb(214, 176, 7);">{</span><span data-style="color: rgb(214, 176, 7);">{</span> secrets.METRICS_TOKEN <span data-style="color: rgb(214, 176, 7);">}</span><span data-style="color: rgb(214, 176, 7);">}</span><br></span><span><br></span><span>          <span># Options</span><br></span><span>          <span>user</span><span data-style="color: rgb(214, 176, 7);">:</span> Peter<span data-style="color: rgb(214, 176, 7);">-</span>JXL<br></span><span>          <span>template</span><span data-style="color: rgb(214, 176, 7);">:</span> classic<br></span><span>          <span>base</span><span data-style="color: rgb(214, 176, 7);">:</span> header<span data-style="color: rgb(214, 176, 7);">,</span> activity<span data-style="color: rgb(214, 176, 7);">,</span> community<span data-style="color: rgb(214, 176, 7);">,</span> repositories<span data-style="color: rgb(214, 176, 7);">,</span> metadata<br></span><span>          <span>config_timezone</span><span data-style="color: rgb(214, 176, 7);">:</span> Asia/Shanghai<br></span></code></pre>
```



等我们提交后，就会自动生成一个 svg 文件：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGo3CTZFeyoPicQIBZSgC0lNvickujd5zhsVL5cXKzdjM6VjbHny3iaficfUw/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)





然后我们在自述文件里添加这个图片，例如 Markdown 格式如下（其实也可以用 HTML 格式，更灵活）：

```
<section><span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 96, 92);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 189, 68);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(0, 202, 78);"></span></span><span> </span></section><pre data-title="true"><code data-line="292"><span><span>!</span><span data-style="color: rgb(214, 176, 7);">[</span><span>Metrics</span><span data-style="color: rgb(214, 176, 7);">]</span><span data-style="color: rgb(214, 176, 7);">(</span><span>/</span>github<span>-</span>metrics<span data-style="color: rgb(214, 176, 7);">.</span><span>svg</span><span data-style="color: rgb(214, 176, 7);">)</span><br></span></code></pre>
```



此时的首页效果：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGoe9HW665ay5GKPrzlBuZVQAr1picWoZQtIet0yTuykBsGIxUDic9GBhCw/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)





### GitHub 资料奖杯

官网：github.com/ryo-ma/github-profile-trophy

效果：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGo8ajgWoLubXoEl4hicZA9lxJdwAlCF9Rf6Sk2eicWbGzQwx9yibiayibXJ6g/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)





使用方法同上，复制如下代码，更改 `?username=` 的值：

```
<section><span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 96, 92);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 189, 68);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(0, 202, 78);"></span></span><span> </span></section><pre data-title="true"><code data-line="320"><span><span><span>!</span>[<span>trophy</span>](<span>https://github-profile-trophy.vercel.app/?username=ryo-ma</span>)</span><br></span></code></pre>
```



同理，这个也可以配置主题。





### GitHub 徽章

为你的开源项目生成高质量小徽章图标，直接复制链接使用。

官网：Shields.io

效果：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGoibL6bOZdhZz7Gt3u8xrOLsZBQaLYsZ0lGnlMvUAsOm3oxYicwoibBXESg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



示例代码：

```
<section><span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 96, 92);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 189, 68);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(0, 202, 78);"></span></span><span> </span></section><pre data-title="true"><code data-line="348"><span><span><span><span data-style="color: rgb(214, 176, 7);">&lt;</span>img</span> <span data-style="color: rgb(230, 0, 103);">src</span><span><span data-style="color: rgb(214, 176, 7);">=</span><span data-style="color: rgb(214, 176, 7);">"</span>https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&amp;logo=html5&amp;logoColor=white<span data-style="color: rgb(214, 176, 7);">"</span></span> <span data-style="color: rgb(214, 176, 7);">/&gt;</span></span> <br></span><span><span><span><span data-style="color: rgb(214, 176, 7);">&lt;</span>img</span> <span data-style="color: rgb(230, 0, 103);">src</span><span><span data-style="color: rgb(214, 176, 7);">=</span><span data-style="color: rgb(214, 176, 7);">"</span>https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&amp;logo=css3<span data-style="color: rgb(214, 176, 7);">"</span></span> <span data-style="color: rgb(214, 176, 7);">/&gt;</span></span> <br></span><span><span><span><span data-style="color: rgb(214, 176, 7);">&lt;</span>img</span> <span data-style="color: rgb(230, 0, 103);">src</span><span><span data-style="color: rgb(214, 176, 7);">=</span><span data-style="color: rgb(214, 176, 7);">"</span>https://img.shields.io/badge/-JavaScript-oringe?style=flat-square&amp;logo=javascript<span data-style="color: rgb(214, 176, 7);">"</span></span> <span data-style="color: rgb(214, 176, 7);">/&gt;</span></span><br></span></code></pre>
```



### GitHub 访客徽章

这个徽章会实时改变，记录此页面被访问的次数。

官网：visitor-badge.glitch.me

效果：![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGo84vGYHkoPA5oJyXrTTj33nEWJXzVMjlQBWhVWp4PeIzuaB8YazCukw/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

使用方法：复制如下代码到 Markdown 并替换 `page_id` 的值为用户名

```
<section><span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 96, 92);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 189, 68);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(0, 202, 78);"></span></span><span> </span></section><pre data-title="true"><code data-line="364"><span><span><span>!</span>[<span>visitors</span>](<span>https://visitor-badge.glitch.me/badge?page_id=page.id&amp;left_color=green&amp;right_color=red</span>)</span><br></span></code></pre>
```

可以配置颜色，参数为：left\_color，right\_color









### GitHub 活动统计图

动态生成的活动图，用于显示您过去 31 天的 GitHub 活动。

官网：github.com/Ashutosh00710/github-readme-activity-graph

效果：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGoHX5vhmEaHYqjxFDOH3SYZddPTkTzJ8icR00JPRhbEKOYbW6ol7CgwEQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)







使用方法同上，复制如下代码，更改 `?username=` 的值：

```
<section><span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 96, 92);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 189, 68);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(0, 202, 78);"></span></span><span> </span></section><pre data-title="true"><code data-line="396"><span><span><span>!</span>[<span>Ashutosh's github activity graph</span>](<span>https://github-readme-activity-graph.vercel.app/graph?username=Ashutosh00710</span>)</span><br></span></code></pre>
```

可以配置主题。





### 修仙系列统计卡片

一个以凡人修仙传境界为基础的 Github 统计卡片。等级分为：\['道祖', '大罗', '太乙', '金仙', '真仙', '大乘', '合体', '炼虚', '化神', '元婴', '金丹', '筑基', '练气'\]，对应区间：\[1, 5, 10, 15, 20, 30,40,50,60, 70, 80, 90, 100\]。

官网：IceEnd/github-immortality

效果：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGoKxt8sLk0Rj6Ncbu2kiaqvc3DRCQvlzne7YDc1OCPC3ZNeibqBLrL36CQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



使用方法同上，复制如下代码，更改 `?username=` 的值：

```
<section><span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 96, 92);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 189, 68);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(0, 202, 78);"></span></span><span> </span></section><pre data-title="true"><code data-line="420"><span><span><span>!</span>[<span>IceEnd's GitHub stats</span>](<span>https://github-immortality.vercel.app/api?username=iceend</span>)</span><br></span></code></pre>
```







### GitHub 连续打卡

在 README 中展示您连续提交代码的次数。

官网：github.com/DenverCoder1/github-readme-streak-stats

效果：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGo74EiaBJm0E9vLGiaOzrMOpxuyMetQPSiaOyuex5wqwZYhRbyw3EkGic2bg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



使用方法同上，复制如下代码，更改 `?username=` 的值：

```
<section><span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 96, 92);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 189, 68);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(0, 202, 78);"></span></span><span> </span></section><pre data-title="true"><code data-line="444"><span><span><span>!</span>[<span>GitHub Streak</span>](<span>https://streak-stats.demolab.com/?user=DenverCoder1</span>)</span><br></span></code></pre>
```

同理，支持主题、样式等配置。





### 社交统计

在 README 中展示你在一些流行的网站的数据，例如知乎，GitHub，B 站，LeetCode，掘金，CSDN，牛客。

官网：github.com/songquanpeng/stats-cards

效果：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGoJRZmZMWzIicwqXKoJvFp94NTO272QBibvZxHe9johFSwThgFurKSwTzg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



使用方法：复制代码到 Markdown 并替换 username 的值为那个网站的用户名

```
<section><span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 96, 92);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 189, 68);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(0, 202, 78);"></span></span><span> </span></section><pre data-title="true"><code data-line="468"><span>![](https://stats.justsong.cn/api/leetcode?username=quanpeng&amp;cn=true)<br></span></code></pre>
```



### star 趋势

如果想要统计和展示自己某个项目的 star 趋势，可以使用下面这两个工具。



#### Star History

官网：https://star-history.t9t.io

输入仓库名，就能自动生成 star 增长曲线。还能输入多个仓库查看项目对比：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGomJfqleaFDdzEACH01Eibm6j2jxTiaMxibTBoLEU631JPP0DPZoGqTrVQg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



#### GitHub Star History

官网：https://codetabs.com/github-stars/github-star-history.html

用法和上一个工具完全一样，就是样式有点不同：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGopR98VPHE4C1OS5eg2bu6CZI3wtepd7FXLpoZxgrr0NwvGRBLqtz9TQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)





### GitHub Corners：分享角标

如果你的 GitHub 项目有一个对应的网站，并且想要用户通过网站跳转到 GitHub 项目页从而得到 star，不防试试这个。

官网：https://tholman.com/github-corners

它可以帮你生成给网站添加 GitHub 角标的代码，只需要选择一个风格，复制代码到自己的项目主页文件中，将超链接替换为自己的仓库地址即可。

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGo4RSCG6kDicic6hYyDFOExOP9wPhgc3eBMevVKibSyHaSpQby95z8DCibmA/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

  





### 打字特效

让内容通过打字的特效来展示，炫酷。

官网：github.com/DenverCoder1/readme-typing-svg

效果：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_gif/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGosiaBIBxSVeiapYepVvrjggb61ibauaQqu77HHWqeo3qN7NTcho4HoEKKw/640?wx_fmt=gif&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



使用方法：复制代码到 Markdown 并替换 `?lines=` 的值为你想要的内容，字与字之间用分号隔开

```
<section><span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 96, 92);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 189, 68);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(0, 202, 78);"></span></span><span> </span></section><pre data-title="true"><code data-line="538"><span><span><span>!</span>[<span>Typing SVG</span>](<span>https://readme-typing-svg.demolab.com/?lines=First+line+of+text;Second+line+of+text</span>)</span><br></span></code></pre>
```





更多配置参考官网文档。还可以去 demo 站里自行调试：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGoiaLch9pZ8NmGicXQnibicy0yrNSfaupqpmxDyiaNRIOekGfAxcBpe7pjD2g/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)









### 贪吃蛇

默认的提交信息是这样子的：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGo2IeXQAXZbVJA8nYBEVWPr8A11PuEVzLyU4waSFGSjoPQGovhxVYJ3Q/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)





而我们可以将其变成一个动画：一只贪吃蛇挨个吃掉图里的绿点：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_gif/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGo2ibqq3cW5jqaicfSv7ftGzIicpeia5OBvCy4NkPKg1W5H3PxF2VCYiaIAgg/640?wx_fmt=gif&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

  



使用起来也不难，先新建一个 workflow 文件（名字随意），不需要任何改动，然后提交：

```
<section><span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 96, 92);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 189, 68);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(0, 202, 78);"></span></span><span> </span></section><pre data-title="true"><code data-line="621"><span><span>name</span><span data-style="color: rgb(214, 176, 7);">:</span> generate animation<br></span><span><br></span><span><span>on</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>  <span># run automatically every 2 hours</span><br></span><span>  <span>schedule</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>    <span data-style="color: rgb(214, 176, 7);">-</span> <span>cron</span><span data-style="color: rgb(214, 176, 7);">:</span> <span data-style="color: rgb(73, 198, 236);">"0 */2 * * *"</span> <br></span><span>  <br></span><span>  <span># allows to manually run the job at any time</span><br></span><span>  <span>workflow_dispatch</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>  <br></span><span>  <span># run on every push on the master branch</span><br></span><span>  <span>push</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>    <span>branches</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>    <span data-style="color: rgb(214, 176, 7);">-</span> master<br></span><span>  <br></span><span>  <br></span><span><br></span><span><span>jobs</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>  <span>generate</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>    <span>permissions</span><span data-style="color: rgb(214, 176, 7);">:</span> <br></span><span>      <span>contents</span><span data-style="color: rgb(214, 176, 7);">:</span> write<br></span><span>    <span>runs-on</span><span data-style="color: rgb(214, 176, 7);">:</span> ubuntu<span data-style="color: rgb(214, 176, 7);">-</span>latest<br></span><span>    <span>timeout-minutes</span><span data-style="color: rgb(214, 176, 7);">:</span> <span>5</span><br></span><span>  <br></span><span>    <span>steps</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>      <span># generates a snake game from a github user (&lt;github_user_name&gt;) contributions graph, output a svg animation at &lt;svg_out_path&gt;</span><br></span><span>      <span data-style="color: rgb(214, 176, 7);">-</span> <span>name</span><span data-style="color: rgb(214, 176, 7);">:</span> generate github<span data-style="color: rgb(214, 176, 7);">-</span>contribution<span data-style="color: rgb(214, 176, 7);">-</span>grid<span data-style="color: rgb(214, 176, 7);">-</span>snake.svg<br></span><span>        <span>uses</span><span data-style="color: rgb(214, 176, 7);">:</span> Platane/snk/svg<span data-style="color: rgb(214, 176, 7);">-</span>only@v3<br></span><span>        <span>with</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>          <span>github_user_name</span><span data-style="color: rgb(214, 176, 7);">:</span> $<span data-style="color: rgb(214, 176, 7);">{</span><span data-style="color: rgb(214, 176, 7);">{</span> github.repository_owner <span data-style="color: rgb(214, 176, 7);">}</span><span data-style="color: rgb(214, 176, 7);">}</span><br></span><span>          <span>outputs</span><span data-style="color: rgb(214, 176, 7);">:</span> <span data-style="color: rgb(214, 176, 7);">|</span><span data-style="color: rgb(73, 198, 236);"><br></span></span><span><span data-style="color: rgb(73, 198, 236);">            dist/github-contribution-grid-snake.svg<br></span></span><span><span data-style="color: rgb(73, 198, 236);">            dist/github-contribution-grid-snake-dark.svg?palette=github-dark</span><br></span><span>  <br></span><span>  <br></span><span>      <span># push the content of &lt;build_dir&gt; to a branch</span><br></span><span>      <span># the content will be available at https://raw.githubusercontent.com/&lt;github_user&gt;/&lt;repository&gt;/&lt;target_branch&gt;/&lt;file&gt; , or as github page</span><br></span><span>      <span data-style="color: rgb(214, 176, 7);">-</span> <span>name</span><span data-style="color: rgb(214, 176, 7);">:</span> push github<span data-style="color: rgb(214, 176, 7);">-</span>contribution<span data-style="color: rgb(214, 176, 7);">-</span>grid<span data-style="color: rgb(214, 176, 7);">-</span>snake.svg to the output branch<br></span><span>        <span>uses</span><span data-style="color: rgb(214, 176, 7);">:</span> crazy<span data-style="color: rgb(214, 176, 7);">-</span>max/ghaction<span data-style="color: rgb(214, 176, 7);">-</span>github<span data-style="color: rgb(214, 176, 7);">-</span>pages@v3.1.0<br></span><span>        <span>with</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>          <span>target_branch</span><span data-style="color: rgb(214, 176, 7);">:</span> output<br></span><span>          <span>build_dir</span><span data-style="color: rgb(214, 176, 7);">:</span> dist<br></span><span>        <span>env</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>          <span>GITHUB_TOKEN</span><span data-style="color: rgb(214, 176, 7);">:</span> $<span data-style="color: rgb(214, 176, 7);">{</span><span data-style="color: rgb(214, 176, 7);">{</span> secrets.GITHUB_TOKEN <span data-style="color: rgb(214, 176, 7);">}</span><span data-style="color: rgb(214, 176, 7);">}</span><br></span></code></pre>
```









将下列代码复制到 Markdown 内，将用户名部分替换成你自己的，并提交。

这段代码的目的是：加载贪吃蛇动画，且贪吃蛇的暗亮风格与你的 Github 的暗亮风格进行自动适配。

```
<section><span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 96, 92);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 189, 68);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(0, 202, 78);"></span></span><span> </span></section><pre data-title="true"><code data-line="641"><span><span><span><span data-style="color: rgb(214, 176, 7);">&lt;</span>picture</span><span data-style="color: rgb(214, 176, 7);">&gt;</span></span><br></span><span>  <span><span><span data-style="color: rgb(214, 176, 7);">&lt;</span>source</span> <span data-style="color: rgb(230, 0, 103);">media</span><span><span data-style="color: rgb(214, 176, 7);">=</span><span data-style="color: rgb(214, 176, 7);">"</span>(prefers-color-scheme: dark)<span data-style="color: rgb(214, 176, 7);">"</span></span> <span data-style="color: rgb(230, 0, 103);">srcset</span><span><span data-style="color: rgb(214, 176, 7);">=</span><span data-style="color: rgb(214, 176, 7);">"</span>https://raw.githubusercontent.com/Peter-JXL/Peter-JXL/output/github-contribution-grid-snake-dark.svg<span data-style="color: rgb(214, 176, 7);">"</span></span><span data-style="color: rgb(214, 176, 7);">&gt;</span></span><br></span><span>  <span><span><span data-style="color: rgb(214, 176, 7);">&lt;</span>source</span> <span data-style="color: rgb(230, 0, 103);">media</span><span><span data-style="color: rgb(214, 176, 7);">=</span><span data-style="color: rgb(214, 176, 7);">"</span>(prefers-color-scheme: light)<span data-style="color: rgb(214, 176, 7);">"</span></span> <span data-style="color: rgb(230, 0, 103);">srcset</span><span><span data-style="color: rgb(214, 176, 7);">=</span><span data-style="color: rgb(214, 176, 7);">"</span>https://raw.githubusercontent.com/Peter-JXL/Peter-JXL/output/github-contribution-grid-snake.svg<span data-style="color: rgb(214, 176, 7);">"</span></span><span data-style="color: rgb(214, 176, 7);">&gt;</span></span><br></span><span>  <span><span><span data-style="color: rgb(214, 176, 7);">&lt;</span>img</span> <span data-style="color: rgb(230, 0, 103);">alt</span><span><span data-style="color: rgb(214, 176, 7);">=</span><span data-style="color: rgb(214, 176, 7);">"</span>github contribution grid snake animation<span data-style="color: rgb(214, 176, 7);">"</span></span> <span data-style="color: rgb(230, 0, 103);">src</span><span><span data-style="color: rgb(214, 176, 7);">=</span><span data-style="color: rgb(214, 176, 7);">"</span>https://raw.githubusercontent.com/Peter-JXL/Peter-JXL/output/github-contribution-grid-snake.svg<span data-style="color: rgb(214, 176, 7);">"</span></span><span data-style="color: rgb(214, 176, 7);">&gt;</span></span><br></span><span><span><span><span data-style="color: rgb(214, 176, 7);">&lt;/</span>picture</span><span data-style="color: rgb(214, 176, 7);">&gt;</span></span><br></span></code></pre>
```



之前我们设置的是每隔 2 小时更新一次，我们可以先手动跑一次。点击 `generate animation`，点击 `Run workflow`：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGogHWQ74VIX6OsFzXatIlUSic6a6xqILCvicLL4XAcBgKx0nE51nib2ogmg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



稍等片刻，显示运行成功，再次回到仓库主页就会看到贪吃蛇动画已被加载：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGodsYMKRsEeYqjAAL1JVxpkAKC0pLrLZsCsibACKvXDmzt2B0OOupy5Bg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)





### 博客文章同步

如果你有博客网站，且网站带有 RSS 功能，就可以配置此功能，它能在你的  GitHub 首页上显示最近更新的博客

原理：利用 blog-post-workflow 在自述文件上展示最近几篇博客文章。

效果：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGoQhwauLAXjCWL0zqOrQFzkuUYM61x9Nn9Pkc0pcN2ugPbXBY3VdSQpQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)





使用起来也很简单。首先创建一个 workflow（例如 `blog-post-workflow.yml` ），需要改动最后一行的 `feed_list` 的内容为你自己网站的 RSS 链接。

```
<section><span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 96, 92);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 189, 68);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(0, 202, 78);"></span></span><span> </span></section><pre data-title="true"><code data-line="695"><span><span>name</span><span data-style="color: rgb(214, 176, 7);">:</span> Latest blog post workflow<br></span><span><span>on</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>  <span>schedule</span><span data-style="color: rgb(214, 176, 7);">:</span> <span># Run workflow automatically</span><br></span><span>    <span data-style="color: rgb(214, 176, 7);">-</span> <span>cron</span><span data-style="color: rgb(214, 176, 7);">:</span> <span data-style="color: rgb(73, 198, 236);">'0 */2 * * *'</span> <span># Runs every hour, on the hour</span><br></span><span>  <span>workflow_dispatch</span><span data-style="color: rgb(214, 176, 7);">:</span> <span># Run workflow manually (without waiting for the cron to be called), through the GitHub Actions Workflow page directly</span><br></span><span><span>permissions</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>  <span>contents</span><span data-style="color: rgb(214, 176, 7);">:</span> write <span># To write the generated contents to the readme</span><br></span><span><br></span><span><span>jobs</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>  <span>update-readme-with-blog</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>    <span>name</span><span data-style="color: rgb(214, 176, 7);">:</span> Update this repo's README with latest blog posts<br></span><span>    <span>runs-on</span><span data-style="color: rgb(214, 176, 7);">:</span> ubuntu<span data-style="color: rgb(214, 176, 7);">-</span>latest<br></span><span>    <span>steps</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>      <span data-style="color: rgb(214, 176, 7);">-</span> <span>name</span><span data-style="color: rgb(214, 176, 7);">:</span> Checkout<br></span><span>        <span>uses</span><span data-style="color: rgb(214, 176, 7);">:</span> actions/checkout@v3<br></span><span>      <span data-style="color: rgb(214, 176, 7);">-</span> <span>name</span><span data-style="color: rgb(214, 176, 7);">:</span> Pull in blog's posts<br></span><span>        <span>uses</span><span data-style="color: rgb(214, 176, 7);">:</span> gautamkrishnar/blog<span data-style="color: rgb(214, 176, 7);">-</span>post<span data-style="color: rgb(214, 176, 7);">-</span>workflow@v1<br></span><span>        <span>with</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>          <span>feed_list</span><span data-style="color: rgb(214, 176, 7);">:</span> <span data-style="color: rgb(73, 198, 236);">"https://www.peterjxl.com/rss.xml"</span><br></span></code></pre>
```

更多构建参数请参考 🔗 github.com/gautamkrishnar/blog-post-workflow，包括显示文章数量、显示主题等等。







然后在自述文件输入这些内容，程序会自动抓取文章标题、链接等并替换这两个注释：

```
<section><span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 96, 92);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 189, 68);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(0, 202, 78);"></span></span><span> </span></section><pre data-title="true"><code data-line="711"><span>📕 <span title="&nbsp;">&amp;nbsp;</span><span><span data-style="color: rgb(214, 176, 7);">**</span><span>Latest Blog Posts</span><span data-style="color: rgb(214, 176, 7);">**</span></span><br></span><span><span>&lt;!-- BLOG-POST-LIST:START --&gt;</span><br></span><span><span>&lt;!-- BLOG-POST-LIST:END --&gt;</span><br></span></code></pre>
```





同理，此时是看不到文章列表的，我们得先手工运行一次 action：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGo6msXXW6C9bJYTWFibGStsQPtic0VNoVzahSFuPp2jdibWPBSickeGWZQTg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)





### 你的 GitHub 故事

GitHub 已经内置了年度提交数统计，方便我们回顾：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGoSnT4vMCgNwEGdiaXtqU1YsJ58RHY3t44VOkgzfDx5HVibwhnzFtBBHLg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



但我们可以更炫酷地用 3D 模型来展示：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGo4uo4QCOibaicYfxaPKwzcsah8eHqKpmrswmiazNeF8nZ0EicqblDicOSFmg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



官网：https://skyline.github.com

用法：输入自己的 GitHub 用户名，和想要查看的年份，i就可以自动生成炫酷的 3D 模型。





PS：

-   这个功能是 GitHub 官方在 2021 年推出的，但是后续又下线了，暂时不知道什么时候回归。
    
-   该网站可以生成 STL 文件，这是用于 3D 立体光刻的文件格式。
    
-   GitHub 本身也是支持查看 3D 文件的，也就是可以托管和渲染 .stl 的 3D 文件
    
-   如果你有 3D 打印机的话，可以通过该文件自己打印出来。或者用线上打印服务 shapeways.com：
    

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGo3yxibProHJZBqh9ggvBW7k1R36wbkhndXV34SEkBFuouDuxdGJaJZlQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



也有不少开发者拿到了打印后的纪念品：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGoiaoAy1ibJnsn5heUBKUtuSibWgud6zPckUuicBibzaZAWqfG8FCoNSZJklQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)





### GitHub 3D 统计

使用 3D 图来展示信息。

官网：github.com/yoshi389111/github-profile-3d-contrib

效果：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGoURCxdPHCGJicVJHdTullHkVCgRKVbFnBia9A7NAgxLvEmC5lOAmMCOog/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)





使用方法是用 GitHub Action。首先创建文件 `.github/workflows/profile-3d.yml`，内容如下：

```
<section><span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 96, 92);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 189, 68);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(0, 202, 78);"></span></span><span> </span></section><pre data-title="true"><code data-line="807"><span><span>name</span><span data-style="color: rgb(214, 176, 7);">:</span> GitHub<span data-style="color: rgb(214, 176, 7);">-</span>Profile<span data-style="color: rgb(214, 176, 7);">-</span>3D<span data-style="color: rgb(214, 176, 7);">-</span>Contrib<br></span><span><br></span><span><span>on</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>  <span>schedule</span><span data-style="color: rgb(214, 176, 7);">:</span> <span># 03:00 JST == 18:00 UTC</span><br></span><span>    <span data-style="color: rgb(214, 176, 7);">-</span> <span>cron</span><span data-style="color: rgb(214, 176, 7);">:</span> <span data-style="color: rgb(73, 198, 236);">"0 18 * * *"</span><br></span><span>  <span>workflow_dispatch</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span><br></span><span><span>jobs</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>  <span>build</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>    <span>runs-on</span><span data-style="color: rgb(214, 176, 7);">:</span> ubuntu<span data-style="color: rgb(214, 176, 7);">-</span>latest<br></span><span>    <span>name</span><span data-style="color: rgb(214, 176, 7);">:</span> generate<span data-style="color: rgb(214, 176, 7);">-</span>github<span data-style="color: rgb(214, 176, 7);">-</span>profile<span data-style="color: rgb(214, 176, 7);">-</span>3d<span data-style="color: rgb(214, 176, 7);">-</span>contrib<br></span><span>    <span>steps</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>      <span data-style="color: rgb(214, 176, 7);">-</span> <span>uses</span><span data-style="color: rgb(214, 176, 7);">:</span> actions/checkout@v3<br></span><span>      <span data-style="color: rgb(214, 176, 7);">-</span> <span>uses</span><span data-style="color: rgb(214, 176, 7);">:</span> yoshi389111/github<span data-style="color: rgb(214, 176, 7);">-</span>profile<span data-style="color: rgb(214, 176, 7);">-</span>3d<span data-style="color: rgb(214, 176, 7);">-</span>contrib@0.7.1<br></span><span>        <span>env</span><span data-style="color: rgb(214, 176, 7);">:</span><br></span><span>          <span>GITHUB_TOKEN</span><span data-style="color: rgb(214, 176, 7);">:</span> $<span data-style="color: rgb(214, 176, 7);">{</span><span data-style="color: rgb(214, 176, 7);">{</span> secrets.GITHUB_TOKEN <span data-style="color: rgb(214, 176, 7);">}</span><span data-style="color: rgb(214, 176, 7);">}</span><br></span><span>          <span>USERNAME</span><span data-style="color: rgb(214, 176, 7);">:</span> $<span data-style="color: rgb(214, 176, 7);">{</span><span data-style="color: rgb(214, 176, 7);">{</span> github.repository_owner <span data-style="color: rgb(214, 176, 7);">}</span><span data-style="color: rgb(214, 176, 7);">}</span><br></span><span>      <span data-style="color: rgb(214, 176, 7);">-</span> <span>name</span><span data-style="color: rgb(214, 176, 7);">:</span> Commit &amp; Push<br></span><span>        <span>run</span><span data-style="color: rgb(214, 176, 7);">:</span> <span data-style="color: rgb(214, 176, 7);">|</span><span data-style="color: rgb(73, 198, 236);"><br></span></span><span><span data-style="color: rgb(73, 198, 236);">          git config user.name github-actions<br></span></span><span><span data-style="color: rgb(73, 198, 236);">          git config user.email github-actions@github.com<br></span></span><span><span data-style="color: rgb(73, 198, 236);">          git add -A .<br></span></span><span><span data-style="color: rgb(73, 198, 236);">          git commit -m "generated"<br></span></span><span><span data-style="color: rgb(73, 198, 236);">          git push</span><br></span></code></pre>
```



然后手动执行一次 action：`Actions` -> `GitHub-Profile-3D-Contrib` -> `Run workflow`

然后会生成这些文件（带路径，各种主题的都有）：

-   `profile-3d-contrib/profile-green-animate.svg`
    
-   `profile-3d-contrib/profile-green.svg`
    
-   `profile-3d-contrib/profile-season-animate.svg`
    
-   `profile-3d-contrib/profile-season.svg`
    
-   `profile-3d-contrib/profile-south-season-animate.svg`
    
-   `profile-3d-contrib/profile-south-season.svg`
    
-   `profile-3d-contrib/profile-night-view.svg`
    
-   `profile-3d-contrib/profile-night-green.svg`
    
-   `profile-3d-contrib/profile-night-rainbow.svg`
    
-   `profile-3d-contrib/profile-gitblock.svg`
    



最后在 Markdown 里添加即可。



PS，如果遇到了这样的报错：

```
<section><span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 96, 92);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(255, 189, 68);"></span><span data-style="display: inline-block; align-items: center; width: 9px; height: 9px; margin-right: 8px; padding: 1px; border-radius: 50%; background-color: rgb(0, 202, 78);"></span></span><span> </span></section><pre data-title="true"><code data-line="838"><span><span>remote</span><span data-style="color: rgb(214, 176, 7);">:</span> Permission to mthsBelloni/mthsBelloni.git denied to github<span data-style="color: rgb(214, 176, 7);">-</span>actions<span data-style="color: rgb(214, 176, 7);">[</span>bot<span data-style="color: rgb(214, 176, 7);">]</span>.<br></span><span><span>fatal</span><span data-style="color: rgb(214, 176, 7);">:</span> <span>unable to access 'https://github.com/Peter-JXL/Peter-JXL/'</span><span data-style="color: rgb(214, 176, 7);">:</span> <span>The requested URL returned error</span><span data-style="color: rgb(214, 176, 7);">:</span> <span>403</span><br></span><span><span>Error</span><span data-style="color: rgb(214, 176, 7);">:</span> Process completed with exit code 128.<br></span></code></pre>
```



大概率是因为没有配置 actions 的写权限，导致无法写入 svg 文件。解决办法：加上权限

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGotribUz2ZnibCH7ZRy2UIMwX12J7XfB4rr9a4xdjI8Id0ibRsIh6UiccRmg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



### 感谢参与者

每位开源项目的参与者都值得记录和感谢，传统方式是手工编辑，项目负责人一个一个地把参与者的名字记录到 README.md，非常低效。

可以使用一种更高效、自动化的方式来添加项目贡献者：

项目名：All Contributors

官网：https://allcontributors.org



可以用命令行或者机器人的方式自动将项目的贡献者补充到项目文档中，并且生成排版精美的表格，效果如下：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGoJibdhbTkTb6AjH5qG9RW6EaLS5M3O5vtvxOzkIU5deTUd7IxgmRHDBg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)







## Profile 编辑器

这个项目是一个是一个可视化 profile 生成工具，使用者无需学习 Markdown 语法，仅需要在对应窗口中输入或者选择相应的内容，工具会自动生成 Markdown 脚本。脚本编辑完成以后，直接复制粘贴到自己的 Github 即可。

官网：profilinator.rishav.dev

效果：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGoA7gnS6TOPUjdutibo5c6sIjpTbbg1s8bE126kDqga7wzPKOTncibHO0w/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)





## 关于 Gitee

很遗憾，Gitee，号称国内版的 GitHub，并没有提供类似的功能。但我们可以完善下个人信息部分：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGoaezlQUVXFrUkQTQ9ponPvTyJHiaSYlQBJpbAYbd0WtnbiatU24JkEylQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)





方法：在个人主页里打开个人设置

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGoicnGVTGCK4w5OXJX4hQLgj04ovicgoia8kZJ6almljhIsLfcgDDeqaCfg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



打开个人资料，可以修改公司，职务，微信，QQ，领英，微博，博客，所在地，自我介绍等信息，多多少少能优化下个人主页：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGoKqicffrQnhEl5SA7WRYE9icWyfNLSKmN3tP1JIumjTibfOt1ZK0wcpZng/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)





例如鱼皮的长这样：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/PdyWzr1ic1ahjKE6zFPjs6JLibMPNHDNGoZrdzCgIzFIPZ01kunNUSrbagSHPsyNCK6PlXoKXN6Q4kTkPnGvArVg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)







## 最后

本文仅仅列出一些常见的功能，感兴趣的同学可以自行搜索更多功能，甚至自定义。

这是我的 GitHub 主页，大家可以抄抄作业（如果能点个 star 就更好了😏）：https://github.com/Peter-JXL

特别注意：由于 GFW 的原因，可能需要魔法上网后才能看到一些内容。

最后，祝你玩得开心！

——完——
