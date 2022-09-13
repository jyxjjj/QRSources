# 第一个问题

注意到锁屏组件中的日期格式如图：

https://raw.githubusercontent.com/jyxjjj/QRSources/main/2022-09-13-Apple-iOS-FR/1.jpg

想修改成 2022-09-13 这样的 Y-m-d 格式

于是去了

https://raw.githubusercontent.com/jyxjjj/QRSources/main/2022-09-13-Apple-iOS-FR/2.jpg

发现了这样一个设置

https://raw.githubusercontent.com/jyxjjj/QRSources/main/2022-09-13-Apple-iOS-FR/3.jpg

虽然还不符合使用减号而不是斜杠的需求，但至少是数字了

但是设置后返回图2

发现底部的日期格式并没有改变，再进去图3，发现他使用的是长日期格式

# 第二个问题

想让锁屏界面显示四个设备的电池信息：

DEMO如：

https://raw.githubusercontent.com/jyxjjj/QRSources/main/2022-09-13-Apple-iOS-FR/4.jpg

实际想要的如：

https://raw.githubusercontent.com/jyxjjj/QRSources/main/2022-09-13-Apple-iOS-FR/5.jpg

但是得到的结果是图4。

其中：134三个设备使用了手动选择设备，而设备2无法选择MagSafe外接电池。只能通过自动。

于是只能在断开耳机后，显示如：

https://raw.githubusercontent.com/jyxjjj/QRSources/main/2022-09-13-Apple-iOS-FR/6.jpg

这样的效果。

那么断开耳机前，设备2就会和设备3或设备4一致，无法正常显示MagSafe电池的信息。

# 第三个问题

组件数量会不会太少？