---
layout: post
title:  "Path-Code"
img: path-code.png
categories: [casual]
date: "2024-01-13"
tags: [Interface, Javascript]
---

定められたルートを特定の移動方法で辿ることで、隠蔽された情報にアクセスする暗号化システムを開発した。


<!--more-->

あらゆる位置情報は暗黙的に次の2つの情報を有している。第一にすべての位置情報にはそこに至るまでに辿ってきた経路が存在する。第二に位置情報の変化にはそれに要した歩く、走るなどの動作が付随するということである。
これらの位置情報がもつ要素をふまえ、従来の位置情報システムに時間軸と意味性を取り入れた。

システムはセンシング部、データ共有部、情報提示部から構成されている。
センシング部では、スマートフォンに内臓された加速度センサーの値と、GPSによる位置情報を取得する。
データ共有部では、サーバー側で受信したスマートフォンのセンシングデータの処理を行う。加速度の値をランダムツリーによって分類して、ユーザーの行動（静止、歩く、走る、カメラで撮影）を判別する。また、位置情報をもとにユーザーが正しい経路を辿っているかどうかを確認する。
情報提示部では、地図の表示と暗号化された情報の提示を行う。暗号化された情報はAR.jsを用いることでAR表示も可能。

{{< figure src="/images/path-code/user-flow.png" class="img-article">}}

{{< figure src="/images/path-code/system.png" class="img-article">}}

# Movie
{{<youtube "tnMKA6FpaCg">}}


# Presentation
{{< embed-pdf url="../pdf/path-code.pdf" >}}

# Repository
- https://github.com/te260ku/path-code

