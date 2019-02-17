
在平时写文档的时候，尤其是在类似Markdown这种纯文本的文档中，使用图片常常很麻烦。

如果随意在网上下载一个图片，担心以后链接不可用；如果把自己的图片上传到一些网站，然后再把图片的链接拷贝下来，虽然图片可以用，但是问题是这个链接往往不可以定制，而且图片分散上传到不同地方也不便于管理。

下面我们来介绍如何利用 [Github Pages](https://pages.github.com/) , 来存储和分享图片资源。

对于Git账户`https://github.com/ipictures`， 其git仓库`https://github.com/ipictures/ipictures.github.io.git`将会默认作为 [Github Pages](https://pages.github.com/)的内容来源。上传到
`ipictures.github.io.git`仓库的资源都可以通过`https://ipictures.github.io/`访问到。

ipictures通过目录进行不同类型、来源和作用的图片区分。

链接：`https://ipictures.github.io/完整目录/完整文件名.文件后缀`就可以引用到图片。

例如在你的markdown文件中引入下面的标签，就可以看到我的照片啦：
```markdown

![ijiangtao](https://ipictures.github.io/me/phonephoto/ijiangtao201902172323.jpg)

```

![ijiangtao](https://ipictures.github.io/me/phonephoto/ijiangtao201902172323.jpg)

图片可以通过git版本管理工具进行上传，也可以在github的网页上上传。

这样图片和文档就进行了分离，文档可以更精简；而且图片还可以通过版本管理工具进行统一管理。

当然，如果你喜欢把图片和文档放在一起也是可以的，比如将图片进行Base64转码以后引入文档或者网页。但我不建议这样做。
