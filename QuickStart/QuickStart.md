# 地面站系统
下图是地面站系统未连接飞控状态
<br>
![](BootToFly.jpg)
<br>
![](FlyViewButton.jpg) **[飞行页面](../FlyView/FlyView.md)**
<br>飞行页面，监控无人机数据，以及图像传输

![](PlanViewButton.jpg) **[航点规划](../PlanView/PlanView.md)**
<br>航点规划页面，自动规划航点

![](SetupViewButton.jpg) **[设置](../SetupView/SetupView.md)**
<br>地面站系统设置和配置你的无人机

# 连接无人机
In most cases if you have connected to your vehicle directly via USB, through a telemetry radio or over WiFi you should not need to take any additional steps. QGroundControl should detect your vehicle and connect it automatically.

By default QGroundControl will show you the Fly view as shown here. If your vehicle requires additional setup you will be automatically shown the Setup view instead.
<br>
<br>
![](ConnectedVehicle.jpg)
<br>

You will notice that the toolbar contains additional information when it is connected. It shows you high level status for your vehicle. By clicking on any of these items you can see more detailed information. 

![](MessageToolbar.jpg) **Vehicle Messages**
<br>Click to show a dropdown of messages from the vehicle. This will change to a Yield sign if there are critical messages.

![](GPSToolbar.jpg) **GPS Status**
<br>Shows you satellite count and curent hdop.

![](RCToolbar.jpg) **RC RSSI** 
<br>RS signal strength information.

![](TelemetryToolbar.jpg) **Telemetry RSSI**
<br>Telemetry signals strength information.

![](BatteryToolbar.jpg) **Battery**
<br>Remaining battery percent.

![](FlightModeToolbar.jpg) **Flight Mode**
<br>Current flight mode. Click to change flight mode.
