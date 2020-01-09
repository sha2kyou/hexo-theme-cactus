[Demo](https://pliuzhuoming.xyz)

## 主要修改

- 删除多语言
- 调整部分mobile端菜单/按钮等显示
- 删除分享按钮
- 调整标题显示
- 调整toc
- 调整部分默认主题样式

## 配置方式
### 自定义主题及配置

自定义主题位置在source/css/_colors目录，配置方式：
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
