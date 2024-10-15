---
created: 2024-10-14T22:27:25 (UTC +08:00)
tags: []
source: https://mp.weixin.qq.com/s/dJujpTG1v3q1EuGQNe4hcg
author: Code潮栈
---

# 10分钟搞定！Hexo个人博客搭建全攻略 + 最美Fluid主题配置

> ## Excerpt
> Hexo 是一个基于 Node.js 的快速、简洁且功能强大的静态博客框架，适合那些想要搭建个人博客的人使用。它通过 Markdown 文件生成静态页面，并且可以方便地部署到 GitHub Pages、Vercel、Netlify 等静态托管平台。下面我将详细介绍 Hexo 的搭建及使用教程。

---
**点击蓝字**

**关注**

Hexo 是一个基于 Node.js 的快速、简洁且功能强大的静态博客框架，适合那些想要搭建个人博客的人使用。它通过 Markdown 文件生成静态页面，并且可以方便地部署到 GitHub Pages、Vercel、Netlify 等静态托管平台。下面我将详细介绍 Hexo 的搭建及使用教程。

### 在开始之前，带大家看一些成品

、、

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/mRUWxjff2F14ibeKxZg3pbrgqFyySbGvNtXibj3eu5RsUGicaI58CvgGIFdJHibvaY8dMibrVCkicpBFBnsn2Y9oX6tw/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/mRUWxjff2F14ibeKxZg3pbrgqFyySbGvNWAHDp6CN4lhgfQRyqE16KZhNpmNlem4wC4aRAzsCzthpibP5u7IznNA/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/mRUWxjff2F14ibeKxZg3pbrgqFyySbGvN46gJvZEM9f8vygh2IldOFPoeXOicveOiciaO3DC2GJN9Ywu4GmfYqhmIw/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/mRUWxjff2F14ibeKxZg3pbrgqFyySbGvNUwmiagkJMNia1gMRFNicGU79QaDIb2qrjicHFhic4cJicbTLX5xRkzYxLe4w/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

![图片](https://mmbiz.qpic.cn/sz_mmbiz_jpg/mRUWxjff2F14ibeKxZg3pbrgqFyySbGvNjH7rxAITVZf3ShO7NRSQpAZjK8icw8NMLqPqd4zKe2iaMk3oRUGJy8pg/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/mRUWxjff2F14ibeKxZg3pbrgqFyySbGvN5a0DZylaBRlBaAmibsTvh0emKBNnZS1QgsZTSjGK5SweMFjC3XDBYCQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

![图片](https://mmbiz.qpic.cn/sz_mmbiz_jpg/mRUWxjff2F14ibeKxZg3pbrgqFyySbGvNa9W5iaTukPFUeMgDjyPo60jeJXL2EPXojGqoCaREpiahpTEcH9ecELAQ/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

### 一、准备环境

1.  **安装NodeJs**
    

> nodejs安装和环境配置-Windows  （可以翻看下一篇NodeJs 详细奖讲解）

按照上面的流程安装完成后检测是否安装成功

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/mRUWxjff2F14ibeKxZg3pbrgqFyySbGvNCk2qPlibj2ZIVg1Yfia3iazIYpQnmNLhUyB3pFs6ovSl2op3bCBdMoZdw/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

**2.  安装Git**

> Git 详细安装教程  （可以翻看下一篇Git 详细奖讲解）

按照上面的流程安装完成后检测是否安装成功

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/mRUWxjff2F14ibeKxZg3pbrgqFyySbGvNW9wZeLh1uAzGCmicOGfuWNMl7N2g6mSaiaoIAiaapyZzVRiagibyibNXusxA/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

**3.  安装Hexo**

> 在Windows搜索栏搜索cmd，找到命令提示符，右键，选择以管理员身份运行

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/mRUWxjff2F14ibeKxZg3pbrgqFyySbGvNpewKIOOUMonvNoGRaANuSic3XDj0oUzzLpK7gkWsmxSaHYJD0ob90jQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

> 输入命令安装Hexo：`npm install -g hexo`

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/mRUWxjff2F14ibeKxZg3pbrgqFyySbGvNGC9sfET8FLvxYP1ZjicWB52lK5ia0VN1Ymefia1IIKbheUNdWAD66licjg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

> 输入命令，查看hexo是否安装成功：`hexo -v`

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/mRUWxjff2F14ibeKxZg3pbrgqFyySbGvNk6ttGCib1JB4tG2j5hYdvCsZh5IVZZgxvSRYb0iaDCIwjSBkLcI8bkAw/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

**4.  初始化Hexo**

```
$&nbsp;hexo&nbsp;init&nbsp;文件夹名<br>$&nbsp;cd&nbsp;文件夹名<br>$&nbsp;npm&nbsp;install
```

会生成很多文件夹，看不懂没关系，知道怎么配置就可以了。

-   • node\_modules: 依赖包
    
-   • public：存放生成的页面
    
-   • scaffolds：生成文章的一些模板
    
-   • source：用来存放你的文章
    
-   • themes：主题
    
-   • \_config.yml: 博客的配置文件
    

**5.  启动Hexo**

```
#&nbsp;每次更改数据后都要执行下面三个命令<br>#&nbsp;清除缓存文件<br>hexo&nbsp;clean<br>#&nbsp;生成静态文件&nbsp;可简写为&nbsp;hexo&nbsp;g<br>hexo&nbsp;generate&nbsp;&nbsp;&nbsp;<br>#&nbsp;启动服务器&nbsp;可简写为&nbsp;hexo&nbsp;s<br>hexo&nbsp;server
```

在浏览器中输入 localhost:4000 就可以看到生成的博客页面了ctrl + c 可以关掉服务

![图片](https://mmbiz.qpic.cn/sz_mmbiz_jpg/mRUWxjff2F14ibeKxZg3pbrgqFyySbGvNWvgTYEiccKd2z1paOmoKPtT2XJHYrFGTBKQUVbNRXR3jPze4yohCfqQ/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

### 二、更换Fluid 主题

> 以管理员身份运行命令提示符，切换当前目录到 myblog 目录，然后输入命令：`npm install --save hexo-theme-fluid`

![图片](https://mmbiz.qpic.cn/sz_mmbiz_jpg/mRUWxjff2F14ibeKxZg3pbrgqFyySbGvNWCb0GLibcOu1C2lkClXT0fZ3gcGhFSH2VFiajzB5e76evrhqzDZoxAiaA/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

> 修改 myblog 目录下的配置文件，修改主题为：`theme: fluid`

![图片](https://mmbiz.qpic.cn/sz_mmbiz_jpg/mRUWxjff2F14ibeKxZg3pbrgqFyySbGvNzB8W71zrUibeoiaIjuv3hHpQ4RWwMTBHcnGhlACqIk1FwPQQlXnCn0Xg/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

![图片](https://mmbiz.qpic.cn/sz_mmbiz_jpg/mRUWxjff2F14ibeKxZg3pbrgqFyySbGvN10iciaD6YbrS92xR0XdMcIX1mricxy5DGUA1CFxhcv6zwSI8s8El7mlgw/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

> 在 myblog 目录下新建一个文件，命名为 `_config.fluid.yml` , 只要存在于 `_config.fluid.yml` 的配置都是高优先级，修改原 `_config.yml` 是无效的。以后我们就对 `_config.fluid.yml` 进行修改即可。

![图片](https://mmbiz.qpic.cn/sz_mmbiz_jpg/mRUWxjff2F14ibeKxZg3pbrgqFyySbGvNvzicZW6yHV7iahrOg4UYzicCHwaJ8tIcA4sF592bdGrEOnibE69kTfS5fg/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

> 输入命令：`hexo clean` 和 `hexo g`

![图片](https://mmbiz.qpic.cn/sz_mmbiz_jpg/mRUWxjff2F14ibeKxZg3pbrgqFyySbGvNL3wMrma54rbpnWUw1YcGXxy6xbHib7K2Dp4Gw9qwxYX9U6rpgyE5FGA/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

> 输入命令：`hexo s`，重新启动 Hexo

![图片](https://mmbiz.qpic.cn/sz_mmbiz_jpg/mRUWxjff2F14ibeKxZg3pbrgqFyySbGvNXFnYugpaUT3VuSXDgty8vPueYO9w89YN32ZMJ2ibxTS2k4ahslhRbnQ/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

> 然后进入 `http://localhost:4000/` 就可以看到 Fluid 主题已经切换了

![图片](https://mmbiz.qpic.cn/sz_mmbiz_jpg/mRUWxjff2F14ibeKxZg3pbrgqFyySbGvNJL2MXZuoGzl49FjadYribWPwKNgd3fqoc5bADlQDa9bFFMj2bfEBQyg/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

### 三、全局主题配置

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/mRUWxjff2F14ibeKxZg3pbrgqFyySbGvNuX2bRQg1lKzjSuibRVhf7NfGBzLHLTOOprwuLqxKot3stu50XpBoRicA/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

```
//配置手册 地址<br>
```

### 四、创建GitHub仓库

1.首先，你先要有一个GitHub账户，去注册一个吧。

2.注册完登录后，在GitHub.com中看到一个New repository，新建仓库。

3.创建一个和你用户名相同的仓库，后面加.github.io，只有这样，将来要部署到GitHub page的时候，才会被识别，也就是xxxx.github.io，其中xxx就是你注册GitHub的用户名。我github用户名是lch2021，所以我的叫lch2021.github.io

### 五、生成 SSH 添加到 github 仓库

由于后续都是通过 SSH 进行仓库代码的快速部署，所以这一步很有必要，如果之前有在你的电脑本地进行过你的 github 仓库的 SSH 绑定，那此步可跳过  
这时在终端中打开，我是用的Git bash  

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/mRUWxjff2F14ibeKxZg3pbrgqFyySbGvNibZe2e0OJNxHHQic6XTrJWUrvzygjWiaDibXGlbGibR40n9vNgkMQek6Xmg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

```
git&nbsp;config&nbsp;--global&nbsp;user.name&nbsp;"yourname"<br>git&nbsp;config&nbsp;--global&nbsp;user.email&nbsp;"youremail"
```

这里的yourname输入你的GitHub用户名，youremail输入你GitHub的邮箱。这样GitHub才能知道你是不是对应它的账户。  
可以用以下两条，检查一下你有没有输对  

```
git&nbsp;config&nbsp;user.name<br>git&nbsp;config&nbsp;user.email
```

然后创建SSH,一路回车

```
ssh-keygen&nbsp;-t&nbsp;rsa&nbsp;-C&nbsp;"youremail"
```

这个时候它会告诉你已经生成了.ssh的文件夹。在你的电脑中找到这个文件夹。  

SSH，简单来说，就是一种安全秘钥机制。这里面，id\_rsa 是你电脑上的私钥，必须严格保密，不能分享给他人；而 id\_rsa.pub 是公共秘钥，你可以自由分享。将这个公钥添加到 GitHub 上后，当你尝试连接到自己的 GitHub 账户时，GitHub 会使用公钥来匹配你的私钥。只有在这两个

秘钥能够成功匹配时，你才能顺利地通过 Git 将文件上传到 GitHub。  

而后在 github 的 setting 中，找到 SSH keys 的设置选项，点击 New SSH key 把你的 id\_rsa.pub 里面的信息复制进去。

之后，在 gitbash 中输入以下指令，查看是否 SSH 是否已绑定成功

```
ssh&nbsp;-T&nbsp;git@github.com
```

### 六、将Hexo 部署到GitHub

接下来，我们需要将 Hexo 与 GitHub 关联，以便将生成的文章部署到 GitHub 上。首先，打开站点的配置文件 \_config.yml，向下滚动到文件底部，然后将 lch2021 替换为你的 GitHub 账户用户名。完成这个设置后，你就可以顺利地将内容发布到你的 GitHub 账户了。

```
deploy:<br>&nbsp;&nbsp;type:&nbsp;git<br>&nbsp;&nbsp;repo:&nbsp;git@github.com:lch2021/lch2021.github.io.github.io.git<br>&nbsp;&nbsp;branch:&nbsp;master
```

修改完配置文件 \_config.yml 并保存后，回到 gitbash

这个时候需要先安装deploy-git ，也就是部署的命令,这样你才能用命令部署到GitHub。

```
npm&nbsp;install&nbsp;hexo-deployer-git&nbsp;--save
```

然后进行部署

```
hexo&nbsp;clean<br>hexo&nbsp;generate<br>hexo&nbsp;deploy
```

使用 hexo clean 命令可以清除之前生成的文件。

接着，使用 hexo generate（也可以用 hexo g 缩写）来生成静态文章。

要部署文章，可以使用 hexo deploy，同样也可以用 hexo d 缩写。

请注意，在部署时，可能会要求你输入用户名和密码，但如果已经设置了 SSH，一般情况下是无需输入的。

如果一切顺利，你会看到部署成功的提示。过一段时间后，你就可以在 http://你的用户名.github.io 访问到你的博客了！

![图片](https://mmbiz.qpic.cn/sz_mmbiz_jpg/mRUWxjff2F14ibeKxZg3pbrgqFyySbGvN0icusoJkYy6DWgJBiaYYibE5icXGxJ6bwlsfYJg0iasjyNCIC3qdTX29wEw/640?wx_fmt=jpeg&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

### 结语

希望通过本文的介绍，能够让你学会使用 Hexo 搭建个人博客，配置 Fluid 主题。无论你是技术博主，还是生活记录者，Hexo + Fluid 的组合都能让你的博客更加专业、个性化。希望通过这次教程，能够让你快速搭建出自己满意的博客，并且在日常使用中不断优化与更新，享受写作和分享的乐趣。  

![图片](https://mmbiz.qpic.cn/sz_mmbiz_gif/mRUWxjff2F0vnDuI4WRjGtSM97Lg5JkmHlhaZJQIzY8795m8ibqIic8h1Hl6lA9GfdQZqBzcb5OxRicjtK81tWUFw/640?wx_fmt=gif&from=appmsg&wxfrom=5&wx_lazy=1&wx_co=1&tp=webp "1565150035434158.gif")

[

挑战极限！用 Vue Mini 实现媲美原生的性能

2024-09-25

![图片](https://mmbiz.qpic.cn/sz_mmbiz_jpg/mRUWxjff2F25joJOeUpZ1bofnjW8Nic2p7ueaGIiaXRHObRc0JXhiaAALdP5PekKNbobibGzKFvgHrGFK33hCqL51A/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

](http://mp.weixin.qq.com/s?__biz=Mzk0MjY5MjI1OQ==&mid=2247486304&idx=1&sn=644654d54884643d21c1d4777df56544&chksm=c33e09acf44980ba231d4744eef4620f798d5894ea72ef89ac46c49bd13acfa8c4cf1d191c55&scene=21#wechat_redirect)

[

深入解析 Three.js 与前端开发的结合：从 3D 模型展示到互动场景构建

2024-09-26

![图片](https://mmbiz.qpic.cn/sz_mmbiz_jpg/mRUWxjff2F2fpiaSAnKH6kGpzJ2qp7rRHR4mT5nRIam0LIUDADicsyica2RKkj66jQZPicWMCCnyoyPUO7icqaxn2pA/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

](http://mp.weixin.qq.com/s?__biz=Mzk0MjY5MjI1OQ==&mid=2247486333&idx=1&sn=91bf137f8c08b4035ba85c4ead56714b&chksm=c33e09b1f44980a7434febe781ba46b04721dd4cd3008bdaecaa86b4c4bbc6de35378d14dda2&scene=21#wechat_redirect)

[

构建高效管理系统：Vue3 Composition Admin 的优势

2024-09-23

![图片](https://mmbiz.qpic.cn/sz_mmbiz_jpg/mRUWxjff2F3pPROxrORzicWBcP6HPClibmt90VINORge35nPluDsSDtYAHRSq8AIo8jP84wfsEUPdutJ5VL22OJg/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

](http://mp.weixin.qq.com/s?__biz=Mzk0MjY5MjI1OQ==&mid=2247486252&idx=1&sn=f854470a5f6929392f06e591558d21d5&chksm=c33e09e0f44980f65c7ab5221274576882126c8fcd5e66ef35523c286225b834dabc05c2601b&scene=21#wechat_redirect)

[

用 jjche-boot 打造跨平台应用，简化开发流程！

2024-09-20

![图片](https://mmbiz.qpic.cn/sz_mmbiz_jpg/mRUWxjff2F0u7zytgeibcXFYIxnCCibnmJN5IBTw5yfGicVjib8Ikpy9SBL1iaF8z4zibwaHaEwjiaDxxltNsarzrZAXw/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

](http://mp.weixin.qq.com/s?__biz=Mzk0MjY5MjI1OQ==&mid=2247486202&idx=1&sn=5f9f32939393cba01533e86cf289d8ca&chksm=c33e0836f4498120a9c3147593977119dfdd442dbf8ee3e2f4d566f6bcd77a22a23ef8a629a8&scene=21#wechat_redirect)

**END**

![图片](https://mmbiz.qpic.cn/sz_mmbiz_jpg/mRUWxjff2F0vnDuI4WRjGtSM97Lg5JkmtHrcPExRWwgG5o8ZJUGqVAqmIUOoG83PGbu0fLqXMXaSuZ7HzgAN9g/640?wx_fmt=other&from=appmsg&random=0.5668546881873968&wxfrom=5&wx_lazy=1&wx_co=1&tp=webp)

**Code潮栈  
**

扫描二维码关注我

欢迎关注我的公众号“**Code潮栈**”

原创技术文章第一时间推送，**关注**，**点赞**和**在****看**就是最大的支持❤️
