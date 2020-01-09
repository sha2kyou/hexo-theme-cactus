# Cactus：一个简洁的Hexo主题

[Demo](https://liuzhuoming.xyz)

## 相对原项目主要修改

- 删除多语言
- 删除分享按钮
- 调整标题显示
- 调整部分mobile端菜单/按钮等显示
- 调整toc显示
- 调整部分默认主题样式

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
       "name":"Hexo",
       "url":"https://hexo.io/",
       "desc":"A fast, simple & powerful blog framework"
    },
    {
       "name":"Font Awesome",
       "url":"http://fontawesome.io/",
       "desc":"The iconic font and CSS toolkit"
    }
]
```

## License

MIT
