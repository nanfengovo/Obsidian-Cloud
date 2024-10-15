---
created: 2024-10-09T10:43:37 (UTC +08:00)
tags: []
source: https://mp.weixin.qq.com/s/TK2ez3Qf5HF7I7QtBvCUcA
author: 诚哥看开源
---

# 每月 GitHub 探索 ｜ 对开发有帮助的精选开源项目

> ## Excerpt
> 本月精选开源项目包括：dokku、Kamal、Sigma、LLM、MetaMask、AI路线图、Ghost、LangChain4j。这些项目涵盖 PaaS、部署、日志检测、大型语言模型、浏览器扩展、AI学习、出版平台、LLM 集成等多...

---
![图片](https://mmbiz.qpic.cn/mmbiz_gif/bL2iaicTYdZn4WjxEos6UL2LJsTlwqC6diapaqeWs5eyDOuD2icc6WcTjlQj3VQWGNr8QapbnBrMQLSDC2siaEYyGSw/640?wx_fmt=gif&tp=webp&wxfrom=5&wx_lazy=1)

> 本月精选开源项目包括：dokku、Kamal、Sigma、LLM、MetaMask、AI路线图、Ghost、LangChain4j。这些项目涵盖 PaaS、部署、日志检测、大型语言模型、浏览器扩展、AI学习、出版平台、LLM 集成等多个领域，为开发人员提供了一系列实用的工具和资源。

1.dokku：一款由 Docker 驱动的 PaaS

![图片](https://mmbiz.qpic.cn/mmbiz_jpg/asU9BglPP50LGbDTIshwFFgLP9FXPRU9KwticQyMMJ09W2fDVA4ABfQbd6s3eveJk2Lky5hmaDVRrqM3pguYyfQ/640?from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

🏷️仓库名称：**dokku/dokku**  
🌟截止发稿星数: **28898** (近一个月新增:2353)  
🇨🇳仓库语言: **Shell**  
🤝仓库开源协议：**MIT License**  
🔗仓库地址：**https://github.com/dokku/dokku**  

### 引言

> dokku 被誉为“最小的 PaaS 实现”，它是一款由 Docker 提供支持的迷你 Heroku，用于构建和管理应用程序的生命周期。

### 仓库描述

dokku 仓库包含以下主要组件：

-   安装脚本
    
-   用户指南
    
-   贡献指南
    
-   维护脚本
    

### 案例

dokku 已被广泛用于小团队和个人开发人员来部署和管理各种应用程序，包括 Web 应用、API 和微服务。

### 客观评测或分析

dokku 的主要优势包括：

-   **易于使用：**安装和配置简单，无需深入了解 Docker 或 Kubernetes
    
-   **轻量级：**资源消耗低，可以在小服务器或云实例上运行
    
-   **高度可定制：**允许开发人员根据需要定制应用程序环境
    

### 使用建议

在使用 dokku 之前，建议开发人员：

-   熟悉 Docker 和容器化概念
    
-   拥有基本的 Linux 命令行知识
    
-   为应用程序创建 SSH 密钥对
    

### 结论

dokku 是一款强大的 PaaS 工具，为开发人员提供了在云中快速部署和管理应用程序的便捷方法。其轻量级、易用性和可定制性使其成为个人和小型团队的理想选择。

2.Kamal：无缝部署 Web 应用

![图片](https://mmbiz.qpic.cn/mmbiz_jpg/asU9BglPP50LGbDTIshwFFgLP9FXPRU9LE1DUlkvozuGSAjN1x7abbhibWkTnR32d0AXUhmLib99H5Lpvic8tbfBQ/640?from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

🏷️仓库名称：**basecamp/kamal**  
🌟截止发稿星数: **10235** (近一个月新增:684)  
🇨🇳仓库语言: **Ruby**  
🤝仓库开源协议：**MIT License**  
🔗仓库地址：**https://github.com/basecamp/kamal**  

### 引言

> Kamal 是一款功能强大的部署工具，可在物理服务器到云端虚拟机等各种环境中无缝部署 Web 应用，且无需停机时间。本文概述了 Kamal 的主要功能、部署场景和应用建议。

### 项目作用

Kamal 最初专为 Rails 应用而设计，但也适用于采用容器部署的任何 Web 应用类型。它通过 kamal-proxy 无缝切换容器之间的请求，并在后台管理容器生命周期。

### 仓库描述

Kamal 是一个开放源代码项目，持有 MIT 许可证，所有文档都托管在 the basecamp/kamal-site 存储库中。

### 客观评测或分析

Kamal 因其无缝部署、跨服务器协作和对各种 Web 应用类型的兼容性而受到用户的赞誉。它已被广泛应用于不同规模的项目中。

### 使用建议

Kamal 提供全面而深入的文档指导，涵盖了安装、配置和命令。它建议用户参考 kamal-deploy.org 了解更多信息。

### 结论

Kamal 是一款功能强大的部署工具，可满足各种 Web 应用部署需求。它提供的无缝切换、零停机时间和多服务器支持使其成为现代 Web 开发环境中的宝贵资产。

3.Sigma：日志检测规则通用格式

![图片](https://mmbiz.qpic.cn/mmbiz_png/asU9BglPP50LGbDTIshwFFgLP9FXPRU9bFsBYA7GP7GqDanA3nve2pBFNmyfuG4WsKl2dmKLr9adS1VzubiaKag/640?from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)![图片](https://mmbiz.qpic.cn/mmbiz_png/asU9BglPP50LGbDTIshwFFgLP9FXPRU9zslB4uYQRiaQtqONGUFybHuEgmOKSOCafxZEh5KTYxyclu0WSXXibUEA/640?from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

🏷️仓库名称：**SigmaHQ/sigma**  
🌟截止发稿星数: **8175** (近一个月新增:155)  
🇨🇳仓库语言: **Python**  
🤝仓库开源协议：**Other**  
🔗仓库地址：**https://github.com/SigmaHQ/sigma**  

### 引言

> Sigma 是一种用于描述日志事件的开源签名格式，可获得更可靠的检测结果。它提供了 3000 多个不同类型的检测规则，旨在帮助安全人员更轻松地进行威胁检测。

### 项目作用

Sigma 使用 YAML 文件格式来定义规则，并提供清晰简洁的规则编写指南。

### 仓库描述

此存储库包含：

-   通用检测规则
    
-   威胁狩猎规则
    
-   新兴威胁规则
    

### 案例

Sigma 已集成到广泛的安全工具中，包括 IBM QRadar、Splunk 和 SIEM。

### 结论

Sigma 是一款功能强大的开源项目，提供了一个社区驱动的平台，用于协作和共享检测规则。它使安全人员能够更轻松地检测响应威胁，从而提高了组织的整体安全态势。

4.LLM：通过命令行访问大型语言模型

![图片](https://mmbiz.qpic.cn/mmbiz_jpg/asU9BglPP50LGbDTIshwFFgLP9FXPRU9j8mLKuYYmRLOyG3uCVRgEZEuuyG0nlYhI2ibBfuA77VeyWeMu9GzUaw/640?from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

🏷️仓库名称：**simonw/llm**  
🌟截止发稿星数: **4278** (近一个月新增:501)  
🇨🇳仓库语言: **Python**  
🤝仓库开源协议：**Apache License 2.0**  
🔗仓库地址：**https://github.com/simonw/llm**  

### 引言

> LLM是一个命令行工具和Python库，用于与大型语言模型（LLM）进行交互，无论它们是通过远程API访问的，还是可以在您自己的机器上安装和运行的模型。

### 仓库描述

LLM插件目录提供对远程和本地模型的访问。

### 结论

LLM为使用LLM提供了一个方便且功能强大的界面，无论是通过远程API还是在本地运行。

5.MetaMask GitHub 代码库

![图片](https://mmbiz.qpic.cn/mmbiz_png/asU9BglPP50LGbDTIshwFFgLP9FXPRU9CZR5oeHC3xLyGXgv7ktkxIwibyz2xvB8ODjhmvfgqicVwbkLZBIt0CNg/640?from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

🏷️仓库名称：**MetaMask/metamask-extension**  
🌟截止发稿星数: **11902** (近一个月新增:125)  
🇨🇳仓库语言: **JavaScript**  
🤝仓库开源协议：**Other**  
🔗仓库地址：**https://github.com/MetaMask/metamask-extension**  

### 引言

> 本文档旨在深入介绍 MetaMask GitHub 代码库，探讨其作用、技术细节和社区参与情况。

### 项目作用

MetaMask 通过将私钥存储在用户的浏览器中来简化与以太坊区块链的交互。它提供了一个安全且用户友好的界面，让用户可以查看余额、发送交易、管理身份，并与去中心化应用程序 (dApp) 进行交互。

### 仓库描述

此 GitHub 代码库包含 MetaMask 浏览器扩展程序的源代码、文档和测试套件。

### 案例

-   MetaMask 已被广泛用作与去中心化金融 (DeFi) 应用程序、不可替代代币 (NFT) 市场和基于区块链的游戏进行交互的网关。
    
-   该扩展程序有助于降低用户访问和使用区块链服务的门槛。
    

### 客观评测或分析

MetaMask 浏览器扩展程序因其以下优点而受到赞誉：

-   安全性：私钥存储在本地，而不是在中心化服务器上。
    
-   易用性：直观的界面让用户可以轻松管理他们的加密资产和与 dApp 交互。
    
-   可定制性：用户可以安装新功能并根据自己的喜好调整扩展程序。
    

### 使用建议

-   安装最新的 MetaMask 浏览器扩展程序以享受最新的功能和安全更新。
    
-   确保您的私钥安全保管，并将其备份在安全的位置。
    
-   仔细审查与 MetaMask 交互的 dApp 的可信度和声誉。
    

### 结论

MetaMask 浏览器扩展程序是与区块链生态系统交互的重要工具。它的开源性质、安全性、易用性和可定制性使它成为希望探索加密货币和去中心化应用程序世界的个人和开发人员的宝贵资源。

6.人工智能专家发展路线图

🏷️仓库名称：**AMAI-GmbH/AI-Expert-Roadmap**  
🌟截止发稿星数: **29033** (近一个月新增:218)  
🇨🇳仓库语言: **JavaScript**  
🤝仓库开源协议：**MIT License**  
🔗仓库地址：**https://github.com/AMAI-GmbH/AI-Expert-Roadmap**  

### 引言

> 本指南为有志于成为人工智能专家的个人提供了一条清晰的路径，涵盖了必要的技能和技术。

### 项目作用

该路线图涵盖了人工智能领域的各个方面，包括数据科学、机器学习、深度学习、数据工程和大数据工程。它提供了每个领域的关键概念和工具的概述。

### 仓库描述

此 GitHub 仓库包含可视化图表、文章和资源，帮助个人规划他们的人工智能学习之旅。它还提供交互式版本，包含指向相关资源的链接。

### 案例

本文未提供具体案例。

### 客观评测或分析

这份路线图由人工智能领域专家编写，提供了全面且最新的信息。它在行业内得到了广泛认可，被个人和组织广泛使用。

### 使用建议

个人可以根据自己的兴趣和职业目标选择关注特定的领域。路线图提供了指导，但最终的学习旅程应该根据个人的背景和抱负进行定制。

### 结论

“人工智能专家发展路线图”为个人提供了宝贵的资源，帮助他们规划和提升他们的人工智能技能。通过遵循路线图，个人可以获得在人工智能领域取得成功的知识和指导。

7.Ghost：开源出版平台

![图片](https://mmbiz.qpic.cn/mmbiz_png/asU9BglPP50LGbDTIshwFFgLP9FXPRU9rYHhCm4ymGzH8hzyslsqD4Bh7tyO2OGRGcryrU9ZnIa2orLuAl4QsQ/640?from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)![图片](https://mmbiz.qpic.cn/mmbiz_png/asU9BglPP50LGbDTIshwFFgLP9FXPRU9lt56BsqQ06BibSECbM2U6wcCIQRiaicXH1qLoQhzRulfibzSggYb7pDF1Q/640?from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

🏷️仓库名称：**TryGhost/Ghost**  
🌟截止发稿星数: **46959** (近一个月新增:381)  
🇨🇳仓库语言: **JavaScript**  
🤝仓库开源协议：**MIT License**  
🔗仓库地址：**https://github.com/TryGhost/Ghost**  

### 引言

> Ghost 是一款开源且专注于独立技术的现代化出版、会员、订阅和时事通讯平台。本文将深入探讨 Ghost 的功能、技术解析，并提供使用建议。

### 项目作用

Ghost 基于 Node.js 构建，使用 MongoDB 作为其数据库。它采用无头架构，可让内容创作者专注于内容创作，而无需担心底层基础设施。Ghost 提供多种功能，包括：

-   直观的用户界面，易于上手
    
-   支持 Markdown 和 HTML 编辑
    
-   主题和插件系统，实现广泛的定制可能性
    
-   RESTful API，可与其他应用程序集成
    

### 仓库描述

Ghost 仓库包含 Ghost 的源代码、文档和示例配置。它还包括一个活跃的社区，用于讨论、支持和贡献。

### 案例

Ghost 已被广泛用于创建各种博客、时事通讯和会员网站，包括：

-   The Ghost Blog
    
-   Medium
    
-   Substack
    

### 客观评测或分析

Ghost 因其以下优点而受到好评：

-   开源且免费使用
    
-   无头架构，提供灵活性
    
-   易于使用，适合各种用户
    
-   强大的主题和插件生态系统
    

### 使用建议

Ghost 非常适合希望创建和发布高质量在线内容的个人和组织。它特别适合：

-   博客作者
    
-   时事通讯发布者
    
-   会员网站运营商
    
-   追求自定义和灵活性的人
    

### 结论

Ghost 是一款强大的开源出版平台，提供广泛的功能和灵活性，满足各种数字出版需求。它易于使用，但又功能强大，是希望创建和管理专业在线内容的用户的理想选择。

8.LangChain4j：Java版LLM集成利器

![图片](https://mmbiz.qpic.cn/mmbiz_jpg/asU9BglPP50LGbDTIshwFFgLP9FXPRU9BEHN8Vp1agBJEp9oKTImUQR6VdTJyN2GBoraXZddekuyZxVoqlnTSw/640?from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

🏷️仓库名称：**langchain4j/langchain4j**  
🌟截止发稿星数: **4548** (近一个月新增:242)  
🇨🇳仓库语言: **Java**  
🤝仓库开源协议：**Apache License 2.0**  
🔗仓库地址：**https://github.com/langchain4j/langchain4j**  

### 引言

> LangChain4j旨在简化LLM与Java应用程序的集成，让开发者可以轻松利用LLM的强大功能。

### 仓库描述

LangChain4j为Java应用程序集成了LLM的强大功能。

### 客观评测或分析

-   支持15+ LLM提供商和15+嵌入存储。
    
-   提供低级和高级的LLM集成工具，满足不同开发者的需求。
    
-   积极维护，致力于整合社区最新的技术和集成。
    

### 使用建议

-   适合想要在Java应用程序中集成LLM的开发者。
    
-   可以用于构建聊天机器人、推荐系统、摘要生成器等LLM驱动的应用程序。
    

### 结论

LangChain4j为Java开发者提供了便捷且强大的LLM集成解决方案，让开发者可以充分利用LLM技术，构建创新的应用程序。

感谢您的观看！别忘了点赞、收藏和分享哦！❤️ 你的支持是我最大的动力！😊 每天为你带来不一样的开源项目！

![图片](https://mmbiz.qpic.cn/mmbiz_jpg/asU9BglPP50LGbDTIshwFFgLP9FXPRU9uQJMPkyf09icqLKk4o4joy8xmAticT9DGnJBhBa7N9qTGRibBV81d31KA/640?from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)
