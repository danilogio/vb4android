## VB for Android (VB4A)是一个基于谷歌simple源码的编程工具，旨在实现通过basic语言轻松编写Android程序 ##
## VB for Android (VB4A) is a BASIC language development tool for android devices based on SIMPLE src ##
### VB4A编译器基于Simple，但不局限于Simple，我们对Simple编译器进行了[扩展](http://code.google.com/p/vb4android/wiki/VB4AExt)，使其功能更为强大 ###
### The VB4ACompiler was based on Simple, we [extended](http://code.google.com/p/vb4android/wiki/VB4AExt) the functionality of simple to make VB4A stronger ###

---

## 支持我/Support me ##
VB4A是一款完全免费的BASIC语言ANDROID开发工具，但是它的完善还有很长的路要走。


[![](http://vb4android.googlecode.com/files/%E6%8D%90%E8%B5%A0.png)](https://me.alipay.com/lcw945)

筹集的款项将用于开放论坛、主页等功能，更好地提升vb4a。

### [Donate with PayPal](http://code.google.com/p/vb4android/wiki/Donate_with_PayPal) ###
|![http://vb4android.googlecode.com/files/V12CH.jpg](http://vb4android.googlecode.com/files/V12CH.jpg)|![http://vb4android.googlecode.com/files/V12EN.jpg](http://vb4android.googlecode.com/files/V12EN.jpg)|
|:----------------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------|

---

## [招募JAVA高手，共同完善VB4A/JAVA Expert Needed!](mailto:yourdds520@163.com) ##
如果你熟悉android应用开发，熟悉java，那么请联系我加入核心编译器的开发；
如果你对C#，VB或者VB.net熟悉，那么请联系我加入IDE的开发，或者直接贡献代码，让你成为VB4A的开发者之一。
Wanna be a developer? Any contributions can be made by any suggestions, codes related with java, c# and vb/vb.net on the core compiler or ide.
请访问GIT获取代码/SRC here:http://git.oschina.net/aslamic/VB4A
## 最新版/Current Version ##
## [VB for Android 12.11](http://vb4android.googlecode.com/files/VB4AV12.11.zip) ##
## 手册/Manual ##
### [中文手册](http://vb4android.googlecode.com/files/VB4A%E6%89%8B%E5%86%8C120614.zip)   [English Manual](http://vb4android.googlecode.com/files/VB4A%20Guide%20Book%20120614.zip) ###
### [VB4A中文使用说明即程序介绍（更新版随程序升级一同发布，无需单独下载）](http://vb4android.googlecode.com/files/VB4A%E4%BD%BF%E7%94%A8%E6%89%8B%E5%86%8C.pdf) ###

---

### [如有任何好的建议，欢迎留言/Let me know your problems!](http://code.google.com/p/vb4android/issues/list) ###

---

### 内测，讨论，联系我[![](http://vb4android.googlecode.com/files/group.png)](http://wp.qq.com/wpa/qunwpa?idkey=a99912279fa9c901c654f7b0853c96ab016ef797c2a585cbca2b4cbc6c893f5f) ###

---


---


|**VB4A的优点**|**VB4A的缺点**|**Why VB4A**|**Why Not**|
|:----------|:----------|:-----------|:----------|
|免费         |不支持SD卡文件操作(V11已支持)|Free        |No SD Storage Access(Supports from v11)|
|支持中文       |不支持网络数据(V11.2支持Socket)|Unicode Support|No Network Access(Socket for v11.2)|
|支持多窗口      |不支持数据库(将于V12支持)|MultiForm   |No Database(Comming up for V12)|
|支持GPS      |不支持多点触控    |GPS Support |No Multitouch|
|支持电话呼叫     |不支持短信发送(V11.1支持)|Phone Call Support|No SMS(supports from v11.1)|
|支持振动       |不支持广告      |Vibrate Support|No Ads     |
|支持重力感应     |无法访问摄像头    |Gravity Support|No Camera  |
|支持加速度感应器   |无法播放媒体文件(V11.23支持声音播放)|Accelerator Support|No Media(V11.23 Supports Sound)|
|类似VB6语法    |你告诉我？      |Similar to VB6|tell me    |


---

## VB for Android更新日志 ##
## [Click to view ChangeLog in English](http://code.google.com/p/vb4android/wiki/ChangeLog): ##
**2010年8月11日 项目开始，仅能添加一个按钮**

**2010年8月12日 加入“标签”，加入事件编辑的功能**

**2010年8月13日 加入"radiobutton" "checkbox" "textbox"的支持**

**2010年8月14日 加入"image" "canvas"，并且可以访问电话、计时器、位置传感器和动作传感器**

**2010年8月18日 V1.0
  1. 首个测试版发布**

**2010年9月1日 V2.0
  1. 加入工程保存和打开
  1. 修改了程序图标**

**2010年9月7日 V3.0
  1. 将界面设计改为10\*13（先前为3\*10），并引入鼠标点击定位的功能
  1. 支持所有SIMPLE支持的硬件**

**2010年9月10日 V4.0
  1. 修复部分bug
  1. 提取了SDK所需文件，VB4A可以无需SDK进行开发**

**2010年10月9日 V5.0
  1. 加入额外的控件特性，如背景色、前景色、字体大小等**

**2011年1月16日 V6.0
  1. 修复大量V5.0的bug
  1. 支持添加密码文本框**

**2011年6月16号 V7.0:
  1. 参考VB6重新设计界面
  1. 加入红色方框表示所选控件位置
  1. 加入删除模式用于删除控件
  1. 增大编辑器字体，并可缩放
  1. 中英双语
  1. 以及很多改善**

**2012年6月14日 V8.0:
  1. 修复：如果form\_initialize事件代码保存过则无法再定义变量
  1. 修复：form\_keyboard事件中HANDSETKEY未定义导致编译失败
  1. 修复：不按顺序删除控件后再添加同一控件导致程序退出
  1. 修复: 保存工程后V5.0特性丢失
  1. 改进: 自动补全实现鼠标跟随
  1. 改进: 自动保存语言设置，下次开启程序后自动调用新语言（仅测试XP环境）
  1. 改进: 分辨率支持自定义分辨率（仅在关闭兼容模式时需要），并提供同步放大字体的选项（多数时候不需要）
  1. 改进: 自动大小写检验添加内置数学函数的检验
  1. 改进: 优化了添加函数和过程
  1. 加入: 关键字高亮，代码生成文本高亮（详见手册）
  1. 去除: 编辑器文本大小设置
  1. 加入：点击关于之后进行更新检查(8月11日版本更新为8.1)
  1. 修复：压缩包加入了richtextbox的ocx控件，避免启动失败(8月11日版本更新为8.1)**

**2012年8月17日 V9.0
  1. 改进: 工程创建检查，提示是否成功创建
  1. 改进: [拾色器](http://code.google.com/p/vb4android/wiki/newcolorpicker?ts=1345095124&updated=newcolorpicker)现在支持自定义颜色，并且支持alpha通道
  1. 改进: 编辑器右键菜单
  1. 新增: 中文支持
  1. 新增：快捷编辑器的引入，可以方便插入各种常见语句，不懂VB for android的语法也能开发
  1. 新增：图片导入功能帮你添加图片到工程
  1. 新增：使用新的文件格式（v4p）作为工程文件，单独文件，随时打开
  1. 修复：存储后丢失背景色
  1. 修复：存储后丢失控件名**

**2012年9月3日 V10.0
  1. 修复: 移除模式移除控件无效
  1. 修复: 密码文本框属性和文本框错乱
  1. 修复: 没有安装7zip时保存和读取工程的bug
  1. 改进：新设计的界面和图标
  1. 改进: 设计器由10\*13扩展为20\*26
  1. 改进: 自动存储分辨率设置
  1. 改进: 支持PNG预览
  1. 改进: 保存项目前移除不必要的文件，减小文件尺寸
  1. 新增: 编辑器支持控件插入
  1. 新增: 支持修改程序名（支持中文名）
  1. 新增: 支持修改程序图标
  1. 新增: 控件修改可以修改控件属性和位置、尺寸
  1. 新增: 新增Dates和Strings两套函数库，可以直接调用近20个新函数
  1. 新增: 编译菜单增加GO选项，一步编译
  1. 新增: 程序中设置JAVA\_HOME
  1. 新增: 兼容模式用于打开9.0的工程，导入用于打开旧版工程
  1. 新增：支持计时器时间间隔修改(10月12日版本更新为10.1)
  1. 新增：支付宝捐赠(10月12日版本更新为10.1)
  1. 改进：程序启动时进行更新检查(10月12日版本更新为10.1)**

**2013年1月27日 V11.0
  1. VB4ACompiler诞生，突破Simple编译器的限制，加入Msgbox和ToastMessage对应弹出式消息框和弹出通知
  1. 新增：多窗体
  1. 新增：控件编辑采用弹出式菜单
  1. 新增：JAVA\_HOME设置及JDK下载
  1. 新增：界面重新设计
  1. 新增：SD卡文件访问（非完善）
  1. 新增：加入了数值转换函数集合（Asc，Hex等）
  1. 新增：SocketSend函数用于支持socket
  1. 新增：发送短信功能
  1. 新增：媒体文件播放（音频）
  1. 新增：工程文件改为v4a格式
  1. 移除：默认的文本高亮改为手动**

**2013年6月25日 V12.0
  1. VB4ACompiler进一步加强，加入更多独有（虽然现在已经呵呵了）的实用功能
  1. 修复：保存工程时点击取消后程序出错
  1. 修复：多窗体下的窗体代码混乱问题
  1. 修复：打开工程后仍然能新建工程的bug
  1. 修复：插入控件后程序错误退出的bug
  1. 修复：V11后无法移除控件的bug
  1. 修复：代码编辑器空白工程插入控件后错误退出
  1. 修复：控件编辑未定义新位置就确定造成的控件丢失
  1. 新增：示例程序管理器，用于打开示例程序
  1. 新增：可以将vbdroid.exe设置为v4a的打开方式
  1. 新增：SQL支持
  1. 新增：代码编辑窗体加入打开所有事件的功能
  1. 新增：关闭程序时删除工程文件夹
  1. 新增：开放button的image属性和textbox的hint属性
  1. 新增：中文化编译器的提示语句
  1. 新增：修改程序窗体背景色
  1. 新增：编辑器插入颜色字符
  1. 新增：加入分辨率拉伸
  1. 新增：可以修改程序默认图标
  1. 新增：加入了多个组件的Click事件，包括Label、Image
  1. 新增：WebView（控件名为VB4AWeb）
  1. 新增：ProgressBar（控件名为VB4AProg）
  1. 新增：Panel容器控件用于动态添加控件
  1. 新增：可控制的Mediaplayer（CreatePlay，Play，PausePlay，StopPlay，ReleasePlay）
  1. 新增；扩展文本对齐方式为9种
  1. 新增：Val()和Str()用于完成文本和数字的转换
  1. 新增：恢复模式，用于恢复错误退出的工程
  1. 新增：编辑器支持删除事件代码
  1. 新增：窗体移除操作
  1. 新增：访问官网和贴吧的快速功能
  1. 新增：数学函数：Asin、Acos、Ceil、Round、Floor（反正弦、反余弦、上舍入、四舍五入、下舍入）
  1. 新增：TextBox、PasswordTextBox的InputType属性，用于定义键盘类型
  1. 新增：VB4AEMU虚拟机，基于Android SDK的快速模拟器，开发更便捷
  1. 新增：关闭工程以便直接新建
  1. 新增：界面设计器支持框选和拖动，取代先前的点击方式
  1. 新增：Canvas扩展绘图命令，支持绘制方形（VB4ADrawRect）、弧线（VB4ADrawArc）、圆角方形（VB4ADrawRoundRect）、刷新（VB4AInvalidate）、绘制文本（VB4ADrawText）、设置画笔粗细（SetVB4APaintSize），修正Canvas背景图片设置无效的bug【20130620】
  1. 新增：长按事件【20130620】
  1. 新增：InputBox用于取得输入（VB4AInputBoxShow）【20130622】
  1. 新增：Quit()用于彻底退出程序【20130623】
  1. 改进：添加四个快捷调试按钮
  1. 改进：原生的中文支持，相比之前的反编译方法更为稳定快速
  1. 改进：原生支持程序名修改和图标更换，不需要反编译
  1. 改进：编译器信息捕捉
  1. 改进：完善的自动大小写机制
  1. 改进：重写自动补全识别代码，自动补全弹出框重新实现，并对字符识别加以优化
  1. 改进：支持小键盘区自动补全
  1. 改进：减少程序目录下的非必要文件数量，移除不需要的lib文件
  1. 改进：编辑模式下禁用所有控件，避免误点
  1. 改进：CodeEditor自动去除保存代码后多余的换行
  1. 改进：CodeEditor支持插入局部变量和全局变量（只在Form Initialize事件中支持全局），或者常量
  1. 改进：界面重绘
  1. 改进：全程序容错机制，避免错误退出
  1. 改进：设计器全屏【20130622】
  1. 新增：Beep()和RC4(thx to someone)用于提示音和加密解密【20130716】【v12.11】
  1. 改进：改进代码编辑器，引入新的高亮引擎(thx to programme)等诸多改良【20130716】
  1. 新增：GetURL用于获得网页源码
  1. 修正：修复Textbox多行文本不能实现的bug，修正passwordtextbox的可见性错误
  1. 新增：AscW和ChrW函数，用于实现程序中的unicode支持【20130723】**

**2014年6月xx日 V13
  1. 修正：菜单重复响应
  1. 新增：矩阵函数库
  1. 新增：统计函数库
  1. 新增：复数函数库及复数数据类型
  1. 新增：VB4AShell、VB4ASetExe函数，用于调用系统命令及运行C语言开发的程序
  1. 新增：Unpack、ReadTxt、WriteTxt、GetSDPath、GetAppPath等函数，加强文件交互能力
  1. 新增：VB4APost函数，提供Post功能
  1. 新增：CSV解析器，用于读写CSV文件
  1. 新增：Ceil2、Floor2和Round2，提供指定位数的舍入
  1. 新增：Sort函数，用于数组快速排序
  1. 新增：Split2函数，兼容VB6的Split用法
  1. 新增：VB4AProp库，用于读取IMEI、型号、电话号码、设备ID及Sim卡序号
  1. 新增：手册明确Property类型数据的使用方法
  1. 新增：手册明确Collection类型数据的使用方法（以上，修改时间：2014年3月20日）
  1. 新增：GetScreenHeight、GetScreenWidth、GetScreenDensity三个函数用于获取屏幕相关参数
  1. 新增：SetMenus(字符数组)方式批量设置菜单项目
  1. 新增：ListAll、ListFiles两个函数，用于获取文件列表
  1. 新增：GPS加入ForceStart和ForceStop来避免停止监听
  1. 新增：设置APP主题、APP最低系统等级
  1. 新增：完成RelativeLayout的移植，新增控件的Left、Top属性，用于定位（以上，修改时间：2014年3月27日）
  1. 新增：RndBetween(min,max)获得指定范围的随机数
  1. 新增：ZoomRatioH、ZoomRatioW用于获取屏幕分辨率缩放比例
  1. 新增：Canvas添加保存图片的方法
  1. 新增：UserQuit和UserHide函数，给定title，content，yesbtn，nobtn的对话框，用于决定用户是否退出程序或转向后台（主要用于响应返回键）
  1. 新增：新的屏幕尺寸自适应方法
  1. 新增：ReCodec用于转换编码，MD5用于计算字符的MD5
  1. 新增：ShowMsgbox()、ShowInputbox()、ShowListbox()、ShowRadiobox及ShowCheckbox等多套对话框
  1. 新增：Form的FormLoad()和FormHide()事件，对应窗体切换和切换走两个事件，类似于VB6的Form Load事件和Hide事件
  1. 新增：ImageButton控件
  1. 新增：ListView控件
  1. 修正：SendSMS发送大于70字的短信失败的问题（采用多条短信发送）**

“你想要的，我们来实现”