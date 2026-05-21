# HTML + Tailwind CSS v4 (本地 CLI)

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io#https://github.com/4GeeksAcademy/html-hello.git)

这是一个仅使用 HTML 与 Tailwind CSS v4（本地编译）的起始项目。

[![How to open html/css preview of my project in gitpod](https://github.com/4GeeksAcademy/Templates-Boilerplates/blob/master/assets/hello-html-intro.png?raw=true)](https://youtu.be/dfbDCMu_p-0)

## 项目规则

- 仅使用 HTML 和 Tailwind CSS。
- 不要使用 React、Vue、Angular、Svelte 或其他 JS UI 框架。
- 使用 Tailwind CSS v4。
- 不要使用 `cdn.tailwindcss.com` 或 `@tailwindcss/browser`。

## 接下来怎么做？

创建一个具有 [基本 HTML 页面结构](http://content.breatheco.de/lesson/what-is-html-learn-html#page-structure) 的 `index.html` 文件并通过使用以下命令，实时预览 Web 服务器提供的 HTML 页面：

```sh
$ pip3 install flask && python3 server.py
```

- 您可以根据需要创建任意数量的 HTML 文件
- 您还可以使用放置在 `<head></head>` 标签之间的 `<link>` 标签创建 CSS 文件并将它们导入您的网站，如下所示：

```html
<head>
  ...
  <link rel="stylesheet" type="text/css" href="styles.css">
  ...
</head>
```

- 本地安装并编译 Tailwind：

```bash
npm install
npm run build
```

- 开发时使用监听模式：

```bash
npm run dev
```

- 在 HTML 中引入编译后的样式：

```html
<head>
  ...
  <link rel="stylesheet" href="./src/output.css">
  ...
</head>
```
