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
http://www.HostMath.com/Show.aspx?Code=%5Cfrac%7B-b%5Cpm%5Csqrt%7Bb%5E2-4ac%7D%7D%7B2a%7D
<script type="text/javascript" src="http://www.hostmath.com/Math/MathJax.js?config=OK"></script>
\[\frac{-b\pm\sqrt{b^2-4ac}}{2a}\]
<math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
  <mfrac>
    <mrow>
      <mo>&#x2212;<!-- − --></mo>
      <mi>b</mi>
      <mo>&#x00B1;<!-- ± --></mo>
      <msqrt>
        <msup>
          <mi>b</mi>
          <mn>2</mn>
        </msup>
        <mo>&#x2212;<!-- − --></mo>
        <mn>4</mn>
        <mi>a</mi>
        <mi>c</mi>
      </msqrt>
    </mrow>
    <mrow>
      <mn>2</mn>
      <mi>a</mi>
    </mrow>
  </mfrac>
</math>