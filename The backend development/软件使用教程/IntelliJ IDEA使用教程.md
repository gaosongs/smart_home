#  IntelliJ **IDEA** **2019**.3.1**安装**激活**破解**使用**教程**（更新最新到**IDEA**2020.3版本）                 

## 一、 前言

作为一枚程序员，你肯定对IntelliJ **IDEA**这个工具一点也不陌生！或许你没有用过，但你也一定听说过。作为在业界被公认为最好的java开发工具，**IDEA**每次大版本更新都备受瞩目。划重点，IntelliJ **IDEA** **2019**.3现已发布！

近期，我也是从**2019**.2版本升级到了**2019**.3.1。说实话，本次升级体验还是非常好的。最明显的一点是启动速度大大提升了。当然，也有其他方面的升级。不得不说，**IDEA**真是变得越来越好用了。

如果你是一名Java学习或开发者，很建议你将IDE转换或升级到IntelliJ **IDEA** **2019**.3.1。使用新版本**IDEA**后，你肯定会有不一样的体验，编码速度大大提升。

![img](https://img2018.cnblogs.com/blog/1363940/201912/1363940-20191213225020171-1067292590.png)

## 二、 **2019**.3.1版本主要改进

IntelliJ **IDEA** **2019**.3.1提供了重大的性能和可用性改进，包括更快的启动，主题和键盘映射插件的更容易**安装**，增强的VCS工作流以及增加了对微服务框架，MongoDB等的支持。

- **性能（Performance）**

  1. 启动时间更快。
  2. 在降低导入大型Gradle项目时的峰值内存消耗
  3. 该版本在UI层面修复了非常非常多的问题（1600+项之多，但基本对用户无感知）。
  4. 修复了各种编辑器冻结（假死），而且还加快了长方法调用链的Java类型推断。
  5. 此版本内置了Kotlin 1.3.60版本支持，从而提供了更好的性能表现。

- **可用性（Usability）**

  1. 动态插件/主题支持
  2. 更明显的滚动条显示
  3. 更平滑的鼠标滚动体验
  4. 自动配置Maven项目
  5. 更好的意图猜测上下文
  6. 对Java13的特性提供了更好的支持
  7. 支持了更多的模版语言
  8. Field Call Hierarchy字段调用树
  9. Git的使用增强

- **新的框架和技术**

  说明：这些特性是旗舰版才有的新特性，社区版是没有的。

  1. 微服务框架支持
  2. Endpoints视图
  3. Spring Web Flux支持
  4. MongoDB支持

- **修复Fix**

  1. IDE现在可以通过自制程序检测Gradle**安装**到的目录
  2. 用户界面已经得到了改进，所以现在更容易手动设置Gradle主目录
  3. IntelliJ **IDEA**现在支持通过KWallet在Linux上存储密码
  4. 对于JavaFX项目，IDE可以在Scene Builder选项卡中显示带有嵌入场景生成器的FXML文件
  5. 当SVN服务器不可用时，SVN的“身份验证要求”对话框不再弹出
  6. IDE现在在索引Git日志时显示一个进度条（新增）
  7. 现在，您可以在文件历史视图和VCS注释中选择查看何时编写了更改或提交时间戳（新增）
  8. JetBrains 运行时升级：主要是JBR 8/11的升级（由于开发者不用关心，略）

## 三、 下载**安装**

不用多说，从官网进行下载。**IDEA**官网：[https://www.jetbrains.com/**idea**/](https://www.jetbrains.com/idea/)

IntelliJ **IDEA**有旗舰版和社区版对比如下：

![img](https://img2018.cnblogs.com/blog/1363940/201912/1363940-20191213225031251-1686064265.png)

## 四、 注册激活

以下方法在最新**2019**.3.1上测试通过。只要你**安装**以下步骤操作，绝对能成功激活。当然，若资金允许，点击[https://www.jetbrains.com/**idea**/buy/](https://www.jetbrains.com/idea/buy/) 购买正版，谢谢合作！
 学生凭学生证可免费申请 https://sales.jetbrains.com/hc/zh-cn/articles/207154369-学生授权申请方式 正版授权！遇到什么问题的话，也可以联系我。操作步骤也不是很繁琐。如下：

1. 先下载压缩包解压后得到jetbrains-agent.jar，把它放到你认为合适的文件夹内。例如：**idea****安装**目录的bin目录：C:\Program Files\JetBrains\IntelliJ **IDEA** **2019**.3.1\bin
    下载地址为：链接: https://545c.com/file/23049940-413608820
    https://474b.com/file/23049940-476166098（最新 2020.3）  访问码：102530

> 最新2020.3激活方式见我的另一篇文章 https://www.cnblogs.com/leton/p/13742611.html ，直接把下载的文件拖到**idea**中，并填写**安装**参数，即可激活成功

1. 启动你的IDE，如果上来就需要注册，选择：试用（Evaluate for free）进入IDE
2. 点击**IDEA**菜单："Help" -> "Edit Custom VM Options ..."
    如果提示是否要创建文件，请点"Yes"。
    ![img](https://img2018.cnblogs.com/blog/1363940/201912/1363940-20191213225054017-9586056.png)
3. 在打开的vmoptions编辑窗口末行添加：-javaagent:/absolute/path/to/jetbrains-agent.jar
    一定要自己确认好路径(不要使用中文路径)，填错会导致IDE打不开！！！最好使用绝对路径。
    一个vmoptions内只能有一个-javaagent参数。
    示例:
   - mac:      `-javaagent:/Users/neo/jetbrains-agent.jar`
   - linux:    `-javaagent:/home/neo/jetbrains-agent.jar`
   - windows:  `-javaagent:C:\Program Files\JetBrains\IntelliJ **IDEA** **2019**.3\bin\jetbrains-agent.jar`
      ![img](https://img2018.cnblogs.com/blog/1363940/201912/1363940-20191213225115224-1859343455.png)
4. 重启你的IDE。
5. 点击IDE菜单 "Help" -> "Register..."
    支持两种注册方式：License server 和 Activation code:
   - 选择License server方式，地址填入：http://jetbrains-license-server （应该会自动填上）（**推荐此方法，方便**）
      或者点击按钮："Discover Server"来自动填充地址。
   - 选择Activation code方式离线激活，请使用：ACTIVATION_CODE.txt 内的注册码激活
      ![img](https://img2018.cnblogs.com/blog/1363940/201912/1363940-20191213225134352-185325660.png)

## 五、 一些使用方法技巧

**1、文件修改变动：**

svn文件修改后，默认只有当前文件更改而父文件没有标注，很不直观；查了一顿后，发现，可以设置；
 File—->settings—->version control—–>勾选show directories with changed descendants 

![img](https://img-blog.csdn.net/20180821201110602?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3d5dG9jc2Ru/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

 

**2、IDEA以新窗口的形式打开多个项目**

**![img](https://img-blog.csdn.net/20180821201211546?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3d5dG9jc2Ru/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)**

**3、解决tomcat中文乱码问题**

JAVA_TOOL_OPTIONS -Dfile.encoding=UTF-8

![img](https://img-blog.csdn.net/20180821201310469?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3d5dG9jc2Ru/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

![img](https://img-blog.csdn.net/20180821201411555?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3d5dG9jc2Ru/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

 

**4、同时引入多个文件方法时，文件路径会转换成\*号**

Setting--editor--code sytle--java--imports
 把Class count to...和Names count to...后边的数值调大一点。

![img](https://img-blog.csdn.net/20180821201447407?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3d5dG9jc2Ru/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

 

**5、IDEA编译特别慢。**

修改:
 File--Settings-Compiler的Addtional build process VM options
 如下配置:
 -ea -Xms2048m -Xmx2048m 

 

**6、IDEA统一编辑文件编码**

全局编码设置
 File -> Other Settings -> Default Settings

![img](https://img-blog.csdn.net/20180821201544450?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3d5dG9jc2Ru/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

Editor -> File Encodings

![img](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\20180821201609521)

**7、当idea中properties配置文件中文显示utf8编码乱码**

file->setting->editor->file encodings

把transparent native-to-ascll conversion勾选上就行了。

![img](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\20180821201638732)

 

**8、解决IDEA中tomcat启动控制台乱码问题。**

![img](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\2018082120171173)

菜单栏run- Edit Configurations 或 右上角有个向下的小箭头 

![img](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\20180821201734579)

选择你乱码的tomcat -> service->VM option，配置虚拟机编码格式为UTF-8（-Dfile.encoding=UTF-8）

![img](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\20180821201759529)

 

**9、Intellij idea用快捷键自动生成序列化id**

Intellij idea用快捷键自动生成序列化id
 类继承了Serializable接口之后，使用alt+enter快捷键自动创建序列化id 
 进入setting→inspections→serialization issues→选择图中的选项。serializable class without ‘serialVersionUID’ 

![img](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\20180821201827272)

 

**10、配置SVN**

![img](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\20180821201857141)

 

**11、配置Maven**

![img](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\20180821201921704)

 

**12、配置tomcat容器**

![img](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\20180821201946634)

 

**13、全局编译时忽略某个目录或文件不进行编译。**

![img](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\20180821202013617)

 

**14、设置统一编译器和编译版本**

推荐使用Javac编译器

![img](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\20180821202037586)

 

**15、设置类注释文件**

![img](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\20180821202103889)

/**
 \* @Package ${PACKAGE_NAME}
 \* @author 侯文远
 \* @date ${DATE} ${TIME}
 \* @version V1.0
 \* @Copyright © 2016-2017 奥琦玮信息科技（北京）有限公司
 */

![img](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\201808212021281)

 

**16、设置方法注释**

先创建一个自定义快捷键，输入如下内容：(第一行不要加*号，因为你在已生成列表里是有的时候他前面已经存在一个*号了。)
 @author 侯文远
 \* @date $date$ $time$

![img](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\20180821202154540)

使用步奏：
 1）在方法的上部输入/**+enter
 2）填入相关信息
 3）在最尾部输入自定义快捷键，我的是@aut+tab
 效果图：

![img](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\2018082120230222)

 

**17、IDEA忽略某个文件或者文件夹，如系统的.idea文件夹和.iml文件。**

![img](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\20180821202325785)

 

**18、Language Injection正则或JSON校验。**

在字符串的赋值处，Alt+Enter选择Inject Language or reference

![img](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\20180821202350829)

**19、给选中内容添加双引号“”或单引号''**

Settings - Editor - General - Smart Keys - 选中 Surround selection on typing quote or brace

使用方法：

选中要添加双引号的代码 然后按键盘上的双引号（shift+"）即可

## 六、另外一些使用技巧

- 高效率配置
- 日常使用 必备快捷键（★★）   
  - 查找
  - 跳转切换
  - 编码相关
  - 代码阅读相关
  - 版本管理相关
- 编码效率相关（★★）   
  - 文件代码模板
  - 实时代码模板
  - 其他
- 代码调试 源码阅读相关（★★★）   
  - 视图模式
  - 代码调试
  - ...
- 插件方面   
  - 插件的安装与使用
  - 插件推荐
- 参考

------

## 高效率配置

### 1. 代码提示不区分大小写

Settings -> Editor -> General -> Code Completion

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTgtMTU3MTE5MjM5Ny5qcGc)

(低版本 将 Case sensitive completion 设置为 None 就可以了)

### 2. 自动导包功能及相关优化功能

Settings -> Editor -> General -> Auto Import

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTEwLTE1NzExOTIzOTguanBn)

### 3. CTRL + 滑动滚轮 调整窗口显示大小

Settings -> Editor -> General -> Change font size (Zoom) with Ctrl+Mouse wheel

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTQtMTU3MTE5MjM5OC5qcGc)

选择之后，就可以通过CTRL+滑动滚轮的方式，调整编辑器窗口的字体大小

### 4. tab 多行显示

这点因人而异，有些人喜欢直接取消所有tab，改用快捷键的方式，我屏幕比较大，所以喜欢把tab全部显示出来。

Window -> Editor Tabs -> Tabs Placement，取消勾选 Show Tabs In Single Row选项。

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTUtMTU3MTE5MjM5OC5qcGc)

效果如下：

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTEtMTU3MTE5MjM5OC5qcGVn)

### 5. 代码编辑区显示行号

Settings -> Editor -> General -> Appearance 勾选 Show Line Numbers

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTgtMTU3MTE5MjM5OC5qcGc)

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTMtMTU3MTE5MjM5OS5qcGc)

------

## 日常使用 必备快捷键（★★）

### 查找

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTMtMTU3MTE5MjM5OS5wbmc)

### 跳转切换

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTctMTU3MTE5MjM5OS5wbmc)

### 编码相关

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTYtMTU3MTE5MjM5OS5wbmc)

### 代码阅读相关

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTgtMTU3MTE5MjM5OS5wbmc)

### 版本管理相关

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTQtMTU3MTE5MjQwMC5wbmc)

更多快捷键请参考此文章

> https://github.com/judasn/IntelliJ-IDEA-Tutorial/blob/master/keymap-introduce.md

mac os 快捷键请参考本文章

> https://github.com/judasn/IntelliJ-IDEA-Tutorial/blob/master/keymap-win-mac.md

------

## 编码效率相关（★★）

### 文件代码模板

Settings -> Editor -> File and Code Template

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTgtMTU3MTE5MjQwMC5qcGc)

在这里可以看到IDEA所有内置的文件代码模板，当你选择某个文件生成时，就会按照这里面的模板生成指定的代码文件。

另外，你可以在这里设置文件头。

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTctMTU3MTE5MjQwMC5qcGc)

设置之后，效果如下

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTUtMTU3MTE5MjQwMC5wbmc)

### 实时代码模板

IDEA提供了强大的实时代码模板功能，并且原生内置了很多的模板，比如，当你输入sout或者psvm，就会快速自动生成`System.out.println();`和`public static void main(String[] args) {}`的代码块。

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTItMTU3MTE5MjQwMS5qcGVn)

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTctMTU3MTE5MjQwMS5qcGVn)

这些的模板可以在Settings -> Editor -> Live Templates看到。使用者可以按照自己的使用习惯来熟悉相关的代码模板。

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTgtMTU3MTE5MjQwMS5qcGc)

### 定制代码模板

IDEA也提供自己定制实时代码模板的功能。

- 创建自己的模板库

- 创建定制的代码模板 

   

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTQtMTU3MTE5MjQwMS5wbmc)

图中的MyGroup就存放着我自己定义的代码模板。

### 其他

### CRTL+ALT+T

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTYtMTU3MTE5MjQwMi5qcGc)

Ctrl + Alt + T 提供的是代码块包裹功能 - Surround With。可以快速将选中的代码块，包裹到选择的语句块中。

### 本地历史版本

IDEA 自带本地版本管理的功能，能够让你本地编写代码变得更加的安心和方便。

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTMtMTU3MTE5MjQwMi5qcGc)

------

## 代码调试 源码阅读相关（★★★）

### 视图模式

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTAtMTU3MTE5MjQwMi5qcGVn)

IDEA提供两种特殊的视图模式，

- Presentation Mode - 演示模式，专门用于Code Review这种需要展示代码的场景
- Distraction Free Mode - 禅模式，专注于代码开发

### 代码调试

**1. 条件断点**

IDEA 可以设置指定条件的断点，增加我们调试的效率。

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTYtMTU3MTE5MjQwMi0xLmpwZw)

**2. 强制返回**

IDEA 可以在打断点的方法栈处，强制返回你想要的方法返回值给调用方。非常灵活！

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTEwLTE1NzExOTI0MDMuanBn)

**![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTEwLTE1NzExOTI0MDMuanBlZw)**

**3. 模拟异常**

IDEA 可以在打断点的方法栈处，强制抛出异常给调用方。这个在调试源码的时候非常有用。

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTctMTU3MTE5MjQwMy5qcGVn)

**4. Evaluate Expression**

IDEA 还可以在调试代码的时候，动态修改当前方法栈中变量的值，方便我们的调试。

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTYtMTU3MTE5MjQwMy5qcGc)

------

## 插件方面

### 插件安装

File -> Setting -> Plugin

插件安装，可以直接在IDEA的插件库中实时搜索安装。browse plugin repository

对于网络不好的用户，可以登录官方插件仓库地址：plugins.jetbrains.com/idea，下载压缩包之后，选择`install from disk`

### 插件推荐

本人日常开发中使用的插件

**Alibaba Java Coding Guidelines**

阿里Java编程规约插件

**FindBugs**

代码缺陷扫描

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTUtMTU3MTE5MjQwMy5qcGVn)

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTUtMTU3MTE5MjQwMy5qcGc)

**PMD**

代码缺陷扫描

**InnerBuilder**

builder模式快速生成

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTctMTU3MTE5MjQwNC5qcGc)

**lombok plugin**

lombok 插件

**maven helper**

maven 依赖管理助手 ，解析maven pom结构，分析冲突；

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTYtMTU3MTE5MjQwNC5qcGc)

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTgtMTU3MTE5MjQwNC5qcGc)

**Rainbow brackets**

让代码中的括号更具标识性

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTEtMTU3MTE5MjQwNC5qcGc)

**String Manipulation**

String相关辅助简化，搭配 CTRL+W 、ALT+J等文本选择快捷键使用

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTYtMTU3MTE5MjQwNS5naWY)

**Translation**

翻译插件，阅读源码必备

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTktMTU3MTE5MjQwNS5wbmc)

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTItMTU3MTE5MjQwNS5wbmc)

**GenerateAllSetter**

**![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTUtMTU3MTE5MjQwNi5naWY)**

**Key Promoter X**

对你的鼠标操作进行 快捷键提示

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTMtMTU3MTE5MjQwNi5naWY)

**GenerateSerialVersionUID**

Alt + Insert 快速生成SerialVersionUID

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTUtMTU3MTE5MjQwNi0xLmdpZg)

**GsonFormat**

**![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTItMTU3MTE5MjQwNy5naWY)**

**RestfulToolkit**

- 快速跳转到Restful Api处( use: Ctrl(Command) + or Ctrl + Alt + N )

- 展示Resultful 接口结构

- http 简单请求工具 

   

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTEtMTU3MTE5MjQwNy5qcGc)

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTAtMTU3MTE5MjQwNy5qcGc)

**Material Theme UI**

本人自用的主题就是这个。

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTQtMTU3MTE5MjQwNy5qcGc)

**MyBatis Log Plugin**

把 Mybatis 输出的sql日志还原成完整的sql语句，看起来更直观。

![IntelliJ IDEA 超实用使用技巧分享](H:\smart_home\The backend development\软件使用教程\IntelliJ IDEA使用教程.assets\aHR0cHM6Ly93d3cuamF2YXpoaXlpbi5jb20vd3AtY29udGVudC91cGxvYWRzLzIwMTkvMTAvamF2YTItMTU3MTE5MjQwOC5qcGc)

**Free Mybatis**

MyBatis 免费的插件

------

## 参考

> https://github.com/judasn/IntelliJ-IDEA-Tutorial

 