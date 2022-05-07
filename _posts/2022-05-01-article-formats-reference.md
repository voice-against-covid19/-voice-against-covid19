---
layout: post
title:  "文章格式参考"
date:   2022-05-01
categories: howto
tags: 参与
---

> 本文从 [如何协作参与发声平台]({{ site.baseurl }}/howto/2022/01/01/how-to-participate.html) 复制出来，方便文章编辑快速参考。祝编辑愉快～


1. 头部格式：（每篇文章（md 文件）都必须在开头放置这样的信息，用于生成网页）  

    ```
    ---
    layout: post
    title:  一女生实名指控曾受沈阳性骚扰
    date:   2018-04-09
    categories: Archive
    tags: 沈阳
    is_sticky: true
    image_feature: ""
    description: 这位女生名叫许红云，她希望更多被沈阳侵扰的女生勇敢地站出来，勇敢地面对过去和现在，才能看到未来。
    ---
    ```
    - layout: post （只能是 post 不要动）  
    - title: 文章的标题（比文件名上的标题优先）  
    - date: 在本站的发布日期（本站文章列表默认以这个日期来排序）  
    - categories: 分类（有必要的话可以自定义）  
    - tags: 标签（在本平台查看是否已有相关标签，有必要的话可以自定义）  
    - is_sticky: true 或者 false，对应是 或 否为置顶  
    - image_feature: "如果文章有合适的图片可作为封面图，图片链接填在这里，若无则不填写"  
    - description: （可用文章的导语做简述，显示在文章列表）  

    > 注意：以上填充的内容中不要出现英文的单引号`''` 和双引号`""`（中文引号可以），其他英文标点符号也最好不使用，若使用的话请在该内容的首尾用英文单引号括起来 :)  
    
2. 引用来源的格式

    ```
    ---
    原文来自公号名称/网站名称：~~[文章标题](原文链接)~~
    
    作者：XXX
    ---
    ```

3. 正文小标题，使用 h2 或 h3。

4. 图片编辑
  1. 使用 [https://sm.ms](https://sm.ms) 或 [https://imgur.com](https://imgur.com) 图床平台生成链接。  
    - 然后在 md 文件中相应位置写：  
    ```
    ![](https://xxxxxxxxxxxx)
    ```
  2. 图注用 `<center>图注</center>` 居中。

