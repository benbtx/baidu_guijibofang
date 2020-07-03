# baidu_guijibofang
百度轨迹播放

调用百度地图API实现路线的轨迹回放功能其实很简单，只要搞懂以下几点即可：

1.需要用Polyline方法先绘制好路线图

2.用Marker添加标注点

3.关键一步，通过结合定时器，使用Marker创建的标注点实例的setPosition改变标注点位置，实现播放功能
