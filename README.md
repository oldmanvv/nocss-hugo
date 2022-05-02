# 这是一个没有CSS的Hugo博客主题

[💾代码库](https://github.com/OlddogClock/nocss-hugo) | [👓预览](https://oldman.wang)

但是，由于各种各样的原因，还是要有一些CSS的

目前仅有的`css/alone.css`作用是：
* 限制图片尺寸
* 插入B站视频
  * `{{<b 视频ID>}}`
* 第三方插件
  * highlight.js
  * katex
    * 在文章Front-matter写入`katex: true`


站点的config必要配置
```toml
[params]
SEOTitle = "一个老伙计心中的少年。天文 无线电"
Subtitle = "一个老伙计心中的少年。PS:这是一个没有CSS的站点"
TOC = true
baiduTongji = "d2b64b94332edb95313ab7ff3a2b2f56"

[taxonomies]
tag = "tags"
category = "categories"
```

开发环境：

```shell
hugo version
hugo v0.93.0-07469082+extended windows/amd64 BuildDate=2022-02-28T08:30:42Z VendorInfo=gohugoio
```

