## atom-wxml

> Basic syntax highlighting for wxml files in Atom. https://atom.io/packages/atom-wxml

### 安装

1. Atom -> Preferences -> Packages
2. 查找 `atom-wxml` 安装

### 微信小程序 wxss 语法高亮

`atom-wxml` 支持 .wxml .wxss 文件语法高亮

> 注意：  
> a. 因微信小程序脚本采用 .js 文件后缀且atom核心js插件包已支持.js后缀文件，所以未对.js文件做语法高亮    
> b. 小程序 javascript 语法自动补全 可参考下面进行手动设置

### 微信小程序 javascript 语法自动补全设置

> 打开并拷贝该目录下 snippets.cson文件内容

1.  
  	* 点击 Atom > Snippets  
  	* 拷贝文件内容复制至 Snippets 面板内容区域  
2.  
    * MAC下拷贝该文件至 ~/.atom文件夹下，覆盖snippets.cson文件
    * Windows下找到.atom文件夹，覆盖snippets.cson文件即可

### todo

* wxss支持自动补全
* 语法高亮主题切换
