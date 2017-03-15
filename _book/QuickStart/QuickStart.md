# 地面站系统
The first step is to [download](download_and_install.md) and install QGroundControl. Below is the screen you will see when no vehicle is connected.
<br>
<br>
![](BootToFly.jpg)
<br>

![](SettingsViewButton.jpg) **[Settings](../SettingsView/SettingsView.md)**
<br>Configure the QGroundControl application.

![](SetupViewButton.jpg) **[Setup](../SetupView/SetupView.md)**
<br>Configure and tune your vehicle.

![](PlanViewButton.jpg) **[Plan](../PlanView/PlanView.md)**
<br>Create autonomous missions.

![](FlyViewButton.jpg) **[Fly](../FlyView/FlyView.md)**
<br>Monitor you vehicle(s) while flying, including streaming video.

# Connecting the drone
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
