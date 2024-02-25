---
layout: post
title:  "Emotional Ice"
img: emotional_ice.png
categories: [casual]
date: "2024-01-10"
tags: [IoT, Javascript, Electronics]
---
表情によって尖ったり凹んだりする製氷モーダル。IoTにおける食べることによるインタラクションの可能性を検証した。

<!--more-->

表情の検出および推定にはTensorflow.jsを用いた。規定時間における表情の種類別の割合を算出して、ソケット通信で冷凍庫内の製氷モーダルに送信する。受信した値をもとにサーボモーターを制御して、水が入ったシリコン製のモーダルに凹凸形状をもたせる。

![](https://i.imgur.com/V2EXSLX.jpg)


![](https://i.imgur.com/9rFXSKb.jpg)

# Presentation
{{< embed-pdf url="../pdf/emotional-ice.pdf" >}}
