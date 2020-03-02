title: GitHub小技巧
author: 王迪
tags:
  - GitHub
  - Tips
categories: []
date: 2020-03-01 14:07:00
---
## 查找项目时需要关注的几个点
- 开源项目名称
- 简要描述
- Read.md
- star数与fork数
- 更新日期


## 通过名称来搜索
比如需要名称来搜索 spring boot 有关的开源项目，可以在搜索框输入 `in:name spring boot` 
搜索出的内容即为项目名称中包含spring boot的开源项目

<!-- more -->

## 通过star数来搜索
比如在前面搜索的基础上搜索大于2000star数的开源项目 `in:name spring boot stars:>2000` 

## 通过fork数来搜索
同star数，比如搜索fork数大于1000的项目： `in name spring boot forks:>1000`


## 在Readme.md中搜索
Readme.md中包含spring boot的开源项目 `in:readme spring boot` ，同理，后可跟star或fork限定查找范围

## 在描述中搜索
项目描述中包含sprin boot的开源项目 `in:description spring boot` 

## 在语言中限定来搜索
项目描述中包含spring boot，且用java语言来开发的（这不是废话！）开源项目 `in:description spring boot language:java` 

## 通过最后一次更新时间来搜索
项目描述中包含spring boot，且用java语言来开发的，最后一次更新的时间最早为2020年2月1日的开源项目 `in:description spring boot language:java pushed:>2020-2-1`



## 不同分支（版本）进行比较
在github项目地址后加 /compare ，然后可以对不同分支（版本）进行比较。