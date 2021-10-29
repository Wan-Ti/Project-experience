# Project-experience
## 大屏制作过程 6/3 - 6-15
知识点：SCSS使用，E-chart使用，参数配置，响应式布局；重点在于掌握了flex布局，改变以往的float布局。
SCSS关键代码：
``` 
@function vw($data) {
  @return $data / 1920 * 100 + vw;
}

@function vh($data) {
  @return $data / 1080 * 100 + vh;
}
```
使用echart完成了地图下钻功能，了解echart相应配置如何配置；
## 隧道人员轨迹回放 6/15 - 7/3
该项目难点在于根据后台传过来的数据作为坐标点，移动图标
## FlowerLex 7/3 - 9/28
