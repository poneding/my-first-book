# giscus

## 配置

参考说明：<https://giscus.app/zh-CN>

获取到 js 代码，格式如下：

```html
<script src="https://giscus.app/client.js"
        data-repo="[在此输入仓库]"
        data-repo-id="[在此输入仓库 ID]"
        data-category="[在此输入分类名]"
        data-category-id="[在此输入分类 ID]"
        data-mapping="pathname"
        data-strict="0"
        data-reactions-enabled="1"
        data-emit-metadata="0"
        data-input-position="bottom"
        data-theme="preferred_color_scheme"
        data-lang="zh-CN"
        crossorigin="anonymous"
        async>
</script>
```

## 使用

```bash
vim theme/index.hbs
```

在 `{{{ content }}}` 下方添加获取到的代码，最终内容如下：

```html
                <div id="content" class="content">
                    <main>
                        {{{ content }}}
                        <script src="https://giscus.app/client.js"
                                data-repo="poneding/my-first-book"
                                data-repo-id="R_kgDOMHy7cQ"
                                data-category="General"
                                data-category-id="DIC_kwDOMHy7cc4CgAPA"
                                data-mapping="pathname"
                                data-strict="0"
                                data-reactions-enabled="1"
                                data-emit-metadata="0"
                                data-input-position="top"
                                data-theme="preferred_color_scheme"
                                data-lang="zh-CN"
                                data-loading="lazy"
                                crossorigin="anonymous"
                                async>
                        </script>
                    </main>
```
