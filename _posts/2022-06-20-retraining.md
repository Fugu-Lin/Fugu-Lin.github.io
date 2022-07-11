---
title: ReTraining
tags: Machine-Learning Deep-Learning
---
前言
-------------
半夜睡不著覺，突然想起先前在學校提到如果有沒看過的種類的圖片要怎麼重新訓練的問題，於是乎就想了一個方法，但不確定可不可行，總之先記錄下來。

> 整體系統說明，當來源端傳送圖片資料到後端(ML/DL Service)。當後端分析完後，則會回傳每個物件的位置，並在網頁上以較高的透明Z-index當作資料的範圍。
>
> 然而重新label的方法則可以透過頁面拉取一個框，並在該框內重新定義名稱，讓使用者能透過自己標註圖片，並送至後端以ML的方式重新Train，達到自動化訓練的目的。

整體物件辨識流程
-------------

![Image](../../../assets/images/retraining-1.png "Image")
![Image](../../../assets/images/retraining-2.png "Image")
![Image](../../../assets/images/retraining-3.png "Image")
![Image](../../../assets/images/retraining-4.png "Image")
