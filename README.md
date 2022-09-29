# TVBoxOSC
不懂java代码，在开源项目中做一些常见的小修改。
改APP名字，版本号，替换app图标，替换背景图片，内置源。共存（com.github.tvbox.osc）。

![9c47ad0a6e7445b825be058e22888b4](https://user-images.githubusercontent.com/102397160/177658190-7863e8bb-619f-4ef3-88b6-2cb5a0c9084b.png)
![7866862a3f3636c9d57527ce175057c](https://user-images.githubusercontent.com/102397160/177658195-ca687aed-427a-4443-af35-df92240729bb.png)
![fe07333d50600375c49612855018fdd](https://user-images.githubusercontent.com/102397160/177658197-ae104e2c-66d9-4e5f-9ea9-60675323574b.png)
![微信图片_20220728040003](https://user-images.githubusercontent.com/102397160/181361340-3d6f361c-8199-4a2b-a445-786ec9dad028.jpg)
调整设置画面选项的位置方法：打开，两块复制调换一下就行。

![微信图片_20220728040329](https://user-images.githubusercontent.com/102397160/181361920-cdcdffa7-5cd0-4b10-af2d-e850d59ae219.png)





# 如何在自己的App中接入猫影视TV的自定义jar

```
思维没有边界 一切皆有可能
```
:rocket:[**TG交流群**](https://t.me/catvodtv_offical)

![logo](app/src/main/res/drawable-xhdpi/app_icon.png)



使用 DexClassLoader 和 反射 获取jar包内的爬虫类，并调用相关数据接口，App中解析爬虫接口返回的数据展示界面及其他相关处理即可，只是个例子，道理都一样。
