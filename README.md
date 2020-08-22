# Cactus：一个简洁的Hexo主题

[预览](https://bolg.futurenotfound.top)

[下载最新发布版](https://github.com/liuzhuoming23/hexo-theme-cactus/releases)

## 相对原项目主要修改

- 删除多语言
- 删除分享按钮
- 调整标题显示
- 调整部分mobile端菜单/按钮等显示
- 调整toc显示
- 调整部分默认主题样式
- 添加Valine评论
- 添加正文加密
- 添加底部上一篇下一篇
- 添加系列文章展示
- 添加打赏
- 添加知识产权共享
- 主页添加文章简介

## 配置方式
### 自定义主题及配置

自定义主题位置在source/css/_colors目录，配置方式是在主题_config.yml里面修改：
```yml
colorscheme: light
```

### 自定义首页项目显示配置

创建文件 `source/_data/projects.json` ：
```json
[
    {
       "date":"2020-02-28 12:23:34",
       "name":"Hexo",
       "context":"A fast, simple & powerful blog framework"
    },
    {
       "date":"2020-02-28 12:23:34",
       "name":"Font Awesome",
       "context":"The iconic font and CSS toolkit"
    }
]
```

### 系列文章展示

在文章配置里面添加相同的series参数：
```yml
series: 算法
```

## License

MIT
