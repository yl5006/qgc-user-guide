# 飞行页面

![](../QuickStart/ConnectedVehicle.jpg)
飞行视图是飞行您的无人机时将使用的主视图。 您可以在地图视图和视频视图（如果有）之间切换。

## 飞行工具栏
在屏幕的正中间上方，你会看到飞行工具。 工具从上到下的顺序是：
* Center map
* Map Type
* Zoom In/Out

### Center Map
The Center Map tool allow you to center the map around various points such as home position, vehicle and so forth.

### Map Type
This tool allows you to change the current map type between Street, Satellite and Hybrid (Street+Satellite). The default map provider is Bing since it seems to provide better Hybrid maps. You can change the map provider from the General page of Settings.

## Video
At the lower left of the display you will see video output. QGroundControl supports RTP and RTSP video streaming over your vehicles UDP connection. It also support directly connected UVC device support. More details on QGC Video support can be found on the [Video README](https://github.com/mavlink/qgroundcontrol/blob/master/src/VideoStreaming/README.md).

By clicking on the video you can make it be the main display for the Fly view.

## Instrument Panel
To the right is an instrument panel showing you current information on your vehicle. The center section of the panel has multiple pages. You can switch between pages by clicking on the center section. 

### Telemetry page

<img src="InstrumentTelemetryPage.jpg" style="width: 100px;"/>

The values shown within the telemetry page can be configured by clicking on the small gear icon.

### Vehicle Health page

<img src="InstrumentHealthPage.jpg" style="width: 100px;"/>

This page shows you the health of the systems within your Vehicle. If any of the systems switchs from healthy to unhealthy this page will automatically be switched to.

### Vibration Clipping page

<img src="InstrumentClipPage.jpg" style="width: 100px;"/>

This page show you current vibration values and clip counts.

## Guided Bar
At the bottom of the view is the Guided Bar. The guided bar allows to to interact with your vehicle directly from the QGroundControl application. Options available vary by Vehicle and current Vehicle state. 

Some of the possible options are:

* Arm, Disarm, Emergency Stop
* Takeoff
* Change altitiude
* Go to location
* RTL
* Pause
