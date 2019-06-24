---
layout: default
title: 领域图
---

# 领域图

{:.no_toc}

| 版本 |   日期    | 描述 |  作者   |
| :--: | :-------: | :--: | :-----: |
| V1.1 | 2019-5-21 | 用户管理领域图 | 534265373 |
| V2.1 | 2019-5-29 | 添加任务管理 | 534265373 |
| V2.2 | 2019-6-16 | 用户认证信息的调整 | 534265373 |
| V2.3 | 2019-6-16 | 添加认证状态字段 | 534265373 |


## v1.1

## 下图为系统关于用户信息及身份（student/job）和组织信息的领域图。

![1](/DatabaseDesign_1.png)


## v2

## v2.1 下图为添加了任务信息和发布者，参与者的领域图。

![2.1](/DatabaseDesign_v2_1.png)

## v2.2 下图为添加了将性别，手机号从基本信息改为认证信息（不可随意修改）。

![2.2](/DatabaseDesign_v2_2.png)

## v2.3 下图为添加了验证状态字段，通过状态，判断用户权限及后台对其的相应处理。

![2.3](/DatabaseDesign_v2_3.png)