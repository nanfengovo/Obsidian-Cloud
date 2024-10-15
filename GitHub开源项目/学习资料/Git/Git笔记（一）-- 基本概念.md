---
created: 2024-10-14T22:13:20 (UTC +08:00)
tags: []
source: https://mp.weixin.qq.com/s/SUvj1U4uNhjPZyuEfLhEsw
author: 可乐米001
---

# Git笔记（一）-- 基本概念

> ## Excerpt
> 本文介绍了Git的基本概念、安装、基本配置等知识

---
Git是每个开发人员必备的知识，在本系列中，我们将学习如何使用Git，并与他人进行有效合作。我们将首先学习基本概念，比如什么是Git，如何安装和配置它。然后逐渐探索不同的Git工具，我们将介绍创建代码快照，浏览项目历史记录，分支与合并，使用Github协作，重写历史记录等。

___

**什么是Git**

什么是Git，为什么它如此流行？

Git是世界上最流行的版本控制系统。版本控制系统将代码随时间所做的更改记录在一个名为存储库(Repository)的特殊数据库中，我们可以查看我们的项目历史记录(History)，看看谁在何时以及为什么做了哪些更改。如果我们搞砸了什么，可以轻松地将项目恢复到较早的状态。

![图片](https://mmbiz.qpic.cn/mmbiz_jpg/KchIzjpiatYdAAesgX8gVPI40AhXEqXV2Lwr5VIvgYlgmgetNicpC5QqQCLGXKLVOfyicCFNklI0bvsqblQGjpaHg/640?wx_fmt=jpeg&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

如果没有版本控制，我们必须不断将整个项目的副本存储在各个文件夹中，这非常慢并且根本无法扩展。特别是多个人在同一个项目上工作，您将不得不通过电子邮件或某些机制不断处理最新代码。

![图片](https://mmbiz.qpic.cn/mmbiz_jpg/KchIzjpiatYdAAesgX8gVPI40AhXEqXV2qfNq1r9DzDgR9Zj6r9IpkorOBDrEEsxvvoBwqtsNT9uibIaYTf5EJAA/640?wx_fmt=jpeg&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

然后手动合并更改。

![图片](https://mmbiz.qpic.cn/mmbiz_jpg/KchIzjpiatYdAAesgX8gVPI40AhXEqXV2N4a77nE3pBtn7pTW7gnPVSBjl9jnRibCAZKhlYlZQvfPElswtXP7sOw/640?wx_fmt=jpeg&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

显然，手动控制版本效率很低。  

简而言之，使用版本控制系统，我们可以跟踪我们的项目历史记录，并协同工作。

版本控制系统分两类：集中式和分布式。

集中式控制下，所有团队成员与中心服务器连接获取最新的代码拷贝，并将修改与其他成员分享。Subversion和微软的Team Foundation Server就是集中式版本控制系统的典型例子。它的主要要问题是单点故障，如果中心节点离线，项目成员就无法协同以及保存快照，必须等待服务器恢复在线。![图片](https://mmbiz.qpic.cn/mmbiz_jpg/KchIzjpiatYdAAesgX8gVPI40AhXEqXV231Qaz3Nd1kEdr4uSQqibac6hORs6EOM2QKpiamPE1FEFmDAlt09eWTbw/640?wx_fmt=jpeg&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)  

分布式版本控制系统没有这个问题。每一个团队成员都在他们自己的设备上持有项目的一份拷贝及其历史版本，所以能够本地保存快照。如果中心服务器离线，我们能够直接与其他人进行同步。Git和Mercurial是分布式版本控制的典型例子。Git是世界上最流行的分布式版本控制系统，因为它免费、开源、速度快、可扩展。

![图片](https://mmbiz.qpic.cn/mmbiz_jpg/KchIzjpiatYdAAesgX8gVPI40AhXEqXV2ibs0xc78q8ibd3Ia2XkJtjicqTPVoGd1ocWnyUHkr1kwJwYZibmqpuN6Og/640?wx_fmt=jpeg&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

在其他版本控制系统（如 subversion 或 tfs）中，分支和合并等操作缓慢而痛苦，但在 git 中它们非常快，我们以后会讨论这个问题。

所以 git 几乎无处不在，世界上90%的软件项目在使用 git。如果你正在寻求软件开发的工作，git 是你简历中必须具备的技能之一。你应该彻底了解它，知道它是如何工作的，以及如何使用它来跟踪你的项目历史并与他人有效地合作。

___

**使用Git**

使用Git有多种方式。

命令行。这是最快的方式，有时候是最容易的方式，很多人都用命令行的方法。

代码编辑器内置的方式。VSCode等集成开发环境内置了Git的基本功能，或使用插件，比如gitlens。  

图形工具。比如GitKraken、Sourcetree。GitKraken可以支持不同的平台，开源版免费，商业版需要支付年费。Sourcetree是完全免费的，但只支持Windows和Mac。

大部分时间我们将使用命令行方式。因为几乎所有图形工具都有些限制，即便你就想使用图形工具，但有些时候您不得不回来使用命令行。另一个原因是命令行始终可用，但在某些情况下您可能无法使用 GUI 工具，比如您远程连接到服务器，但没有安装 GUI 工具的权限，如果您不知道如何使用命令行，那就会不知所措。  

实际上，很多人都同时使用命令行和 GUI 工具。

___

**安装Git**

检查本机有没有安装Git，打开命令行工具，输入：  

git --version

如果能看到Git的版本信息，说明已经安装。  

访问https://git-scm.com，升级或新安装Git。

在Windows环境下，Git会添加一个Git Bash，它模拟Linux命令行。所以一般而言，在Windows环境下使用Git，尽量使用Git Bash，而不是内置的命令提示窗口。

___

**配置Git**

在使用Git前首先得做些配置，比如姓名、电子邮件、默认的编辑器，以及如何处理行末。我们可以在三个不同的级别进行配置。  

最高级别是系统级别，该级别的配置应用到当前电脑的所有用户；下一级是全局级别，它应用到当前用户的所有存储库；然后是本地(local)级别，它仅应用于当前的存储库或者说是当前文件夹的存储库，利用该级别，我们可以设置不同存储库分别有不同的配置。

![图片](https://mmbiz.qpic.cn/mmbiz_jpg/KchIzjpiatYdRfrlZANthvJibBOQ3Ww0htV7fHZdVeLu6GQKMPHqpEJurADMuxbtZMzibLxU69l2nBl36cShleAmA/640?wx_fmt=jpeg&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

看一下实际配置。

git config --global user.name "kele mi"

git config --global user.email kelemi001@gmail.com

如上，我们全局配置了Git的用户姓名和电子邮件。姓名中间有空格，我们加了双引号，没有空格的电子邮件，则不必加双引号。

默认情况下，Mac下的git编辑器是vim，我们设置为vscode。您当然可以使用您喜欢的任何编辑器。  

如果您的电脑尚未安装vscode，访问https://code.visualstudio.com下载安装，并打开命令行工具，输入：code，确认vscode会打开，说明环境变量中关于vscode的路径配置正确。

配置vscode为我们Git的编辑器。  

git config --global core.editor "code --wait"

所有的配置都被写入了一个文本文件，用命令 -e 查看。

git config --global -e

默认的编辑器就打开了该配置文件，通常是用户目录的.gitconfig文件。

![图片](https://mmbiz.qpic.cn/mmbiz_jpg/KchIzjpiatYdRfrlZANthvJibBOQ3Ww0ht6uoZibIDxfOTLlYZiczNnfQnnZJnSs4Lnkick7y8gga9gSia0FPSSpFo8A/640?wx_fmt=jpeg&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

下面我们来配置行末设置，这个其实很重要，很多人忽略了。

对于Windows系统，换行使用 “回车+换行”两个字符 \\r\\n，而Mac系统和Linux系统中，只有换行符 \\n。如果我们不做设置，而项目的团队成员同时有使用Windows系统和Mac系统的话，将会出现一些奇怪的问题。  

这个配置是 core.authcrlf。那如何设置呢？

在Windows系统中，设置成true。当我们签入存储库时，Git自动去除回车符，仅将换行符签入；当签出时，则自动加上回车符。

在MacOS系统或Linux系统中，设置成input。只有在签入(input)时，才将可能误添加的回车符去除，而在签出时不做任何修改。

![图片](https://mmbiz.qpic.cn/mmbiz_jpg/KchIzjpiatYdRfrlZANthvJibBOQ3Ww0htu3jx0lrn51HiayKHZK4qWmJNtYYia8Rp1oBb4ESEicia02NianohLC5aic6A/640?wx_fmt=jpeg&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

当前的系统是MacOS，所以配置成input。

git config --global core.autocrlf input

Git的配置有很多，如果您想了解更多，可以用谷歌搜索：git config，也可以使用命令查询：  

git config --help

或者

git config -h

___

**小结**

本文介绍了Git的基本概念，比如什么是Git，如何安装、配置等知识。下一篇开始介绍快照的创建。
