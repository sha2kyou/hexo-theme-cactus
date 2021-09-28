# Cactus：一个简洁的 Hexo 主题

[预览](https://blog.futurenotfound.top)

[下载最新发布版](https://github.com/liuzhuoming23/hexo-theme-cactus/releases)

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
- 添加稍候再写标记
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

创建文件 `source/_data/projects.json` ：

```json
[
  {
    "date": "2020-02-28 12:23:34",
    "name": "Hexo",
    "context": "A fast, simple & powerful blog framework"
  },
  {
    "date": "2020-02-28 12:23:34",
    "name": "Font Awesome",
    "context": "The iconic font and CSS toolkit"
  }
]
```

### 系列文章展示

在文章配置里面添加相同的 series 参数：

```yml
series: 算法
```

### 标题标记稍候再写的文章（🐦）

首先需要在主题\_config.yml 添加：

```yml
post_emoji_mark: true
```

稍候再写文章在文章配置里面添加：

```yml
later: true
```

### 首页是否展示文章简述

在文章配置里面添加：

```yml
show_post_excerpt: true
```

## License

MIT
