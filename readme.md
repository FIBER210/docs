# Fiber210 文档

访问文档网址：[https://fiber210.github.io/docs/](https://fiber210.github.io/docs/)

## 使用方法

添加内容时，修改 `source` 目录下的 `index.rst` 文件，并添加其他 `.rst` 文件。

添加内容后在main分支push自动更新gh_docs分支和网站

### 添加内容步骤

1. 修改 `source` 目录下的 `index.rst` 文件，添加新 `.rst` 文件的引用。
2. 创建新的 `.rst` 文件来添加额外内容。
3. 在 `index.rst` 文件中，使用以下语法包含新的 `.rst` 文件：

   ```rst
   .. toctree::
      :maxdepth: 2

      new_file
