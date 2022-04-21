---
layout: page
title: About
permalink: /about/
image: an.jpg
---

***

# The history of flower languages

Flowers have been used for centuries in many European and Asian countries and have even played an important role in literature, from the sonnets, which show us the gardens Shakespeare travelled through, to the myth of Shennong tasting a hundred herbs in ancient times, when flowers had their own meaning and were even used as medicine. Almost every emotion can be expressed in flowers, for example a red rose means "I love you". 

Learning about the special symbolism of flowers became a popular pastime in the 1800s. It helped us to express ourselves in a subtle way and it can help us to express our feelings of disgust(Almanac, 2021).



***

![]({{site.baseurl}}/images/all2.jpg)

# Our Purpose

On our website we will introduce you to the different meanings of each flower, including their colours and combinations, and we will also suggest suitable gift ideas to help you express your emotions perfectly. 

***

![]({{site.baseurl}}/images/wedding12.png)

# Our Categories

On our website, you can find the language of flowers in three categories according to your needs:

### Content List

In this section, we list all the information we have collected on the language of flowers, including what the different colours of the same flower mean, what they are used for and when they are suitable as gifts.

### Occasion

Different flowers for different occasions will help us to convey our feelings better. Here we will list some of the different occasions and the flowers that are appropriate for these occasions. We have also divided the flowers to show more clearly the different meanings of the flowers.

### People

There are some flowers with meanings aimed at special people.Different flowers are needed to express emotions such as gratitude, love, reverence or encouragement to different people. In this section, we give you advice on choosing flowers as a gift, categorised by the different recipients.

***

![]({{site.baseurl}}/images/all.jpg)

***

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
        Almanac. 2021. <i>Flower Meanings: The Language of Flowers.</i> [online] The African Garden. Available at: <https://www.almanac.com/flower-meanings-language-flowers> [Accessed 12 April 2022].<br><br>
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