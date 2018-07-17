# DataRenderer2D subpage 

[PatchNote](PatchNode.md)

[AssetStore(commercial)](https://assetstore.unity.com/packages/tools/modeling/data-renderer-2d-102377)

[FreeVersion](https://github.com/geniikw/drawLine)
- purpose is same. draw bezier which can animate by unity3d animator. but the two source codes are completely different.
- old version.
- not optimazed(used linq, more use stack,heap memory) Nevertheless, changing the mesh in real time causes a lot of gc.
- less utility, less option, less featured. 
- not managed.

DataRenderer2D is tool allow you can create mesh base data. you can create line, polygon and sinwave. Also you can  animate these mesh by modify data using Unity3d animator.

* this is not source code repository. only handle guide and patch note. 

## Bezier line
- Each node has control point and width.
- set line drawing rate using start rate and end rate.

![bezier](bezier.gif)

## Polygon
- various method to draw polygon.
- count, scale, inner ratio.

![polygon](polygon.gif)

## Sinwave
![sin](sin.gif)

## Hole
![hole](hole2.gif)
