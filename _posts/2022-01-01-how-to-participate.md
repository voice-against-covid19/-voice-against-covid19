---
layout: post
title:  "【置顶】如何协作参与发声平台"
date:   2022-01-01
categories: howto 
is_sticky: true
tags: 参与
description: '图文并茂教你如何参与本平台的文章发布'
---

## 中国民间抗疫发声平台是什么

中国民间抗疫发声平台，是在 GitHub 开放平台搭建的一个站点，用于备份微信、微博等平台被删文章。防火墙外也有像 [中国数字时代](https://chinadigitaltimes.net/chinese/)、[GreatFire](https://zh.greatfire.org/)、[自由微博](https://freeweibo.com/)、[自由微信](https://freewechat.com/)、[墙与书](https://wallsandbooks.wordpress.com) 这样的网站做文章备份，但不便于墙内网络传播。


## 抵抗404，需要公众参与新方法

在严重依赖微信、朋友圈的情况下，抵抗 404，保证文章传播阅读的持久有效性，现在比较常见的方法有：

- 订阅号菜单栏的非正式群发
- 订阅号小号
- 文字保存为长图片
- 借助有道云笔记

可以发现，这些备份方法并没有很好地使用超链接、微信之外的网站平台，它们有时候也会意想不到的消失，就像断断续续的水滴。

公众参与抵抗404，需要开辟新的方法，重新捡起超链接、网站，再加上开源开放的协作平台。

> 本平台，在众多前辈的开放协作平台（如有颗银河系遥远的星球）的基础上，砥砺前行，继续启程！  


## 如何参与本平台

### 需要的基本技能

- 熟悉使用 Markdown 基本标记语法
- 熟悉 Markdown 文本编辑器（可选项）：这些工具适用于对 Markdown 语法不熟悉的协作者
  - [MarkdownPad](http://markdownpad.com/)
  - [Atom](https://atom.io/)
  - html 转成 markdown：浏览器插件「[简悦](http://ksria.com/simpread/)」

- 熟悉基本 GitHub 平台使用（如提交 issue 问题报告）。
  - 若您是本站志愿者/长期贡献者，建议使用 GitHub Desktop 桌面客户端，可以直接提交文章或 PR。  

### 多种参与方式：
- 提交 issue
- 自己写好文章，通过 PR 方式提交给平台志愿者审核
- 若您是长期的贡献者，欢迎加入本平台的组织账号，直接发布文章。

### 提交 issue 步骤

1. 注册并登录 [GitHub](https://github.com/) 帐号

2. 访问[中国民间抗疫发声平台](https://github.com/voice-against-covid19/voice-against-covid19.github.io) GitHub 页面，在正上方有`issues` 超链接，点击后在右侧有绿色的`new issue` 按钮，点击即可。

3. Issue 版面可用于为平台提出任何意见、想法、网站问题、文章勘误等等，但不适宜就文章内容本身进行评论（请移步专门的地方讨论）。 

### PR 步骤说明

1. PR 的意思就是：我有新的想法、作品已经准备好了，发给你们一个提交请求，如果同意，站方可以直接合并我的代码和/或文章就可以了，很方便。当然必须先有 GitHub 账号。

2. fork 本平台仓库到自己的名下: 访问[中国民间抗疫发声平台](https://github.com/voice-against-covid19/voice-against-covid19.github.io) GitHub 页面，点击右上角 **Fork** 按钮。

3. (TODO) 如果本平台的 issue 版面有 issue 标记为 `404`、`help-wanted`，可以认领该 issue，进行相应修改等操作后，提交 PR。  

4. 编辑文章备份：在自己帐号里面的 Terminus2049.github.io 仓库，编辑添加备份的文章。

5. 填写 **commit new file**
  ![commit_new_file.png](https://i.loli.net/2020/02/09/fCs72X3pBYgSkT8.png)

6. 向原仓库提交 PR
    
    在自己的仓库页面，点击 **new pull request**，再点击 **create pull request**，填写 PR 描述并提交。
    ![new_pull_request.png](https://i.loli.net/2020/02/09/mONEWGFJwXod1ep.png)

7. 等待 Terminusbot 查看 PR ，符合要求的内容会 merge(合并）。

## 创建/编辑文章

### 使用网页
- 第一种方式：直接在线编辑添加
  1. 点击进入 `_posts/` 文件夹，点击上面的 **Create New File**
  2. 命名文章标题：统一格式为「Year-Month-Day-title.md」，例如 `2018-01-01-biao-ti.md`
  3. 在下方 **Edit new file** 空白区域编辑内容，编辑格式看下方[文章格式编辑要求](#文章格式编辑要求)
  4. 点击 **Preview** 可预览效果
    ![add_new_post.png](https://i.loli.net/2020/02/09/uhZUAWm6yr3MJ4I.png)

- 第二种方式：从本地上传已编辑的 md 文档
  0. 在电脑本地用文档编辑软件写好/改好 md 文件，文件名格式同上  
  1. 点击进入 `_posts/` 文件夹，点击 **Upload files**
    ![drag_files.png](https://i.loli.net/2020/02/09/Be21nogCdw4pJlE.png)
  2. 从本地选择要上传的 md 文档

### 使用 GitHub Desktop
      TODO 

### 文章格式编辑要求

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
