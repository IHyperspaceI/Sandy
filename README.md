ATTiny works but needs redesign as ground pours are not connected. Hence, the IMU does not get power. The focus on small packaging led to certain compromises in layout, ultimately bringing the project's downfall.
Unfortunately, KiCAD was not configured to highlight isolated GNDs, and this oversight led to the issues.
![](Photos/Schematic.png)

Top Layer:
![](Photos/Top%20layer.png)

Bottom Layer
![](Photos/Bottom%20Layer.png)