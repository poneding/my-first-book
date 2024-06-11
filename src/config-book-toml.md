# 配置 book.toml

```bash
vim "./book.toml"
```

编辑 `book.toml` 文件，添加或修改配置：

```toml
[book]
authors = ["poneding"]
language = "en"
multilingual = false
src = "src"
title = "My First Book"

[output.html]
default-theme = "light"
preferred-dark-theme = "navy"
git-repository-url = "https://github.com/poneding/my-first-book"
git-repository-icon = "fa-github"
edit-url-template = "https://github.com/poneding/my-first-book/edit/master/{path}"
```
