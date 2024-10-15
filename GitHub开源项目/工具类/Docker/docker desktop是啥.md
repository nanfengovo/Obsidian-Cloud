---
created: 2024-10-10T22:31:57 (UTC +08:00)
tags: [docker desktop是啥]
source: https://blog.csdn.net/xyl192960/article/details/120246820
author: 
---

# Docker-desktop(Docker桌面版)——入门篇_docker desktop是啥-CSDN博客

> ## Excerpt
> 文章浏览阅读5.3w次，点赞73次，收藏240次。如果你是docker初学者，或者压根就不知道docker是什么，那你一定要先知道docker是个什么东西，是用来干嘛的。引入百科的解释：Docker 是一个开源的应用容器引擎，让开发者可以打包他们的应用以及依赖包到一个可移植的镜像中，然后发布到任何流行的 Linux或Windows 机器上，也可以实现虚拟化。容器是完全使用沙箱机制，相互之间不会有任何接口。这段话的重点我个人认为是“容器”，那么什么是容器？在我们生活中，容器是杯子用来装水，是碗用来装饭，那么在电脑系统里面的容器是用来装什么的？答案：在_docker desktop是啥

---
## 前言

> 本章内容主要涉及内容：
> 
> 1.  在**Windows10系统**下进行安装和简单使用\*\*Docker-desktop(Docker桌面版)。
> 2.  如果你是docker初学者，或者压根就不知道docker是什么，那你一定要先知道docker是个什么东西，是用来干嘛的。
> 3.  本章内容不是专业性的学术研究，而是近期自己使用学习Docker得到的经验分享。
> 4.  有误的地方可以在评论告知，好让我进行更正。

### 什么是Docker

> **百科**的解释：  
> Docker是一个开源的应用容器引擎，让开发者可以打包他们的应用以及依赖包到一个可移植的容器中，然后发布到任何流行的Linux机器上，也可以实现[虚拟化](https://so.csdn.net/so/search?q=%E8%99%9A%E6%8B%9F%E5%8C%96&spm=1001.2101.3001.7020)。容器是完全使用沙箱机制，相互之间不会有任何接口。

> 简单理解:  
> Docker就是一个虚拟机，可以让你在一个虚拟的，类似于沙盒的环境下进行环境搭建、软件安装、软件使用、程序编码等操作，并且这个环境是**Linux系统**。  
> 实际上：  
> 是在**Linux系统**下的一种**容器**，**容器技术**把一个系统需要的资源划分给一个独立的组(Linux系统下每个组的权限不同，互不干扰)，可以将此看作是一个新的Linux系统，因为它包含了Linux系统所需要的环境。与虚拟机不同的是，虚拟机下的系统是有虚拟硬件的，而Docker内的系统实际上是一个**环境**。

#### 所以Docker是用来干嘛的？

> 1.  Docker可以使用镜像快速的搭建运行程序所需要的环境。
> 2.  节省资源，虚拟机实际是机器，一个“虚拟出的机器”，而 Docker 则是环境，“被限制的使用”，相比较而言 Docker 的内存占用更少，更加轻量级。
> 3.  对于入门来说知道这两点就足够了，其他企业级的作用就自行挖掘把。

### Docker-desktop(桌面版)安装

> 1.搜索Docker官网进入官网，找到[Docker-desktop](https://www.docker.com/products/docker-desktop)的下载链接下载安装包，直接打开安装包进行安装即可(安装前最好**关闭防火墙**)(安装好后重启)。  
> 2.需要手动进入系统**BIOS启用虚拟化技术**，并且在系统启动需要启动**Hyper-V服务**。这是必须手动开启的，不会的话请自行百度查阅教程。  
> 3.系统一定要**Windows10系统(专业版和家庭版都可以)**，win10以下的系统好像暂不支持Docker-desktop(桌面版）  
> 4.其他问题：  
> Docker Desktop启动的时候，有可能提示"WSL2 installations is incomplete"，这是您的系统中没有安装WSL2内核的原因，打开 https://aka.ms/wsl2kernel， 在打开的页面中有一个"适用于x64计算机的WSL2 Linux内核更新包"链接，点击下载，安装。  
> WSL2 Linux内核更新包安装后，重启Docker Desktop即可正常使用。您可在cmd或者PowerShell命令行中使用docker或者docker-compose等相关命令了。  
> PS: 如果您在安装WSL2的过程中遇到了问题，可能是您的系统版本较低等原因，您可按照 https://aka.ms/wsl2wkernel 页面的相关提示更新系统。该Docker Desktop的安装方法基于Windows10的WSL2，如果您的系统没有或者不能安装WSL2，可能不能使用该方法安装Docker Desktop。

### 使用Docker搭建一个Linux系统环境

> 安装好后打开任务栏docker的界面就是这样的，左下角图标显示绿色就表示服务都正常运行。![docker界面](https://i-blog.csdnimg.cn/blog_migrate/e168e464ee4617854b26be5108ccfdaf.png)
> 
> #### 设置镜像加速器
> 
> ![设置镜像加速器](https://i-blog.csdnimg.cn/blog_migrate/5dade238df3dce276c4e422a1ce17c39.png)  
> 国内从 DockerHub 拉取镜像有时会遇到困难，此时可以配置镜像加速器。Docker 官方和国内很多云服务商都提供了国内加速器服务，例如：  
> 科大镜像：https://docker.mirrors.ustc.edu.cn/  
> 网易：https://hub-mirror.c.163.com/  
> 阿里云：https://<你的ID>.mirror.aliyuncs.com  
> 七牛云加速器：https://reg-mirror.qiniu.com  
> 当配置某一个加速器地址之后，若发现拉取不到镜像，请切换到另一个加速器地址。国内各大云服务商均提供了 Docker 镜像加速服务，建议根据运行 Docker 的云平台选择对应的镜像加速服务。  
> 阿里云镜像获取地址：https://cr.console.aliyun.com/cn-hangzhou/instances/mirrors，登陆后，左侧菜单选中镜像加速器就可以看到你的专属地址了
> 
> #### 进入CMD命令行窗口，进行镜像下载拉取
> 
> ##### 镜像搜索
> 
> **命令：**  
> docker search centos 【查找Linux系统镜像】【也可以直接去[DockerHub网站](https://hub.docker.com/)进行搜索】  
> ![查找镜像](https://i-blog.csdnimg.cn/blog_migrate/2067b910c472a34a9c36a9a8498afcb4.png)NAME: 镜像仓库源的名称  
> DESCRIPTION: 镜像的描述  
> OFFICIAL: 是否 docker 官方发布  
> stars: 类似 Github 里面的 star，表示点赞、喜欢的意思。  
> AUTOMATED: 自动构建。
> 
> ##### 镜像下载
> 
> **命令：**  
> docker pull centos  
> 【docker pull 环境】默认是下载latest最新的版本，也可以用【docker pull 环境:版本号】下载指定版本，例如【docker pull mysql:5.7】  
> ![下载镜像](https://i-blog.csdnimg.cn/blog_migrate/193292342b61e3b4081e4c16bfacd2c1.png)
> 
> ##### 使用镜像
> 
> **命令：**  
> docker images  
> 查看所有现有已经拉去下载的镜像  
> ![查看安装的镜像](https://i-blog.csdnimg.cn/blog_migrate/d380e95490df6dba86ed13b655da9c91.png)  
> **命令：**  
> docker run -it centos  
> 使用指定镜像创建一个新的容器  
> 语法：docker run \[OPTIONS\] IMAGE \[COMMAND\] \[ARG…\]  
> OPTIONS说明：  
> \-a stdin: 指定标准输入输出内容类型，可选 STDIN/STDOUT/STDERR 三项；  
> \-d: 后台运行容器，并返回容器ID；  
> \-i: 以交互模式运行容器，通常与 -t 同时使用；  
> \-P: 随机端口映射，容器内部端口随机映射到主机的端口  
> \-p: 指定端口映射，格式为：主机(宿主)端口:容器端口  
> \-t: 为容器重新分配一个伪输入终端，通常与 -i 同时使用；  
> –name=“nginx-lb”: 为容器指定一个名称；  
> –dns 8.8.8.8: 指定容器使用的DNS服务器，默认和宿主一致；  
> –dns-search example.com: 指定容器DNS搜索域名，默认和宿主一致；  
> \-h “mars”: 指定容器的hostname；  
> \-e username=“ritchie”: 设置环境变量；  
> –env-file=\[\]: 从指定文件读入环境变量；  
> –cpuset=“0-2” or --cpuset=“0,1,2”: 绑定容器到指定CPU运行；  
> \-m :设置容器使用内存最大值；  
> –net=“bridge”: 指定容器的网络连接类型，支持 bridge/host/none/container: 四种类型；  
> –link=\[\]: 添加链接到另一个容器；  
> –expose=\[\]: 开放一个端口或一组端口；  
> –volume , -v: 绑定一个卷  
> ![linux容器](https://i-blog.csdnimg.cn/blog_migrate/51c678b66882c4e9f5733529d857ab34.png)

### END

> Docker的安装和简单使用到这里就结束了  
> 而Docker还有其他很多的操作，比如：  
> 容器的删除、容器状态的查看、镜像的删除，或者是镜像的构建，集群管理、仓库管理、容器之间的网络连接等详细内容可以去自行查找资料学习。  
> [菜鸟教程](https://www.runoob.com/docker/docker-tutorial.html)  
> [动力节点](http://www.bjpowernode.com/docker/)
