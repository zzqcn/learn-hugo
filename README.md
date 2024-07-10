# hugo学习

## 代码介绍

sites 子目录中包括学习使用的 helloworld 项目和练手用的其他项目的源码.
其中 helloworld 项目随着特性不断增加, 后面跟的数字不断增大.

目录          | 内容
--------------|--------------------------
helloworld    | hugo项目骨架, 带有主题
helloworld2   | 修改配置文件, 加入几个内容页, 添加 logo 和背景图片
helloworld3   | 内容页使用 Markdown 格式, 使用索引页布局 index.html, 使用 front matter 做为数据源生成页面
helloworld4   | 对不同环境使用不同的配置文件
helloworld5   | 用 sections 和 menus 组织内容
helloworld6   | 用 bundles 更好地整合页面
helloworld7   | 用 taxonomies 组织内容

themes 子目录中存放通用主题. 一般主题是存放在站点目录的 themes 子目录中的, 如 sites/helloworld/themes,
但 helloworld 等站点都依赖同一个主题, 为避免存放大量重复文件, 就都放在上层公共目录中了,
这时要修改使用此主题的站点的配置文件, 如:
```yaml
themesDir: ../../themes
theme: Eclectic
```


## 参考

- [《Hugo in Action》官方](https://www.manning.com/books/hugo-in-action)
- [《Hugo in Action》在线版本(中文,不完整)](https://hugo-in-action.foofun.cn/zh/)
- [Hugo Documentation](https://gohugo.io/documentation/)
