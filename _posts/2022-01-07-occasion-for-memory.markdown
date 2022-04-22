---
layout: post
title:  FOR MEMORY
date:   2022-01-07 15:01:35 +0300
image:  me.jpg
tags:   occasion
---

### 1. Poppy
* The poppy is a memorial flower that is used to honor a loved one who has passed away. Poppy bouquets and sprays are stunning since the blooms are big, cup-shaped, and bright. For funerals and memorial services, especially for soldiers who died while serving or veterans, give the gift of the poppy. Encourage relatives and family members who are suffering from insomnia to get better sleep. Leaving poppy bouquets on graves or monuments as a gift to the deceased(Zoe, 2021).
![]({{ site.baseurl }}/images/me1.jpg)
<br>

***

### 2.  Willow Branches
* In China, some people carry willow branches with them on the day of their Tomb Sweeping or Qingming Festival(Wikipedia, 2022).
![]({{ site.baseurl }}/images/me2.jpg)
<br>

***

__Image Source:__ <a href="https://pixabay.com/">__Pixabay__</a>

<html lang="en">
 
<head>
    <meta charset="UTF-8">
    <title>Title</title>
</head>
 
<body>
    <div style="border: 2px solid lightgray;">
    <a href="javascript:;" id="btn" style="font-size: 24px; font-style: bold; color:rgb(255, 157, 0);">
        >>>Reference</a>
    <span id="content">
        <br>
        Wikipedia. 2021. <i>Qingming Festival.</i> [online] Available at: <https://en.wikipedia.org/wiki/Qingming_Festival> [Accessed 12 April 2022].<br><br>
        Zoe, 2021. <i>POPPY FLOWER MEANING AND SYMBOLISM.</i> [online] The African Garden. Available at: <https://theafricangarden.com/poppy-flower-meaning/> [Accessed 12 April 2022].<br><br>
        <br>
    </span>
    </div>
    <script type="text/javascript">
        //获取button按钮
        var btn = document.getElementById('btn');
        //获取p
        var content = document.getElementById('content');
        //获取p中的内容
        var str = content.innerHTML;
        //定义一个变量，表示当前的状态（收缩、展开）
        var onOff = true; // true表示展开
        btn.onclick = function() {
            if (onOff) {
                content.innerHTML = str.substr(0, 0);
            } else {
                //说明当前状态是收缩的，需要展开
                content.innerHTML = str
            }
            onOff = !onOff; //每点击一次，改变一次展开、收缩状态
            return false; //阻止a标签的默认事件
        }
    </script>

</body>
 
</html>