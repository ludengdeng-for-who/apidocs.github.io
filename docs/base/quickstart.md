## 初始化项目
推荐全局安装`docsify-cli`工具，可以方便地创建及在本地预览生成的文档。

```bash
npm i docsify-cli -g
```

## 开始写文档
初始化成功后，可以看到 <code>./docs</code> 目录下创建的几个文件

* <code>index.html</code> 入口文件
* <code>README.md</code> 会做为主页内容渲染
* <code>.nojekyll</code> 用于阻止 GitHub Pages 忽略掉下划线开头的文件

直接编辑 <code>docs/README.md</code> 就能更新文档内容，当然也可以[添加更多页面](base/more-pages.md)。

## 本地预览
通过运行 <code>docsify serve</code> 启动一个本地服务器，可以方便地实时预览效果。默认访问地址 http://localhost:3000 。

```bash
docsify serve docs
```

?> 更多命令行工具用法，参考 [docsify-cli 文档](https://github.com/docsifyjs/docsify-cli)。
