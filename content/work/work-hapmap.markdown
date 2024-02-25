---
layout: post
title:  "移動ロボットを用いた広域・高解像度な凹凸地図の構築"
img: hapmap.png
categories: [research]
date: "2024-01-04"
tags: [Haptics, Robot, XR, ROS, Unity, Python]
---

移動ロボットとVIOを用いて、地面の数mm程度の凹凸の情報を含む触覚地図を構築する触覚センシングシステムを開発した。


<!--more-->

ロボットが凹凸のある地面を走行する際に生じる上下移動をVIOを用いて検出する。VIOにはRelasense T265を使用。高さ1mm、横幅50mmの解像度で空間の凹凸を検出可能。移動ロボットの制御にはROSを使用している。センシングデータをPythonで解析して、Unityにインポートすることで、それを3次元CG空間における地形として復元できる。

デモアプリケーションとして、計測したアスファルト面の凹凸形状を数倍に増幅した3Dデータを使ってプレイするパターゴルフを開発した。


{{< figure src="/images/hapmap/hapmap_1.png" class="img-article">}}

{{< figure src="/images/hapmap/hapmap_2.png" class="img-article">}}

{{< figure src="/images/hapmap/hapmap_3.png" class="img-article">}}


# Movie
{{<youtube "xvizzGH8I6I">}}

# Presentation
{{< embed-pdf url="../pdf/hapmap.pdf" >}}



