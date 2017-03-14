# 说明
这个项目是希望能够将 Google 的官方 Material Design 翻译为中文，并且保持原有的网站样式和布局。项目使用 Hammer for Mac 来合并，原有的样式和代码都是直接从 Google 那里拷贝而来的。

项目目前已经上线了，需要查看的可以移步 [md.maxoxo.design](http://md.maxoxo.design)。只包含了目前已经翻译的页面，其他页面会在翻译完成后上传，有问题请及时反馈给我。

# 关于 Daily 分支
我会把最新的更新放在 Daily 分支里面，目前 Daily 分支包含了部分的媒体文件，另外一部分因为文件太大超过了 GitHub 的限制，因此无法上传，以后也不会上传了。

# 项目进度
- [x] 整理素材文件
- [x] 更新 HTML 文件结构
- [x] 替换 HTML 内部链接
- [x] 翻译进度（100%）

###### 其他补充
另外有一张图片和一个视频因为 Google 服务器的原因，在原网页也无法打开，因此丢失了，如果以后可以拿到就在补充。

# Material Design 翻译对照

### 属性

**Elevation**：海拔。之所以翻译成海拔是为了区别 Width（宽） 和 Height（高），其实从三维空间中来看，Elevation 对应的应该是高度，而 Width 和 Height 应该对应的是长和宽。但手机屏幕毕竟是一个虚拟的三维空间，从视觉上来看它其实还是二维的，所以 Width 和 Height 翻译成宽和高就不会有太大的问题，而且符合它们原本的意思。而且从 Material Design 中对 Elevation 的解释其实也更符合海拔的定义。Elevation 是相对于某一平面的高度，而海拔恰好也是这样，只是海拔的这个平面是海平面，不过说起来每个国家再统计的时候，所参考的海平面也是不同的。因此 Elevation 翻译成海拔会更合适。

**Redaction**：掩饰。参考了 [韦氏词典](https://www.merriam-webster.com/dictionary/redacting) 中的解释「to select or adapt (as by obscuring or removing sensitive information) for publication or release」为了公布或发表而挑选或调整（掩盖或移除敏感信息）。

### 组件名称

**Tiles**：磁帖。这个翻译参考了 Windows 中对于 Live Tile（动态磁帖） 的翻译。

**Picker**：选择器。参考了 IXUS 在 iOS 的人机交互指南中对于 Picker 的翻译。

**Tab**：选项卡。参考了 Windows 系统中对于 Tab 的翻译。

**Chips**：片段。原意是碎屑，碎片。但作为元素的容器，直译会有点难以理解，因此译作片段，也是说明截取了例如「联系人」信息中的某段文本来展示的意思。

**Stepper**：步进器。参考了 IXUS 在 iOS 人机交互指南中的翻译。

**Ellipses**：着重号。原意为椭圆或省略号，为了符合原文的意义以及避免歧义，参考了下文中 Unicode 的编码的名称（U2022 名称为 Bullet），翻译为着重号。

**Error message**：出错信息。

**Character counter**：字符计数器。

### 文字排印

**Typeface**：字型。

**Font**：字体。

**Font size**：字号。

**Font weight**：字重。

**Kerning**：字符间距。

**Tracking**：字偶间距。

**Leading**：行高。原意为行距，但是在 MD 的指南中的解释与行高相同，而与中文排版中常说的行距不同。

**Type hierarchy**：字级。

### 文本框和状态

**Form field**：表单字段。

**Text field**：文本框。

**Normal**：正常。

**Focus**：聚焦。

**Active**：激活。

**Press**：按下。

**Disable**：禁用。

### 手势操作

**Touch**：轻触。参考了 iOS 中的翻译。

**Double Touch**：轻触两下。参考了 iOS 以及 MacOS 的翻译。

**Drag**：拖拽。参考了 Windows 以及 iOS 的翻译。

**Swipe**：轻扫。参考了 macOS 以及 Windows 的翻译。

**Fling**：轻甩。原意为甩，在手势操作中，是快速滑动，手指在一个地方按下，然后迅速滑动较短的距离。

**Pinch**：捏合。参考了 MacOS 的翻译。

**Pinch open**：双指张开。参考了 MacOS 的翻译。

**Pinch closed**：双指捏合。参考了 MacOS 的翻译。

**Press**：按下。

**Long press**：长按。

**Click**：点击。

**Tap**：轻点。参考了 MacOS 的翻译。

### 展示状态

**Permanent**：固定展示。

**Persistent**：持续展示。

**Temporary**：临时展示。
