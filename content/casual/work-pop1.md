---
layout: post
title:  "POP1 Kill Extractor"
img: pop1.png
categories: [casual]
date: "2024-01-15"
tags: [Interface, Image Processing, Python]
---

VRゲーム「POPULATION: ONE」のプレイ映像から、自動的にキルシーンを抽出してキル集を作成するツール。


<!--more-->

「POPULATION: ONE」ではキルが発生した際に、視野中のUIにそれを示す文字列が表示され、効果音が再生される。
しかし、VRゲームのUIの位置や向きは頭部の運動にしたがって変化するため、デスクトップゲームのように画面中の固定された位置に常にログが表示されるわけではなく、画像処理によるアプローチでは偽陰性が多くなってしまうという問題があった。
そこで、第一段階として音声処理によるキル時の効果音検出を行い、第二段階としてOCRを使って文字列を検出する画像処理を行うアプローチを採用した。
音声処理は画像処理と比較して偽陽性が多い。最初に大まかにキルシーンとして疑われる場面をフィルタリングしたうえで、画像処理を使って細かな判別を行うことで、先述の問題の解消を試みた。



# Movie
本ツールを使って自動生成されたキル集
{{<youtube "KIDa9pQgZP4">}}

# Repository
- https://github.com/te260ku/pop1-kill-extractor
