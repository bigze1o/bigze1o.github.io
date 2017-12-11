---
layout: post
title: Dự đoán liên kết dựa trên hướng tiếp cận máy học
description: "Link prediction with machine learning approach"
modified: 2017-12-11
tags: [link-prediction]
categories: [data-mining]
image:
    feature: feature.jpg
    credit: dargadgetz
    creditlink: http://www.dargadgetz.com/ios-8-abstract-wallpaper-pack-for-iphone-5s-5c-and-ipod-touch-retina/
---

Khai thác dữ liệu trên dữ liệu lớn là một trong những bài toán được quan tâm nhiều nhất hiện nay. Những thành tựu nghiên cứu của bài toán dự đoán liên kết có thể được áp dụng trong nhiều lĩnh vực của cuộc sống như: tiếp thị sản phẩm, dịch vụ thương mại điện tử, phát hiện cấu trúc mạng lưới tội phạm, nghiên cứu các bệnh di truyền qua gen, đề xuất kết bạn trong mạng xã hội,.. Trong bài viết này, tôi giới thiệu và giải quyết về bài toán dự đoán liên kết trong mạng dựa trên hướng tiếp cận máy học.

## 1.Phát biểu bài toán:
Mạng lưới mạng xã hội 
<img src="http://www.sciweavers.org/tex2img.php?eq=%5Clim_%7Bx%20%5Cto%20a%7D%20%5Cfrac%7Bf%28x%29%20-%20f%28a%29%7D%7Bx%20-%20a%7D&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0" align="center" border="0" alt="\lim_{x \to a} \frac{f(x) - f(a)}{x - a}" width="124" height="44" />