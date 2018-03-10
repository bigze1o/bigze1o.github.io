---
layout: post
title: Dự đoán liên kết dựa trên hướng tiếp cận máy học
description: "Link prediction with machine learning approach"
modified: 2017-12-11
tags: [link-prediction]
categories: [data-mining, machine-learning]
image:
    feature: feature.jpg
    credit: dargadgetz
    creditlink: http://www.dargadgetz.com/ios-8-abstract-wallpaper-pack-for-iphone-5s-5c-and-ipod-touch-retina/
---

Khai thác dữ liệu trên dữ liệu lớn là một trong những bài toán được quan tâm nhiều nhất hiện nay. Những thành tựu nghiên cứu của bài toán dự đoán liên kết có thể được áp dụng trong nhiều lĩnh vực của cuộc sống như: tiếp thị sản phẩm, dịch vụ thương mại điện tử, phát hiện cấu trúc mạng lưới tội phạm, nghiên cứu các bệnh di truyền qua gen, đề xuất kết bạn trong mạng xã hội,.. Trong bài viết này, tôi giới thiệu và giải quyết về bài toán dự đoán liên kết trong mạng dựa trên hướng tiếp cận máy học.

## 1.Phát biểu bài toán:
Mạng lưới mạng xã hội $s$, bao gồm:
* <a href="https://www.codecogs.com/eqnedit.php?latex=E" target="_blank"><img src="https://latex.codecogs.com/svg.latex?E" title="E" /></a>: là tập các liên kết (cạnh).
* <a href="https://www.codecogs.com/eqnedit.php?latex=V" target="_blank"><img src="https://latex.codecogs.com/svg.latex?V" title="V" /></a>: là tập các đỉnh (đỉnh).

Bài toán dự đoán sự tồn tại của liên kết trong mạng có trọng số có *input* và *output* như sau:
* **Input** : thông tin về các liên kết trong mạng tại một thời điểm.
* **Output** : những liên kết sẽ được xuất hiện trong tương lai.

## 2.Tổng quan về hướng tiếp cận:

## 3. Cơ sở lý thuyết:
### 3.1 Mô hình dự đoán tổng quát
Mô hình để giải quyết bài toán dự đoán sự tồn tại của liên kết dựa theo hướng tiếp cận máy học hoạt động trên hai quá trình: *huấn luyện (thực hiện offline)* và *dự đoán (thực hiện online)*. Toàn bộ hoạt động của mô hình được biểu diễn chi tiết theo hình dưới đây:

**Hình**

Chi tiết hoạt động của hai quá trình huấn luyện như sau:
* **Quá trình huấn luyện**:
* Quá trình tiền xử lý dữ liệu (Pre-processing): ở bước này, quá trình tiền xử lý dữ liệu và đưa về cấu trúc của đồ thị mạng, với các đỉnh là các nhân tố/chủ thể đại diện, đồng thời các cạnh liên kết giữa các đỉnh thể hiện mối quan hệ tương tác với nhau.
