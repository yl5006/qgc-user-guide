# 飞行页面

![](../QuickStart/ConnectedVehicle.jpg)
飞行视图是飞行您的无人机时将使用的主视图。 您可以在地图视图和视频视图（如果有）之间切换。

## 飞行工具栏
在屏幕的正中间上方，你会看到飞行工具。 工具从左到右的顺序是：
* 定位地图中心
* 地图类型
* 地图缩放大/小
* 地面站警告声音提示
* 虚拟遥控

### 定位地图中心
定位地图中心工具允许您地图以各种点（如起始位置，无人机等）居中。

### 地图类型
此工具允许您更改街道，卫星和混合（街道+卫星）之间的当前地图类型。 默认地图提供程序是Bing，因为它似乎提供更好的混合地图。 您可以从“设置”的“系统设置”页面更改地图提供商。

## 视频显示
在显示屏的左下角，您将看到视频输出。 地面站系统支持RTP和RTSP视频流通过您的车辆UDP连接。 它还支持直接连接的UVC设备支持。 

By clicking on the video you can make it be the main display for the Fly view.

## Instrument Panel
To the right is an instrument panel showing you current information on your vehicle. The center section of the panel has multiple pages. You can switch between pages by clicking on the center section. 

### Telemetry page

<img src="InstrumentTelemetryPage.jpg" style="width: 100px;"/>

The values shown within the telemetry page can be configured by clicking on the small gear icon.

### Vehicle Health page

<img src="InstrumentHealthPage.jpg" style="width: 100px;"/>

This page shows you the health of the systems within your Vehicle. If any of the systems switchs from healthy to unhealthy this page will automatically be switched to.

## Guided Bar
At the bottom of the view is the Guided Bar. The guided bar allows to to interact with your vehicle directly from the QGroundControl application. Options available vary by Vehicle and current Vehicle state. 

Some of the possible options are:

* Arm, Disarm, Emergency Stop
* Takeoff
* Change altitiude
* Go to location
* RTL
* Pause
