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
该项目用到的技术包括：Vue，Vuex,VueRouter,Vue-cli,axios，ES6等；
在制作过程中遇到了如何进行认证登录，如何远程摄像头的位置，如何进行聊天等；
该项目作为从学习过程中从原生JS操作DOM到使用Vue作为框架搭建项目的一个过渡；
同时也学会了在前后端分离过程中如何与后台进行接口对接；

