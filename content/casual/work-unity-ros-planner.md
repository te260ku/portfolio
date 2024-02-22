---
layout: post
title:  "Unity ROS Action Planner"
img: unity-ros-planner.png
categories: [casual]
date: "2022-09-28"
tags: [Interface, Unity, ROS]
---

UnityからROSのトピックに任意のメッセージを送信するためのインターフェースを実装した。


<!--more-->

UnityとROSの通信にはUnity-Robotics-Hubに含まれるROS-TCP-EndpointとROS-TCP-Connectorを使用した。
任意のメッセージ型を選択して、プロパティの値とトピック名を指定するとメッセージを送信できる。シーケンスに対応しており、指定秒数ごとに送信するメッセージをプログラムすることもできる。



# Repository
- https://github.com/te260ku/unity-ros-action-planner

