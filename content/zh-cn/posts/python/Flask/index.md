---
title: "关于足印英语"
date: 2022-11-27T10:06:25+08:00
description: Sample post with multiple images, embedded video ect.
menu:
  sidebar:
    name: 足印英语
    identifier: paw
    parent: python
    weight: 10
hero: images/forest.jpg
tags: ["Markdown","Content Organization","Multi-lingual"]
categories: ["Basic"]
---
《足印英语》是一款用于英语学习的小程序。它通过对句子的反复听说进行英语学习。在我个人经验中，这是最快最有效果的一种学习方式。

《足印英语》分为四个部分。这四个部分分别为前端（微信小程序）、后端语句库、后端工具和后端语音识别引擎。

在用户使用《足印英语》之前，需要管理员先使用后端工具将英语学习资料导入后端语句库。在用户使用《足印英语》时，前端即微信小程序首先到后端语句库获取此次学习的资料，然后后端的语音识别引擎对用户的语音输入进行评分，将用户的朗读效果反馈给用户，帮助用户正确的发音。

《足印英语》的前端是微信小程序，采用H5开发。

《足印英语》的后端都是使用Python+Flask Appbuilder作为开发框架，然后根据每个模块的特点，分别在开发中使用了Mysql、Redis、pyTorch等技术。


