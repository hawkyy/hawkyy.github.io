---
layout: post
title:  "Linux下抓WiFi包"
date:   2015-05-21 14:06:05
categories: Linux
excerpt: 
---

* content
{:toc}

sudo ifconfig wlan0 down

sudo iwconfig wlan0 mode monitor

sudo iwconfig wlan0 channel X

sudo ifconfig wlan0 up