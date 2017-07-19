---
layout: post
zsaid: "ZSA-2017-01"
cve: "2017-9324"
level: "高危"
title: "Administrative privileges for agents by accessing the installer"
date: 2017-5-30T00:00
author: "文浩坚"
category: "advisory"
tags: ["advisory"]
excerpt: Administrative privileges for agents by accessing the installer
---

## 问题描述

任何服务人员通过在浏览器输入 "otrs/index.pl?XXXXXX" (出于安全理由隐藏) 取得完全的管理员权限, 可以读出系统的配置, 或更改系统配置.

以下的版本都存在风险:

OTRS 3.1.1 以上包含 3.3.16
OTRS 4.0.1 以上包含 4.0.23
OTRS 5.0.1 以上包含 5.0.19

## 临时方案
