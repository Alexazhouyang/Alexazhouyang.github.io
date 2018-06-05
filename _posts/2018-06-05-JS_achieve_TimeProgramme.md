---
layout:     post
title:      TimeProgramme
subtitle:   JavaScript
date:       2018-06-05
author:     Alexa
header-img: img/post-bg-iWatch.jpg
catalog: true
tags:
    - JavaScript
    - html5
---
#Just based on JavaScript to show localtime immediately 

```javascript
 <script>  
    function  show_time()  
    {  
        var today,hour,second,minute,year,month,date,time;  
            
        today=new Date();  
        
        year = today.getFullYear();  
        month = today.getMonth()+1;  
        date = today.getDate();  
        hour = today.getHours();  
        minute =today.getMinutes();  
        second = today.getSeconds();  
        if(minute < 10) minute = '0' + minute;  
       if(second < 10) second = '0' + second;  
       time = year + "-" + month + "-" + date +" " + hour + ":" + minute + ":" + second;  
       $("#nowdate").html(time);  
   }   
   setInterval(show_time,1000);  
 </script>  
 ```
