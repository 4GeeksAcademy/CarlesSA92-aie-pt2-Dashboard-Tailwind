# HTML + Tailwind CSS v4 (Local CLI)

Starter project for building a website using only HTML and Tailwind CSS v4 with local compilation.

> There is a video tutorial on [how to use this template to create your very first website here](https://youtu.be/dfbDCMu_p-0).

## Project Rules

- Use only HTML and Tailwind CSS.
- Do not use React, Vue, Angular, Svelte, or any JS UI framework.
- Use Tailwind CSS v4.
- Do not use `cdn.tailwindcss.com` or `@tailwindcss/browser`.

## What to do next?

Create an `index.html` file with the [basic HTML structure](http://4geeks.com/lesson/what-is-html-learn-html#page-structure) and see it live by running a web-server using the following command:

```bash
$ pip3 install flask && python3 server.py
```

- You can create as many HTML files as you want.
- You can also create CSS files and import them into your website using a `<link>` tag placed between the `<head></head>` tags, like this:

```html
<head>
  ...
  <link rel="stylesheet" type="text/css" href="styles.css">
  ...
</head>
```

- Install dependencies and compile Tailwind locally:

```bash
npm install
npm run build
```

- Use watch mode during development:

```bash
npm run dev
```

- Include the generated stylesheet in your HTML:

```html
<head>
  ...
  <link rel="stylesheet" href="./src/output.css">
  ...
</head>
```

### Contributors

This template was built as part of the [Full Stack Developer course](https://4geeksacademy.com/us/coding-bootcamps/part-time-full-stack-developer) at [4Geeks Academy Coding Bootcamp](https://4geeksacademy.com/us/coding-bootcamp) by [Alejandro Sanchez](https://twitter.com/alesanchezr) and [many other contributors](https://github.com/4GeeksAcademy/html-hello/graphs/contributors).

You can find other templates and resources like this at the [school's GitHub page](https://github.com/4geeksacademy/).
