# SPLIT POLYGON

## Author

Uros Ilic

### contact:
uros92vozd@gmail.com

### About plugin

Split polygon is a QGIS plugin developed to solve the problem of dividing polygons into different ways. This can be very useful in jobs like land parceling and many others.
First, I must note that the biggest aspect of this division problem is the polygon shape. So, to simplify things I limited the program to work only with convex polygons because there is always a solution, otherwise the things may be complicated because of the algorithms nature.
The user can define 4 ways of dividing by himself. The offered options of division are:

- one cut by entered area
- one cut once by entered percentage of polygons area
- multiple cuts into equal parts
- multiple cuts into parts with an equal width

The other parameter that user has to input is the angle of the division. By th at, he can define whether he wants to cut it, for example, horizontal from north to south or either vertical from east to west or any other way. Also, you can choose if you want to cut only selected polygons.
Each sub-polygon inherits all of the attributes as well as the projection from its parent polygon.


![screenshot_1](https://user-images.githubusercontent.com/32105551/30648433-62d4cd50-9e1e-11e7-867b-e9dc4bed0d66.jpg)

