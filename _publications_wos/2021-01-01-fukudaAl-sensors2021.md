---
title: "DSSM: Distributed Streaming Data Sharing Manager"
collection: publications_wos
permalink: /publication/wos/fukudaAl-sensors2021
year: 2021
date: 2021-01-01
venue: 'Sensors'
author: 'Hiroaki Fukuda, Ryota Gunji, Tadahiro Hasegawa, Paul Leger, Ismael Figueroa'
paperurl: 'https://www.mdpi.com/1424-8220/21/4/1344'
doi: '10.3390/s21041344'
quartil: 1
---

# Abstract

Developing robot control software systems is difficult because of a wide
variety of requirements, including hardware systems and sensors, even though
robots are demanding nowadays. Middleware systems, such as Robot Operating
System (ROS), are being developed and widely used to tackle this difficulty.
Streaming data Sharing Manager (SSM) is one of such middleware systems that
allow developers to write and read sensor data with timestamps using a Personal
Computer (PC). The timestamp feature is essential for the robot control system
because it usually uses multiple sensors with their own measurement cycles,
meaning that measured sensor values with different timestamps become useless
for the robot control. Using SSM allows developers to use measured sensor
values with the same timestamps; however, SSM assumes that only one PC is used.
Thereby, if one process consumes CPU resources intensively, other processes
cannot finish their assumed deadlines, leading to the unexpected behavior of a
robot. This paper proposes an SSM middleware, named Distributed Streaming data
Sharing Manager (DSSM), that enables distributing processes on SSM to different
PCs. We have developed a prototype of DSSM and confirmed its behavior so far.
In addition, we apply DSSM to an existing real SSM based robot control system
that autonomously controls an unmanned vehicle robot. We then reveal its
advantages and disadvantages via several experiments by measuring resource
usages.