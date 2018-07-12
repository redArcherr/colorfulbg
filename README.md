# colorfulbg
颜色变换库使用方法：
colorful.js用户自定义关键帧的颜色，通过css3的transition实现颜色渐变功能。在低版本浏览器会通过javascript来实现。
简单用法：startLoop(document.getElementById('page'));

example：
var page = document.getElementById('page');
var array = [[255,255,0],[0,220,220],[153,51,0]];
var msec = 3000;
startLoop(page,array,msec);
