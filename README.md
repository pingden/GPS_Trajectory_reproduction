# GPS参数提取及轨迹重现

> 本项目分为两个版本：
>
> ​	1、基于百度地图API的轨迹快速重现
>
> ​	2、基于Leaflet的状态及轨迹重现
>
> 两者均采用在线地图，都需要Internet的支持。



### 1、基于百度地图API的轨迹快速重现

### 1.1、功能简介

- 数据提取：提取出GPS文件中的坐标信息
- 坐标转换：原始坐标转化成百度坐标
- 轨迹描绘：根据提取出来的坐标信息将轨迹一次性描绘出来
- 支持地图的放大与缩小



### 1.2、效果展示

![GPS_fast 00_00_00-00_00_30~1](https://cdn.jsdelivr.net/gh/pingden/mypic/img/GPS_fast%2000_00_00-00_00_301.gif)



### 1.3、项目实现

> 查看项目实现详情与源码请转到[详情页，点击跳转](https://pingden.github.io/archives/5bb786c7.html)



## 2、基于Leaflet的状态及轨迹重现

### 2.1、功能简介

- 数据提取：提取出GPS文件中的坐标、速度、高度等信息
- 坐标转换：原始坐标转化成其他坐标系
- 轨迹描绘：根据提取出来的信息将轨迹逐点描绘出来，并显示相应的状态信息
- 支持地图的放大与缩小
- 支持图层切换，MapBox提供的图层支持国外的高级别卫星地图



### 2.2、效果展示

![GPS_Leaflet](https://cdn.jsdelivr.net/gh/pingden/mypic/img/GPS_Leaflet.gif)



### 2.3、项目实现

> 项目体验地址
>
> 查看项目实现详情与源码请转到[详情页，点击跳转](https://pingden.github.io/archives/5bb786c7.html)

