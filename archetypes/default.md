---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false          # 編輯模式
summary: ""           # 文章大綱
description: ""       # 文章描述
categories: ['']      # 分類
tags: ['']            # 標籤
author: ['黑糖']       # 作者

showtoc: true         # 顯示目錄
tocopen: true         # 預設打開目錄
comments: true        # 顯示評論
hidemeta: false       # 是否隱藏 meta 訊息(發布日期、作者...etc)
isCJKLanguage: true   # 是否是中文(chinese,japanese,korea) 字數判斷用

searchHidden: false   # 隱藏頁面不被搜尋
disableShare: false   # 取消社群分享區塊
robotsNoIndex: false  # 防止被搜尋引擎索引

ShowCanonicalLink: false # 啟用標準網址
CanonicalLinkText: "Originally published at"
canonicalURL: "" 

cover:
    hidden: false     # 隱藏封面圖片
    relative: false   # 是否使用相對路徑
    image: ""         # 封面圖片路径
    caption: ""       # 封面圖片底部描述
    alt: ""           # 封面圖片替代文字
---