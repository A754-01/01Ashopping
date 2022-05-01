# A购商城（pc端）



## 项目类型：静态页面

### 1、创建文件夹

- 项目文件夹	shopping

- 样式类图片文件夹	images

- 样式文件夹	css

- 脚本文件夹	js

- 产品类图片文件夹	upload

- 字体类文件夹	fonts

### 2、创建文件

- 首页                                      index.html

- css初始化样式文件	base.css

- css公共样式文件            common.css

- favicon图标                       favicon.ico

### 3.标签SEO优化

- ```html
  <title>网站SEO标题</title> 
  <meta name="description" content="网站描述" /> 
  <meta name="keywords" content="网站关键词" />
  ```

  

### 4.一般制作首页的头部和底部，根据模块化开发，样式写到公共样式common.css里面。

### 5.命名标准

- 快捷导航栏                      shortcut

- 购物车                                shopcar

- 搜索                                     search

- 热点词                                hotwords

- 导航                                     nav

- 导航左侧                           dropdown 包含 .dd .dt

- 导航右侧                           navitems

- 页面底部                            footer

- 标志                                      logo

- 页面头部                            header

- 页面底部服务模块    mod_service

- 页面底部帮助模块	mod_help

- 页面底部版权模块	mod_copyright

### 6.logo SEO优化

- 6.1. logo盒子里先放一个h1标签，目的是告诉搜索引擎，这个地方很重要。

- 6.2. h1里面再放一个链接，可以返回首页的，把logo的背景图片给链接即可。 

- 6.3. 为了搜索引擎收录我们，我们链接里面要放文字（网站名称），但是文字不要显示出来。
  -   6.3.1.     📝方法：直接给 font-size:0; 就看不到文字了，京东的做法。

- 6.4. 最后给链接一个 title 属性，这样鼠标放到logo上就可以显示提示文字了。