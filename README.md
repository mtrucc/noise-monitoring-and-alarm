# 噪音监控与报警
有时候会制造一些奇怪的噪音（打呼噜），我打算自己制作一个噪音监控与报警的模块。

## 预期效果
精确识别自己发出的噪音（不小心发出的除外），让灯亮起来提醒自己不要再发出声音了。

## 买的工具
- Nodemcu 或者 Arduino板子一个
- 声音检测模块
- LED灯一个
- PWM发生器
- 其他（什么杜邦线啊，电阻啊自己准备）

## 制作步骤一：测试声音检测模块
忘记下载Arduino软件了
[Arduino下载](https://www.arduino.cc/en/Main/Software)

插上Arduino板子到电脑上，连上声音传感器

不要问我具体步骤，该方案放弃了，声音传感器麦克风灵敏度不高，理想和现实是有差距的


## 2019年2月24日 项目被迫中断
研究了一下，这种高灵敏度的麦克风价格比较贵
- 手机送话器原件（买了也不会用系列）
- 采访麦（贵）
- 电容麦（我看到个联想的 59元，但是评价中发现声音小）
- mems硅麦传感器（买了也不会用系列）

## 新的发现
苹果手机可以获取及其微小的声音

## 新的方案（设想）
IOS开发，声音获取，物联网报警。