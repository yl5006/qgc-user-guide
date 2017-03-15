# 航线规划

![](PlanView.jpg)

航线规划计划视图用于为您的无人机规划自主任务。 一旦任务被计划并发送到无人机，你切换到 [飞行页面](FlyView.md) 来飞行任务

如果你设置里地理围栏，你也可在航线规划试图中看见它.

上图显示了一个简单的任务，从起飞开始，飞过两个航点，然后返航。

创建任务的步骤是：

1.切换到航线规划视图
2.向任务添加命令并根据需要进行编辑
3.将任务发送到无人机
4.切换为飞行视图并飞行您的任务

## 飞行页面工具
在屏幕的左边缘，您将看到计划工具。 工具从上到下的顺序是：

*添加命令
* 自动扫描航线（Survey.md）
* 同步
*中心地图
*地图类型
*放大/缩小

### Add Commands
Click to activate the Add Commands tool. While active, clicking in the map will add new mission commands at the clicked location. The tool will stay active until you click it again.

### Sync
The Sync tools allows you to move Missions back and forth to your Vehicle or a file. *Before you fly a mission you must be sure to send your Mission to your vehicle.* The tool will change to have an "!" within it to indicate that you have changes to your Mission which you have not sent to your vehicle. 

The Sync tool provides the following functionality:

* Send to Vehicle
* Load from Vehicle
* Save to File
* Load from File
* Remove All

### Survey

[Survey](Survey.md) allows you to fly a grid pattern over a polygonal area.

## Mission Command List
On the right edge of the display is the list of mission commands for this mission. You can click on one of these to edit the values for the item. Above are a set of options to switch between editing the Mission, GeoFence and Rally Points.

### Mission Command Editors

Click on a mission command to show its editor which allows you to specify the values for the command. You can also change the type of the command by clicking on the command name, "Waypoint" in this example. This allows you to pick from the set up available commands to build your mission. To the right of the command name is a menu you can open by clicking. This menu provides you access to additional options such as Insert and Delete.

### Planned Home Position
A mission always has a "Planned Home Position" associated with it. This is used to simulate the home position of the vehicle such that waypoint lines can be drawn correctly to the first actual waypoint. Keep in mind that the actual home position for a mission is set by the vehicle and may differ from the "planned" home position if you don't begin your mission with the vehicle in the same location as "planned".

## Mission Display
In the center of the map you will see a visualization of your current mission. You can click on the inicators to select then and then you can also drag them around to move them.

## Mission Height Display
At the bottom of the map you will see a representation of the height differences between your mission commands. To the left of that is information for the currently selected command relative to the previous command. For example: Distance from previous waypoint.