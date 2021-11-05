# Minifps

## 项目

本项目使用游戏引擎Unreal Engine 4.27，以蓝图开发为主。工程文件存放于本仓库中，打包的Windows和Android程序可于release中下载。

## 游戏

简单实现了FPS游戏的基本操作和游戏流程。
- WASD控制人物移动，鼠标移动控制视角，鼠标左键控制射击；移动端操作以左右摇杆和开火键替代
- 游戏画面中心红点为准星，射击命中会加一分，显示在画面左上角
- 敌人被命中后会被击倒，1秒后消失，然后在一定距离内随机位置刷新新敌人
- 画面正上方显示倒计时，设置为20秒，倒计时结束后命中敌人不再有效，2秒后游戏自动退出

## 素材来源及参考资料
- https://quaternius.com/
- https://www.unrealengine.com/marketplace
- https://www.youtube.com/watch?v=bQtbhWKsQKA