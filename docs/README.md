> 本地启动 😉

- 全局安装
```bash
npm i docsify-cli -g
```
- 本地启动

?> `docsify serve <path> [--open false] [--port 3000]`  open: 是否默认打开浏览器；port: 启动端口, 默认3000
```bash
docsify serve docs
```
- 本地访问

`http://localhost:3000 `

> 编写文档 😉

直接在`docs`目录下编写对应的markdown文件即可.

> 添加菜单 👇

- 左侧菜单 在根目录下`_sidebar.md`文件中添加对应的md文件.

- 顶部菜单 在根目录下`_navbar.md`文件中添加对应的md文件.

> 修改封面 😬

封面所有内容在根目录下`_coverpage.md`中修改.

> 相关配置 😛

参考`index.html`中`window.$docsify`的配置及对应的注释.

> 其它 👇

- 静态资源可以放在`assets`文件夹下
- 如果某个文档中的标题不想展示在左侧菜单，可在标题后配置`{docsify-ignore}`，如果所有的标题都不展示，可在最高等级标题后面配置 `{docsify-ignore-all}`
- 编写过程中支持emoji表情，eg: `:100:` :100:
- 如果想要展示更新时间，可在文中使用`\{docsify-updated\}`变量即可. eg:  {docsify-updated}

> 相关链接 🤙

- [docsify官网](https://docsify.js.org/)
- [Markdown官网](http://www.markdown.cn/)


 {docsify-updated}

