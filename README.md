# Welcome to material-cnblogs，这是一个 Material 风博客园皮肤，可以直接套用。

使用cnblogs-skin搭建，但是cnblogs-skin里面的HTML模板好像过时了。于是我制作之后又用Stylus大修大改了一番。

内含 `css.css`、`header.html`、`footer.html` 三个文件，分别对应博客园后台“设置”选项卡下的“页面定制 CSS 代码”、“页首 HTML 代码”和“页脚 HTML 代码”。

**可以前往 [我的个人博客](https://www.cnblogs.com/henrylin/) 查看显示效果。**

## 亮点

- 自动生成目录；
- 右下角小飞机游戏；
- 自动添加“本文共 6419 字，阅读本文大概需要 13 ~ 21 分钟”这样的提示条；
- 图片点击放大；
- 页面加载进度条（其实是心理安慰）；
- 漂亮的超链接样式；
- 在文章的任意部分套上 `<div class="no-select">` 和 `</div>` 可以防止这部分内容被复制；
- 友链模板（在 `footer.html` 里面）。

## 使用

1. 在`css.css`中自定义你的头像和用户名，以及各个标签的颜色；
2. 打开 [博客园后台管理设置](https://i.cnblogs.com/settings)；
3. 将 `css.css` 中的内容复制到“页面定制 CSS 代码”框里面，同理，`header.html` → “页首 HTML 代码”，`footer.html` → “页脚 HTML 代码”；
4. 把“标题”框里面的东西删掉（因为已经在 CSS 中定义了）；
5. 把“博客皮肤”改成默认的“AnotherEon”， **不要** 勾选“禁用模板默认CSS”。
6. **保存；**
7. 顺便 Star 一下这个仓库。