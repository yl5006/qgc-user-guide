# 计划 - 网格航线

调查允许您在多边形区域上创建网格线条图案。 您可以指定多边形以及适用于创建带有地理标记的图像的网格和摄像机设置的规格。

![](Survey.jpg)

要为您的调查绘制多边形，请单击“绘制”按钮，然后在地图中单击以设置多边形顶点。

网格航线有多个选项。 您可以从编辑器顶部的下拉菜单中选择主选项。

## Manual Grid
<img src="SurveyManual.jpg" style="width: 150px;"/>

手动网格选项允许您指定用手在多边形上生成网格图案的所有值。

    * 网格角     - 网格的平行飞行轨迹的角度。 例如0度将产生向南/向南行进的平行线。
    * 网格间距   - 每个平行飞行轨迹之间的距离。
    * 高度       - 飞行整个网格图案的高度。
    * 周转距离   - 在执行下一个飞行轨迹的周转之前，飞越多边形边缘的额外距离。
    * 触发距离   - 用于根据飞行距离触发摄像机拍摄的图像。

## Camera
<img src="SurveyCamera.jpg" style="width: 150px;"/>

Selecting a known camera from the option dropdown allows you to generate a grid pattern based on the camera's specifications.

* Landscape/Portrait - Specifies the orientation that the camera is placed on the vehicle.
* Image Overap - Allows you to specify the amount of overlap you want between each image.
* Altitude - Selecting this value allows you to specify the altitude for the survey. The ground resolution will be calculated and shown for the specified altitude.
* Ground resolution - Selecting this value allows you to specify the ground resolution you want for each image. The altitude required to achieve this resolution is calculated and shown.

## Custom Camera
<img src="SurveyCameraCustom.jpg" style="width: 150px;"/>

The custom camera option is similar to the known camera option. The difference is that you must specify the details for the camera specifications yourself.

* Sensor width/height - The size of the image sensor of the camera.
* Image width/height - The resolution of the image captured by the camera.
* Focal Length - The focal length of the camera lens.
