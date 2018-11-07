---
title: "使用Hugo移植網站心得"
date: 2018-11-07T20:31:53+08:00
draft: false

categories: ['隨筆']
tags: ['Hugo','Gitlab']
author: "HY Cheng"
---

之前寫Blog都使用Logdown，因為那時覺得介面美觀，操作方便，直到有一次Logdown帳號突然無法登入(因為之前都是綁定Github登入)，客服都沒回如同荒廢，因此決定轉換平台，後來選擇Hugo的原因只是因為是基於Go，想試試新語言的效能。

Hugo的安裝步驟不難，但在安裝的時候卻歷經波折。原本在Windows 10 上安裝了各種GCC的軟體(Mingw,TDM-GCC)都無法解決安裝支援SASS的Hugo版本遇到的編譯GCC問題(`cc1.exe: sorry, unimplemented: 64-bit mode not compiled in`)，後來開虛擬機想說使用Ubuntu 16.04開發試試，又遇到一樣問題，後來索性升級18.04，終於問題解決了(Ubuntu 18.04讚！大推Ubuntu Dock最小化)，可是apt底下最新版本不支援使用的theme版本，因此改用snap安裝，再部屬到Gitlab平台上。

雖然之前Gitlab因為rm事件雷過，但是免費私有repo蠻有吸引力的，而且他對hugo的支援滿完整，官方有出整合Hugo的範例，fork下來之後再根據官方教學，幾分鐘就能生成Gitlab Page。。

總之現在Hugo用下來使用者體驗算不錯，目前已完全入坑了。
