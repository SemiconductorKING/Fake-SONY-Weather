# Fake-SONY-Weather

### 这是一个仿索尼手机自带天气预报的webApp。

>1. Vue.js(用了组件vue-cookies)
>
>2. Flex+REM(使用lib-flexible方案)
>
>3. swiper.js
>
>4. API(万年历提供<http://wthrcdn.etouch.cn/weather_mini?city=>城市名)

天气预报初次打开会往cookie储存预制的五个城市（demo展示），用户之后做出的修改（增加删除城市）会同步到cookie里，现在删光所有城市会恢复初始五个城市状态（方便调试）。

天气预报的界面左右滑动使用的是swiper，可以用触屏鼠标和键盘控制城市天气页面的切换，menu侧栏的城市列表与天气预报滑动页面做了联动，点击可以做出相应的跳转。
