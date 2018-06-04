---
layout:     post
title:      Mobile APP Achieve Horizon Scrolling Menu
subtitle:   Web Developer 
date:       2018-06-04
author:     Alexa
header-img: img/post-bg-2015.jpg
catalog: true
tags:
    - CSS
---
## How to achieve Scrolling Menu based on webApp ?
1. based on CSS, compatible with mobile except Firefox;

```
<!DOCTYPE html>
<html>
<head>
    <title>Horizon Scroll Menu</title>
    <style type="text/css">
        .slide-box{
            margin-top: 200px;
            display: -webkit-box;
            overflow-x: scroll;
            -webkit-overflow-scrolling:touch;
        }
        .slide-item{
            width: 400px;
            height: 400px;
            border:1px solid #ccc;
            margin-right: 30px;
        }
		.slide-box::-webkit-scrollbar{display: none;} //hide scroll
    </style>
</head>
<body>
    <div class="slide-box">
        <div class="slide-item"></div>
        <div class="slide-item"></div>
        <div class="slide-item"></div>
        <div class="slide-item"></div>
        <div class="slide-item"></div>
    </div>
</body>
</html>
```
2. Using JQuery package to achieve, high compatibility but it is too large;

```
<link href="{$host}zb_users/theme/{$theme}/style/css/jquery.mCustomScrollbar.min.css" rel="stylesheet">
<script src="{$host}zb_users/theme/{$theme}/script/jquery.mCustomScrollbar.concat.min.js" type="text/javascript"></script>
<script>
    (function($){
        $(window).on("load",function(){
            $(".Scrollbar").mCustomScrollbar({
             theme:"minimal-dark", //选了minimal-dark样式
             scrollInertia: 0, //滚动不加入任何动画时间
//更多配置信息 http://manos.malihu.gr/jquery-custom-content-scroller/
             });
        });

    })(jQuery);

</script>
```
