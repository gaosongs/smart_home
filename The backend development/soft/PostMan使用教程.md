# postman安装使用教程---图文讲解

# 一、安装postman

## 1，安装包安装

官网下载地址:[https://www.getpostman.com](https://www.getpostman.com/)
选择好对应的版本下载,下载完后直接安装
![这里写图片描述](PostMan使用教程.assets/20170424114544583)

## 2，插件包安装

可以在谷歌的应用商店里面找到,或者在网上下载。
准备了一个配置完整的postman插件包
http://download.csdn.net/detail/qazwsxpcm/9823420
下载完成后 打开谷歌浏览器
打开扩展程序，勾选开发者模式,点击加载文件，选择解压后的插件包
![这里写图片描述](PostMan使用教程.assets/20170424114603256)

![这里写图片描述](PostMan使用教程.assets/20170424114615955)

# 二、postman使用

## 1，启动postman

打开谷歌浏览器，点击应用，点击postman，或者在开发工具里面也可以启动postman。

![这里写图片描述](PostMan使用教程.assets/20170424114656992)

![这里写图片描述](PostMan使用教程.assets/20170424114706455)
第一次启动postman 会要求输入用户名和密码，如果没有的话，关闭，再次启动就可以直接进入了
![这里写图片描述](PostMan使用教程.assets/20170424114734243)

![这里写图片描述](PostMan使用教程.assets/20170424114744633)

## 2，postman使用

将url复制到输入框中,选好格式,然后点击send,就可以调用了。Body是返回的参数，可以判断是否调用成功.
注:如果是https的的请求,可以在设置setting里面去掉ssl验证,或者现在谷歌浏览器先刷一遍,点击继续前往便可以调用了。
![这里写图片描述](PostMan使用教程.assets/20170424114811743)
保存请求
方便下次调用
![这里写图片描述](PostMan使用教程.assets/20170424114819409)
导出、加载请求
换环境之后只需加载以前的请求便拥有和以前一样的配置
![这里写图片描述](PostMan使用教程.assets/20170424114826884)
![这里写图片描述](PostMan使用教程.assets/20170424114849487)
代码生成
点击Generate Code
选择开发语言便可以生成代码
![这里写图片描述](PostMan使用教程.assets/20170424114857784)