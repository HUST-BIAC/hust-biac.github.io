---
layout: pageWithLeftNav
pageType: 1
title: 中心概况
subtitle: 联系我们
cover-img: /assets/img/title.jpg
---
<!--
 * @Author: Conghao Wong
 * @Date: 2023-03-08 19:13:03
 * @LastEditors: Conghao Wong
 * @LastEditTime: 2023-04-27 19:07:17
 * @Description: file content
 * @Github: https://cocoon2wong.github.io
 * Copyright 2023 Conghao Wong, All Rights Reserved.
-->

## 联系我们

---

- 地址：湖北省武汉市洪山区珞喻路1037号华中科技大学国家防伪工程技术研究中心
- 电话：027-87544817
- 邮箱：nacerc@hust.edu.cn

<div id="map_container" style="text-align: center; width: 100%; height: 500px;"></div>
<!-- <div style="text-align: center;">
     <img src="/assets/img/intro/c1.png">
</div> -->

<script src="http://api.map.baidu.com/api?type=webgl&v=1.0&ak=eAySKs5DdAvG8nBCo2W7vxANtUUryWgw"></script>
<script>
     var map = new BMapGL.Map('map_container'); // 创建Map实例
     map.centerAndZoom(new BMapGL.Point(114.423166, 30.51477), 15); // 初始化地图,设置中心点坐标和地图级别
     map.enableScrollWheelZoom(true); // 开启鼠标滚轮缩放
     // 创建点标记
     var marker1 = new BMapGL.Marker(new BMapGL.Point(114.423166, 30.51477));
     // 在地图上添加点标记
     map.addOverlay(marker1);
     var opts = {
          position: new BMapGL.Point(114.423166, 30.51477), // 指定文本标注所在的地理位置
          offset: new BMapGL.Size(30, -30) // 设置文本偏移量
     };
     // 创建文本标注对象
     var label = new BMapGL.Label('国家防伪工程技术研究中心', opts);
     // 自定义文本标注样式
     label.setStyle({
          color: 'blue',
          borderRadius: '5px',
          borderColor: '#ccc',
          padding: '10px',
          fontSize: '16px',
          height: '50px',
          lineHeight: '30px',
          fontFamily: '微软雅黑'
     });
     map.addOverlay(label);
</script>
