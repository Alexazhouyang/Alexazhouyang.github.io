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
