# Cactus：一个简洁的 Hexo 主题

[预览](https://tr1ck.cn)

[下载最新发布版](https://github.com/sha2kyou/hexo-theme-cactus)

## 相对原项目主要修改

- 删除多语言
- 删除分享按钮
- 调整标题显示
- 调整部分 mobile 端菜单/按钮等显示
- 调整 toc 显示
- 调整部分默认主题样式
- 添加 Valine 评论
- 添加正文加密
- 添加底部上一篇下一篇
- 添加系列文章展示
- 添加打赏
- 添加知识产权共享
- 主页添加文章简介
- 添加文章状态标签（如精选、草稿等）
- 添加文章字数统计
- 添加 TOC
- 添加备案展示
- 添加 Google Ad
- 添加过期文章提示

## 配置方式

### 自定义主题及配置

自定义主题位置在 source/css/\_colors 目录，配置方式是在主题\_config.yml 里面修改：

```yml
colorscheme: light
```

### 自定义首页项目显示配置

创建文件 `source/_data/projects.json`，并添加 `url` 字段用于链接跳转：

```json
[
  {
    "date": "2020-02-28 12:23:34",
    "name": "Hexo",
    "url": "https://hexo.io/"
  },
  {
    "date": "2020-02-28 12:23:34",
    "name": "Font Awesome",
    "url": "https://fontawesome.com/"
  }
]
```

### 文章合集展示

在文章配置里面添加相同的 `series` 参数，可以将文章聚合为合集：

```yml
series: 算法
```

### 文章状态标签

通过在文章的 front-matter 中设置 `status` 字段，可以为文章添加状态标签。

首先，在主题的 `_config.yml` 中启用该功能：
```yml
post_tag_mark: true
```

然后，在文章的 front-matter 中添加 `status` 字段，例如：
```yml
status: featured
```
支持的状态包括：`featured` (精选)。精选文章标题前会有一个星号图标。

### 首页是否展示文章简述

在文章配置里面添加：

```yml
show_post_excerpt: true
```

## License

MIT
