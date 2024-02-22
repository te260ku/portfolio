---
layout: post
title:  "Boomshin: 触覚提示の有無を時空間的に変動させるVRゲーム体験の評価"
img: boomshin.png
categories: [research]
date: "2022-09-28"
tags: [XR, Haptics, Robot, Unity]
---

VR空間における触覚提示の有無を時空間的に切り替えることがVRゲーム体験に及ぼす影響を調査した。


<!--more-->


VR体験において触覚提示の重要性が主張されている一方、アクチュエーターの動作速度と動作範囲の制約により、完全な触覚提示を行うことは難しい。触覚がない物体でも、適切なパターンにしたがって触覚がある物体と組み合わせて提示することで、VR体験のエンターテインメント性の向上に貢献できるのではないかと考えた。

接触時に触覚が得られる物体／得られない物体を、それぞれ実体／分身と名付けた。
プレイヤーはVR空間内に見えているターゲットをハンマーで叩くゲームをプレイする。
触覚提示には移動ロボットをベースとした遭遇型触覚ディスプレイを用いており、触覚を提示する際には視覚的なターゲットと同じ位置に、触覚を提示しない際にはあえてそこからずれた位置にロボットを移動させる。
両者の時間的な出現パターンを従属変数とし、VRゲーム体験の印象を評価した。

その結果、実体あるいは分身のみの場合よりも、両者が混在している場合のほうがゲームにおける驚きおよび満足感が高くなることが明らかになった。また、ゲーム中に実体の出現頻度を急激に変化させることで、より大きな印象変化を提示可能であることが示された。

<!-- toioとの比較もした -->


{{< figure src="/images/boomshin/boomshin_1.png" class="img-article">}}

{{< figure src="/images/boomshin/boomshin_2.png" class="img-article">}}


# Publication
- 奥谷 哲郎, 田井 普, 中西 泰人. (2022). Boomshin: 触覚提示の有無を時間的に変動させるVRゲーム体験の評価. インタラクション2022論文集. http://www.interaction-ipsj.org/proceedings/2022/data/pdf/4P01.pdf.
- Tetsuro Okuya, Amane Tai, Yasuto Nakanishi. (2022). Boomshin: Evaluation of VR Game Experiences with Switching the Presence of Haptic Feedback. ICAT-EGVE 2022 – Posters and Demos. https://doi.org/10.2312/EGVE.20221311.
- 奥谷 哲郎, 中西 泰人. (2023). Boomshin: 触覚提示の有無を時空間的に切り替えるVRゲーム体験の評価. 日本バーチャルリアリティ学会　ハプティクス研究委員会 第30回研究会.

# Movie
{{<youtube "Dxh3Szwg3nM">}}

# Presentation
{{< embed-pdf url="../pdf/boomshin.pdf" >}}



