---
layout: layout
title: Hexo添加标签页
date: 2017-06-30 23:25:43
tags:
---

在hexo项目根目录使用命令添加一个新的页面tags

```
$ cd your-hexo-site
$ hexo new page tags
```


然后需要编辑新建的页面，需要将页面类型设置为tags：

```
title: 标签
date: 2014-12-22 12:39:04
type: "tags"
---
```
在菜单中添加链接。编辑 主题配置文件 ， 添加 `tags` 到 `menu` 中，如下:

```
menu:
  home: /
  archives: /archives
  tags: /tags
```

