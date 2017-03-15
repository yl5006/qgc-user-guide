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
在屏幕中上方，您将看到计划工具。 工具从上到下的顺序是：

* 添加航点
* 网格航线（Survey.md）
* 同步
* 中心地图
* 地图类型
* 放大/缩小

### 添加航点
单击以激活添加航点命令工具。 当激活时，点击地图将在点击的位置添加新的任务命令。 该工具将保持有效，直到您再次单击它。

### 同步
同步工具允许您将任务来回移动到您的无人机或文件。 *飞行任务之前，您必须确保将您的任务发送到您的无人机。*该工具变为红色，以指示您对您的任务的更改，您尚未发送任务到您的无人机。

同步工具提供以下功能：

* 发送到无人机
* 从无人机载入
* 保存到文件
* 从文件加载
* 移除所有航点

### 扫描航线

[扫描航线](Survey.md) 允许您在多边形区域上生成网格航线。

### 任务命令编辑
单击任务命令以显示其编辑器，它允许您指定命令的值。 您也可以通过单击命令名称“航点”(带下划线)更改命令的类型。 这允许您从设置可用命令中选择来构建您的任务。 命令名称的下方是你可以编辑改命名的参数，命令的右方是 插入和 删除 航点命令。

### Planned Home Position
A mission always has a "Planned Home Position" associated with it. This is used to simulate the home position of the vehicle such that waypoint lines can be drawn correctly to the first actual waypoint. Keep in mind that the actual home position for a mission is set by the vehicle and may differ from the "planned" home position if you don't begin your mission with the vehicle in the same location as "planned".

## Mission Display
In the center of the map you will see a visualization of your current mission. You can click on the inicators to select then and then you can also drag them around to move them.

## Mission Height Display
At the bottom of the map you will see a representation of the height differences between your mission commands. To the left of that is information for the currently selected command relative to the previous command. For example: Distance from previous waypoint.