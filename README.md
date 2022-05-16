# ios2win
Bark的反向实现，从ios设备将信息发送到win

需要用到的东西

一个IOS设备 使用快捷指令APP
一台WINDOWS电脑 使用易语言（模块引用：CCHTTP、精易模块）当然你能用其它语言更好
windows用来做服务端，iOS需要与windows在同一网络下（有公网可忽略）

使用易语言引入cchttp模块并创建网站，注册一个接口，GET/POST方式都可以，接口取回数据即可，源码如下。

http://blog.tutool.cn:82/wp-content/uploads/2022/05/image.png
接下来在IOS新建快捷指令

http://blog.tutool.cn:82/wp-content/uploads/2022/05/8d97f0eea30cc2a35f8abd699d821d3-473x1024.jpg
打开“在共享表单中显示”选项，指令如下，注意修改IP地址和接口字段

http://blog.tutool.cn:82/wp-content/uploads/2022/05/b2a9c73fa619832bf3bf62507554c9a-473x1024.jpg
在windows上运行服务器，手机上复制一段文本后运行快捷指令。效果图：

http://blog.tutool.cn:82/wp-content/uploads/2022/05/image-1.png
当然，你可以通过在ios设置轻点两下背面运行ios2win快捷指令，也可以将快捷指令绑定在“小圆点”里

http://blog.tutool.cn:82/wp-content/uploads/2022/05/e2b7488208c33b85c5be39ecbc97d04-473x1024.jpg
利用ios的快捷指令，你甚至可以把手机做成一个扫码枪：

http://blog.tutool.cn:82/wp-content/uploads/2022/05/62eb702341d886de40abb903bca3e85-473x1024.jpg
运行效果：

http://blog.tutool.cn:82/wp-content/uploads/2022/05/image-2.png
以上只是一个简单的实现，只要有创意，利用好快捷指令可以达成更多功能

# 快捷指令
ios2win
https://www.icloud.com/shortcuts/e391661ef57a4bdebe24cf06a8140c38

扫码枪
https://www.icloud.com/shortcuts/832aeb1174d9445c8fa17436df2951fc
