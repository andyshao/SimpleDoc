`Simple doc`是一个简易的文档发布管理工具，为什么要写`Simple doc`呢？主要原因还是`github`的`wiki`并不好用；没有目录结构，文章没有`Hx`标签索引，最悲剧的是文章编辑的时候不能直接图片粘贴和文件上传;为了满足自己的需求也顺带帮`Beetlex`写个完整的`web`示例所以花了些时间写了`Simple doc`.虽然`Simple doc`功能简单但在文档展现上还是要比`github`的`wiki`好上不少，所以在完成后也把`github`的`wiki`迁到这上面来了（毕竟都是基于markdown所以迁过来也简单）。
## 功能
- 基于markdown

  (如果不会`markdown`那这个工具就没法用了)
- 支持图片和附件上传

  默认实现只支持`jpa`,`png`,`zip`和`rar`文件上传（最大2MB，这个限制可以自行修改），上传方式支持：拖放，粘贴等.
- 支持各种代码主题

  支持数十种代码主题，由浏览者选择自己喜欢的主题
- 支持两层目录列表

  大部分情况下两层目录能够满足大部分需求，所以在实现上没有支持更多层次的目录结构
- 支持文章结构标签

  只要文章超过3个h2,h3,h4的标签则会对应生成文件的目录列表，方便文章内容定位

应用示例 http://doc.beetlex.io/

![](https://user-images.githubusercontent.com/2564178/68264979-a9582d00-0085-11ea-9789-00a1e8748918.png)

支持大量的代码主题，浏览者可以随意选择自己喜欢的样式
![image](https://user-images.githubusercontent.com/2564178/68272414-99991280-009e-11ea-87ee-712205a72b44.png)

