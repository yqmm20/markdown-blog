---
layout: post
title: 手动升级微软新版edge
slug: 2020-02-20-001
date: 2020-02-20
status: publish
author: tu-tu
categories: 
  - 默认分类
tags: 
  - edge降级
  - 禁用edge自动更新
excerpt: 最新版微软edge关闭自动更新
---

方法：

- 1.关闭自动升级，避免自动升级到最新版的 edge.  
C:\\Program Files\\Microsoft\\EdgeUpdate 里的 MicrosoftEdgeUpdate.exe 改一下名字即可.

- 2.到微软官方下载 79.xx 版本的 exe 文件，下载后不要双击 exe 文件，要使用压缩软件解压 79.xx.exe 文件  
提取 msedg.7z 里面的全部文件，包括一个 79.XX 开头的文件夹，两个可执行文件 msedge.exe 和 msedge\_proxy.exe.  
复制到 C:\\Program Files\\Microsoft\\Edge\\Application 里面。  
改名原有的 78.XX 开头的文件夹以及旧的 msedge.exe 和 msedge\_proxy.exe.  
如果你要保留旧版本的设置信息请保留 SetupMetrics 文件夹和 msedge.VisualElementsManifest.xml  
测试新版本没问题的话可以删除刚才改名的3个旧文件

--end--
