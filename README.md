# ios2win
Bark的反向实现，从ios设备将信息发送到win

需要用到的东西

一个IOS设备 使用快捷指令APP
一台WINDOWS电脑 使用易语言（模块引用：CCHTTP、精易模块）当然你能用其它语言更好

windows用来做服务端，iOS需要与windows在同一网络下（有公网可忽略）

使用易语言引入cchttp模块并创建网站，注册一个接口，GET/POST方式都可以，接口取回数据即可，源码如下。

![image](https://user-images.githubusercontent.com/30887695/168523458-df4ee585-1150-4ea9-9b6e-d72ac6d63407.png)
接下来在IOS新建快捷指令

![image](https://user-images.githubusercontent.com/30887695/168523474-583484cb-cadf-40fd-848f-d4c0455bc398.png)
打开“在共享表单中显示”选项，指令如下，注意修改IP地址和接口字段

![image](https://user-images.githubusercontent.com/30887695/168523482-843a4d42-dfd0-4cf2-9c0b-466a28fcf2f0.png)
在windows上运行服务器，手机上复制一段文本后运行快捷指令。效果图：

![image](https://user-images.githubusercontent.com/30887695/168523496-034fe815-5a3e-41ae-8684-5454b29c2bbd.png)
当然，你可以通过在ios设置轻点两下背面运行ios2win快捷指令，也可以将快捷指令绑定在“小圆点”里

![image](https://user-images.githubusercontent.com/30887695/168523517-c1d06589-b609-4829-a39e-32add96c1cea.png)
利用ios的快捷指令，你甚至可以把手机做成一个扫码枪：

![image](https://user-images.githubusercontent.com/30887695/168523527-b8c3b2ce-77ef-4ca1-bd60-78e74e4a1022.png)
运行效果：

![image](https://user-images.githubusercontent.com/30887695/168523535-794ef54c-3cc5-4424-b4d2-ac387fc2b1df.png)
以上只是一个简单的实现，只要有创意，利用好快捷指令可以达成更多功能


# 快捷指令
ios2win
https://www.icloud.com/shortcuts/e391661ef57a4bdebe24cf06a8140c38

扫码枪
https://www.icloud.com/shortcuts/832aeb1174d9445c8fa17436df2951fc
