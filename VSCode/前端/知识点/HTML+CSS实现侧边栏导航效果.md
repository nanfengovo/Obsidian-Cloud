---
created: 2024-10-11T12:19:27 (UTC +08:00)
tags: []
source: https://mp.weixin.qq.com/s/UT5jQtVdV9fTmwLWnDvvsg
author: 小黑学长T
---

# HTML+CSS实现侧边栏导航效果！！附源码！！

> ## Excerpt
> 侧边导航栏在很多后台项目中比较常用，主要是为了方便我们快速找到需要的内容，可以一步到位，因此，今天我们就来练习一个这样的侧边导航栏效果，希望这个效果对你有帮助！

---
前言：

侧边导航栏在很多后台项目中比较常用，主要是为了方便我们快速找到需要的内容，可以一步到位，因此，今天我们就来练习一个这样的侧边导航栏效果，希望这个效果对你有帮助！

![图片](https://mmbiz.qpic.cn/mmbiz_png/oMlX8Lll9JjHxveiciaHKicXW3ttCwd1dhxrUMgQQjAOOsBPIqtWHYp5eficgaNwHCyzHfHdVYt4ClaBVTibXibL8xqg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

效果展示：

![图片](https://mmbiz.qpic.cn/sz_mmbiz_gif/OOibJzicqyItcXOYhJ7OW0XicfFMWebNBCIL2tsLt2XMBoNLzutFWpoRicnbBYg83B0d50vT2B5Mpf6iccVLfRDnjIg/640?wx_fmt=gif&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

![图片](https://mmbiz.qpic.cn/mmbiz_png/oMlX8Lll9JjHxveiciaHKicXW3ttCwd1dhxrUMgQQjAOOsBPIqtWHYp5eficgaNwHCyzHfHdVYt4ClaBVTibXibL8xqg/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

完整源码：

![图片](https://mmbiz.qpic.cn/mmbiz_png/oMlX8Lll9JjHxveiciaHKicXW3ttCwd1dhx4F8ibzib3WOwTpSzXbkIcd7fALtRTHodMerA7gs6dkb4srZgRvfoIHRw/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

```
<!DOCTYPE html>

<html>

  

<head>

    <meta http-equiv="content-type" content="text/html; charset=utf-8">

    <meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no">

  

    <title>侧边导航栏</title>

    <!-- 引入字体图标 -->

    <link href="https://cdn.bootcdn.net/ajax/libs/font-awesome/4.7.0/css/font-awesome.css" rel="stylesheet">

  

    <style>

        *{

    /* 初始化 */

    margin: 0;

    padding: 0;

}

body{

    /* 100%窗口高度 */

    height: 100vh;

    /* 弹性布局 居中 */

    display: flex;

    justify-content: center;

    align-items: center;

    background-color: #7284a7;

}

ul{

    list-style: none;

}

nav{

    /* 固定定位 */

    position: fixed;

    width: 300px;

    height: 650px;

    left: 0;

    background-color: #ffbb00;

    border-radius: 20px 20px 20px 0px;

}

.menus{

    /* 垂直居中 */

    margin: 50px 0;

    color: #fff;

}

.li{

    letter-spacing: 2px;

    font-size: 17px;

    font-weight: 600;

    padding: 16px 0;

    /* 动画过渡 */

    transition: 0.3s;

}

.menus li:hover{

    background-color: #ae00ff;

}

.li .fa{

    font-size: 20px;

    width: 50px;

    height: 20px;

    text-align: center;

    margin-left: 5px;

}

.li ul{

    border-radius: 20px;

    width: 0;

    height: 550px;

    padding: 50px 0;

    background-color: #a06993;

    position: absolute;

    top: 0;

    right: 0;

    overflow: hidden;

    transition: 0.3s;

}

.li ul li{

    padding: 16px 24px;

    /* 文字禁止换行 */

    white-space: nowrap;

    transition: 0.3s;

}

.li:hover ul{

    border-radius: 20px;

    width: 250px;

}

.li ul li:hover{

    background-color: #c28fb4;

}

</style>

</head>

  

<body>

    <nav>

        <ul class="menus">

            <li class="li">

                <i class="fa fa-qq" aria-hidden="true"></i>

                QQ

                <ul>

                    <li><i class="fa fa-qq" aria-hidden="true">1号</i></li>

                    <li><i class="fa fa-qq" aria-hidden="true">2号</i></li>

                    <li><i class="fa fa-qq" aria-hidden="true">3号</i></li>

                    <li><i class="fa fa-qq" aria-hidden="true">4号</i></li>

                    <li><i class="fa fa-qq" aria-hidden="true">5号</i></li>

                    <li><i class="fa fa-qq" aria-hidden="true">6号</i></li>

                    <li><i class="fa fa-qq" aria-hidden="true">7号</i></li>

                </ul>

            </li>

            <li class="li">

                <i class="fa fa-weixin" aria-hidden="true"></i>

                weixin

                <ul>

                    <li><i class="fa fa-weixin" aria-hidden="true">1号</i></li>

                    <li><i class="fa fa-weixin" aria-hidden="true">2号</i></li>

                    <li><i class="fa fa-weixin" aria-hidden="true">3号</i></li>

                    <li><i class="fa fa-weixin" aria-hidden="true">4号</i></li>

                    <li><i class="fa fa-weixin" aria-hidden="true">5号</i></li>

                    <li><i class="fa fa-weixin" aria-hidden="true">6号</i></li>

                    <li><i class="fa fa-weixin" aria-hidden="true">7号</i></li>

                    <li><i class="fa fa-weixin" aria-hidden="true">8号</i></li>

                    <li><i class="fa fa-weixin" aria-hidden="true">9号</i></li>

                    <li><i class="fa fa-weixin" aria-hidden="true">10号</i></li>

                </ul>

            </li>

            <li class="li">

                <i class="fa fa-weibo" aria-hidden="true"></i>

                weibo

                <ul>

                    <li><i class="fa fa-weibo" aria-hidden="true">1号</i></li>

                    <li><i class="fa fa-weibo" aria-hidden="true">2号</i></li>

                    <li><i class="fa fa-weibo" aria-hidden="true">3号</i></li>

  

                </ul>

            </li>

            <li class="li">

                <i class="fa fa-tencent-weibo" aria-hidden="true"></i>

                tencent-weibo

                <ul>

                    <li><i class="fa fa-tencent-weibo" aria-hidden="true">1号</i></li>

                    <li><i class="fa fa-tencent-weibo" aria-hidden="true">2号</i></li>

                    <li><i class="fa fa-tencent-weibo" aria-hidden="true">3号</i></li>

                    <li><i class="fa fa-tencent-weibo" aria-hidden="true">4号</i></li>

                    <li><i class="fa fa-tencent-weibo" aria-hidden="true">5号</i></li>

                </ul>

            </li>

            <li class="li">

                <i class="fa fa-telegram" aria-hidden="true"></i>

                telegram

                <ul>

                    <li><i class="fa fa-telegram" aria-hidden="true">1号</i></li>

                    <li><i class="fa fa-telegram" aria-hidden="true">2号</i></li>

                    <li><i class="fa fa-telegram" aria-hidden="true">3号</i></li>

                    <li><i class="fa fa-telegram" aria-hidden="true">4号</i></li>

                    <li><i class="fa fa-telegram" aria-hidden="true">5号</i></li>

                </ul>

            </li>

        </ul>

    </nav>

</body>

  

</html>
```
