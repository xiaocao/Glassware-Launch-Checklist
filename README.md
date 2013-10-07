Glassware 发布规范
==========

> #### 关于本文档
> - **Glassware** 是 Google Glass 应用的专有名词
> - 这是 Glassware 的开发规范，只有符合规范的 Glassware 才能上架官方的 MyGlass 推荐
> - 由于文化和理解上的差异，译文中难免存在纰漏，望各位提出宝贵的意见
> 
> #### 关于我们
> 我们（BestApp/BestNG）是国内第一支从事 Glassware 开发的团队，致力于 Glassware 的开发和 Glass 的本土化工作，同时尽可能向社区回馈我们的研究成果和新鲜好玩本土 Glassware。
>
> 更多信息请移步 [GlassX](http://www.glassx.cn/)，欢迎加入到我们的行列。
>
> - 翻译：[Jason Wu](cn.jason.wu@gmail.com)(BestNG)
> - 校对：[XiNGRZ](chenxingyu92@gmail.com)(BestNG)
>
> 原文地址：https://developers.google.com/glass/distributing/checklist

####图片样式

######提供 20x20, 30x30, 40x40, 50x50, 和 150x150 像素的源图标

Glass 会在timeline卡片上自动显示你的图标在不同的位置和大小。这让用户了解timeline卡片的来源，确保你的图标:

* 代表你的品牌
* 除了大小其他是相同的
* 白色或者透明背景，这确保Glass正常显示图标在不同位置
* 每个图标完全填充所要求的尺寸

以下是Glass使用的你图标的地方

######以你的标志色为底色的 20x20 和 40x40 图标	
![20x20 icon](https://developers.google.com/glass/images/icons/g-20.png)
![40x40 icon](https://developers.google.com/glass/images/icons/g-40.png)

######在timeline卡片的底部是一个30x30的图标
![30x30 icon](https://developers.google.com/glass/images/icons/g-30.png)

######在 "ok glass"的触摸菜单上是一个50x50的图标
![50x50 icon](https://developers.google.com/glass/images/icons/g-50.png)

######当用户激活Glassware是发送的卡片上图标是150x150
![150x150 icon](https://developers.google.com/glass/images/icons/g-150.png)

######提供 40x40 和 85x85 像素的画廊图标

MyGlass 网站在用户的各个界面显示你的品牌图标，确保你的图标:

* 代表你的品牌
* 除了大小其他是相同的
* 白色或者透明背景

######提供一个640x360 贴图图标
MyGlass 将会一直使用这个图标和你的Glassware名字，，20x20图标和你的标志创建一张贴图在MyGlass上显示

######初始图标
![original icone](https://developers.google.com/glass/images/icons/g-640-360-tile.png)

######MyGlass 贴图
![MyGlass tile](https://developers.google.com/glass/images/icons/tile-with-icon.png)

###### 提供一种logo的主色调
Glass 使用这种颜色来显示你的20x20和40x40的logo图标在不同情况下，颜色必须是十六进制(比如,#556677)

######提供Glassware的屏幕截图
告诉用户你的Glassware是怎么使用的，提供一张Glassware的屏幕截图以及一张在使用中的屏幕截图。MyGlass结合两张图片创建一个插图当做屏幕截图用于显示你的Glassware。

* 上下文图片必须是2528x1856像素，这是Glass的相机分辨率
* Glassware 屏幕	截图必须是640x360像素分辨率，这是Glass的显示屏分辨率
* 你必须至少提交一张插图，最多提交5张

######背景图片和Glassware屏幕截图
![context image](https://developers.google.com/glass/images/icons/context-640.jpg)
![application image](https://developers.google.com/glass/images/icons/traffic.png)

######最终的MyGlass插图，下半部分已经裁剪
![vignette](https://developers.google.com/glass/images/icons/vignette-640.jpg)

####商标
######避免额外的商标出现在个人的timeline 卡片上
Glassware 将会显示你的30x30像素的品牌logo在timeline 卡片的底部
######写一个好的关于Glassware的描述
Glassware的描述将会出现在MyGlass 网站上告诉用户你提供什么服务:

* 用一句精简的话描述你的Glassware
* 提供一个800字以内的详细描述.MyGlass显示这些描述在你的Glassware的更多信息上，别复制你的断描述在这里
* 在适当的地方展示Glassware的特性
* 不能包含MyGlass 或者GlassUI 的工作原理的文字
* 如实描述你的Glassware的功能
* 不能包含未注册商标的宣传材料
* Glassware是Glass软件的专业术语，而不是应用软件

#####遵守Glass的品牌设计指导
你的Glassware应遵循Glass品牌设计指导，详见[Glass Brand Guidelines](https://developers.google.com/glass/brand-guidelines)

####设计

#####在卡片上应遵循以下标准
######如果你使用自定义HTML
* 确保你遵循标准[standard margin requirements.](https://developers.google.com/glass/ui-guidelines#displaying_your_own_custom_html)
* 使用大于30像素的Roboto Thin字体和在底部使用小于或者等于30像素的Roboto Light字体
* 使用的颜色必须遵循[standard Glass CSS file.](https://mirror-api-playground.appspot.com/assets/css/base_style.css)

######保持页脚的中间空白
“ok glass”的相关语音指令菜单将出现在底部的中间区域和一些相关的内容在卡片的下方
![ok glass](https://developers.google.com/glass/images/glass-screens/contextual-voice.png)

######不要使用一张固定的timeline卡片作为Glassware的程序入口
如果你需要一个新的语音指令来解决这个问题，请[提交请求](https://services.google.com/fb/forms/glassvoicecommand/)

####内容
######尽可能使用图片而不是文字
如果可能，使图片全屏(640x360像素)或左列(240x360像素)代替文字。图片应保持原有的宽高比例。
######保持信息简洁
每个卡片显示一小块相关信息方便查看
######不要重复发送timeline items
不要太频繁更新.Glass 发送定期更新应该保持一致的值
######遵循媒体格式要求
* 所有公共视频都是事件流,不要附加到timeline items
* 视频的比例是16:9
* 视频分辨率是640x360像素
* 视屏格式: 视频容器:MP4。视频编码:H.264 和 H263。音频: AAC 和MP3

####菜单
######创建合适的菜单图标以及文字
* 图标是完全白色或者透明背景
* 使用50x50像素和描述执行的行为
* 使用[Glass menu icons](https://developers.google.com/glass/downloads/menu-icons-50.zip)如果你想符合GlassUI标准
* 使用简短和可操作的菜单项的显示名字，动词祈使句看起来很棒，像以下例子
![menu item one](https://developers.google.com/glass/images/glass-screens/google.png)
![menu item two](https://developers.google.com/glass/images/glass-screens/take-a-picture.png)
![menu item three](https://developers.google.com/glass/images/glass-screens/record-a-video.png)

#####避免没有明确使用的删除菜单
删除是可以接受的如果有相关Glassware操作(比如:照片分享).如果你使用删除，在Glass上删除timeline项和在你的服务器上进行相关操作

####集合和分页
######适当得使用包
* 使用类似卡片组但不应该是一样的卡片，例如，使用集合为一组新闻故事在一个小时内或者一组体育成绩
* 设计简要集合封面卡片，视觉上包含不同来自集合内的卡片内容
* 每个集合通知用户的通知声音只有一次

######正确地使用分页
* 适当地使用内容分页因为空间限制所有内容不适合显示在一张单独的卡片上.例如：使Email或者新闻故事分页，跨越多个卡片

####分享联系人
######尽可能创建一个简要的描述在分享联系人的时候
* 省略冗余的信息在分享联系人时所显示的，如你的品牌名称
* 为联系人创建一个丰富的图片，图片像素为640x360像素。
* 如果分享多个联系人，确保他们在逻辑上是不同的，可区分的

######添加适当的元数据在共享内容的时候
* 添加“throughglass“”分类共享内容
* 在从Glass分享内容的时候添加"Sent through Glass"，不强求分类

#####适当声明内容的MIME类型
你的联系人有可能不能接受所有类型的内容，声明你的联系人有效的支持类型和‘[acceptTypes](https://developers.google.com/glass/reference/contacts#acceptTypes)'属性

####网站
如果你的Glassware和产品有一个相关的网站，请遵循以下指导标准
* 使用 [Send to Glass](https://developers.google.com/glass/downloads/send-to-glass-buttons.zip) 图标如果从网站上推送内容到Glass
* 确保正确地语法和拼写
* 如果提供 "More info"链接在MyGlass上，链接到网页和Glassware的特定信息例如Glassware的支持或者提示，不要链接到通用产品信息
* 在你的网站上不提供Glassware的取消授权，取消授权只能是在MyGlass上.

####Glassware 设置

提供简单的方法调整和授权Glassware

######提供简操作的授权流程
* 不要有超过两个的授权或者登陆界面
* 设置在一个合理的不需要重复授权的时间范围(小于三个月)
* 如果一个账号和相应的应用程序是不许的，对于那些没有你的服务账号的用户来说，授权流程必须是清晰的。
* 授权链接地址必须和设置链接地址是不一样的
* 如果一个用户账号是必学的，Glassware必须不验证用户没有链接到用户账号(这句表示不懂)

######提供条例清晰有用的设置
* 设置改变保存的时候提供良好的视觉表明
* 显示更新的频率和订阅数量。下面截图是一个例子，允许用户设置更新时间频率和订阅类型

![cnn](https://developers.google.com/glass/images/cnn-settings.png)










