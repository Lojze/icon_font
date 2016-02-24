## 个人常用的字体图标

## 字体一览
字体展示 [icon_font/index.html](http://Lojze.github.io/icon_font/index.html)

##安装
`bower install git://github.com/Lojze/icon_font.git --save`

在页面中引用 iconfont.css 即可：

网页使用: `<link href="icon_font/iconfont.css" media="all" rel="stylesheet" type="text/css">`

##命名规范
基本规则是按照英文翻译过来
*  使用中划线连字符
*  自己可以在`inconfont.css`中修改命名
*  最好命名规范，统一易于管理

##更新图标

1.在 `funt` 目录下更新图标源文件（svg 格式）  
2.执行 `gulp build` 命令生成图标和对应样式表


## 需要说明字体格式的支持方式

### TrueType格式(.ttf)
>Windows和Mac上常见的字体格式，是一种原始格式，因此它并没有为网页进行优化处理。  
>浏览器支持：IE9+,FireFox3.5+,Chrome4.0+,Safari3+,Opera10+,IOS Mobile Safari4.2+

### OpenType格式(.otf)
>以TrueType为基础，也是一种原始格式，但提供更多的功能。  
>浏览器支持：FireFox3.5+,Chrome4.0+,Safari3.1+,Opera10.0+,IOS Mobile Safari4.2+

### Web Open Font格式(.woff)
>针对网页进行特殊优化，因此是Web字体中最佳格式，它是一个开放的TrueType/OpenType的压缩版，同时支持元数据包的分离。  
>浏览器支持：IE9+, FireFox3.5+, Chrome6+, Safari3.6+,Opera11.1+

### Embedded Open Type格式(.eot)
>IE专用字体格式，可以从TrueType格式创建此格式字体。  
>浏览器支持：IE4+

### SVG格式(.svg)
>基于SVG字体渲染的格式。  
>浏览器支持：Chrome4+, Safari3.1+, Opera10.0+, IOS Mobile Safari3.2+
