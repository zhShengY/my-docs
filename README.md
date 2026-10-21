# my-docs

开源软件设计与开发 实验二 实践项目二：使用 MkDocs 构建静态文档站，并通过 GitHub Actions 自动部署到 GitHub Pages。

## 目录结构

```
my-docs/
  docs/
    index.md            主页
    about.md            关于页
    guide.md            使用指南
    api.md              API 参考
  .github/workflows/
    deploy.yml          自动部署工作流
  mkdocs.yml            MkDocs 配置
  README.md             项目说明
```

## 部署方式

向 main 分支推送 docs 目录或 mkdocs.yml 的改动时，工作流自动构建站点并把生成结果发布到 gh-pages 分支，由 GitHub Pages 对外提供访问。
