# 仿QQ6.x侧滑菜单

通过ViewDragHelper实现了一个仿QQ6.x的滑动菜单，该菜单具有以下特点：

  1. 可以根据滑动距离和滑动速度来确定拖动结束后菜单的状态
  2. 菜单会跟随主界面的滑动而滑动，它们之间的距离具有一定的线性关系
  3. 为菜单增加阴影遮罩，其透明度随主界面位置的变化而变化
  4. 裁剪掉菜单被主界面遮盖的部分，避免过渡绘制
  
### 效果
![](https://github.com/bestTao/CoordinateMenu/blob/master/demo.gif)<br/>
