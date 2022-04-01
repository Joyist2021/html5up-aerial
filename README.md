# html5up-aerial

##由 HTML5 UP 制作的空中

https://html5up.net/aerial

html5up.net | @ajlkn

在 CCA 3.0 许可下免费用于个人和商业用途 (html5up.net/license)


这是 Aerial，单页、单屏响应式网站模板。真的很简单。

大量使用 CSS 动画（我最近一直在搞砸的东西）。

应该作为一个登陆页面很好地工作，它只是将人们引导到 www 上其他地方的东西。 Sass 源代码也包含在内，所以如果您从未使用过 Sass 并且有兴趣尝试一下，请前往 sass-lang.com（如果没有，您可以安全地删除“sass/”文件夹） .

滚动的山峦背景来源于 Ryan Schroeder 的《Icefields》，

一位来自温哥华的才华横溢的摄影师，他在 CC0 许可下慷慨地在 Unsplash 上发布了它。一定要在 flickr（下面的链接）上查看他的其他东西，以及在 Unsplash (unsplash.com) 上查看所有其他获得 kickass CC0 许可的图像。

问题/评论/问题 = 只需发送电子邮件或在 Twitter 上找到我。玩得开心！

阿杰
aj@lkn.io | @ajlkn


滚动背景：

这完全依赖于 CSS 来完成它的工作，这很酷，但是一开始改变它有点奇怪/棘手。您仍然可以使用几乎任何您想要的图像，但为了获得最佳效果，请确保您的图像是：

- 水平平铺。
- 
- 宽而短。
- 
- 大约 1500 像素宽。
- 
- 在底部顶部渐变为纯色（用于填充图像上方或下方的空白区域）。

现在，有两种使用方式：使用 CSS 或使用 Sass：

	CSS:

在 css/style.css 中查找这一行（撰写本文时的第 108 行）：

背景：#348cb2 url("images/bg.jpg") 左下角；

并使用它来设置图像的页面背景颜色、URL 和位置。它应该尽可能接近 1500 像素宽。

	Sass:

将 $bg 的值设置为图像的页面背景颜色、URL 和位置。如果您的图像不是 1500 像素宽，请更改 $bg-width。


致谢：



背景图像：

Ryan Schroeder 通过 Unsplash（unsplash.com - CC0 许可）

“冰原” (flickr.com/photos/ryanschroeder/11876741703)

图标：

字体真棒 Font Awesome（fontawesome.io）

其他：

响应式工具 (github.com/ajlkn/responsive-tools)
