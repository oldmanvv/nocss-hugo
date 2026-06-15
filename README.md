# 这是一个没有CSS的Hugo博客主题

[💾代码库](https://github.com/oldmanvv/nocss-hugo) | [👓预览](https://oldman.wang)

但是，由于各种各样的原因，还是要有一些CSS的

目前仅有的`css/alone.css`作用是：
* 限制图片尺寸
* github-markdown.css
* 插入B站视频
  * `{{<b 视频ID>}}`
* 第三方插件
  * highlight.js
  * katex
    * 在文章Front-matter设置`katex: true`

```
hugo new post/文章标题.md
```

站点的config必要配置
```toml
[params]
SEOTitle = ""
Subtitle = ""
TOC = true
baiduTongji = "d2b64b94332edb95313ab7ff3a2b2f56"

[taxonomies]
tag = "tags"
category = "categories"
```

开发环境：

```shell
hugo version
hugo v0.163.1-2a4fd58818ffdf45bbb2a97ab119bb4c46cd93f0+withdeploy linux/amd64 BuildDate=2026-06-11T15:34:40Z VendorInfo=gohugoio
```

