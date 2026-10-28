# 在Typora中使用

在**Typora**中使用步骤如下：

1. 打开 `偏好设置` -> `导出` -> `点击右侧的 + 按钮` -> `从模版添加，选择HTML(without Styles)` -> `添加` -> `修改刚才添加的模版名称，如：Mdtht`
2. 点击添加的模版 Mdtht -> `在<head/>文本框中`  -> `输入：<style> </style>` -> 复制 dist 文件夹中的 **mdtht.min.css** 代码到 `<style>` 标签对中，如：`<style> 复制 mdtht.min.css 的代码到这里 </style>`
   整理在：[在 head 中添加.txt](./在 head 中添加.txt)
3. `在<body/>文本框中`  -> `输入：<script> </script>` -> 复制 dist 文件夹中的 **mdtht.min.js** 的代码到`<script>`标签对中，如：`<script> 复制 mdtht.min.js 的代码到这里 </script>`
   整理在：[在 body 中添加.txt](./在 body 中添加.txt)
4. 样式文件添加完成。
5. 代码高亮：
   1. 下载 highlight.min.js，[highlight.min.js下载地址](https://highlightjs.org/download)，**注意：下载时请选择 “Select all languages”**
   2. 解压下载的文件，参照第 3 步将 highlight.min.js 代码复制到 `<body/>文本框中`
   3. **在 highlight.min.js 代码的最后位置添加代码： `hljs.highlightAll();`** -> `保存完成`。
6. 导出 html 时选择刚刚添加的 Mdtht 模版即可。

