# cugblbs.github.io

这是 [ZhuDong's Blog](https://zhudong.site) 的源码仓库，使用 Jekyll 构建，并通过 GitHub Pages 部署。

[English README](./README.md)

## 项目简介

- 个人博客站点仓库，包含文章、页面、静态资源和主题定制
- 基于 Hux Blog 结构改造，当前站点域名为 `zhudong.site`
- 支持文章发布、标签页、RSS，以及基础 PWA 能力

## 技术栈

- Jekyll
- Liquid 模板
- Grunt
- LESS
- Bootstrap
- jQuery
- GitHub Pages

## 本地开发

### 环境要求

- Ruby / RubyGems
- Node.js / npm
- 已安装 Jekyll 和 `jekyll-paginate`

### 安装依赖

```bash
npm install
gem install jekyll jekyll-paginate
```

### 启动项目

只启动 Jekyll 本地服务：

```bash
jekyll serve
```

如果还需要同时监听 LESS 变更，并用 Python 3 启动 `_site` 目录预览：

```bash
npm run py3wa
```

## 目录说明

- `_posts/`：博客文章
- `_layouts/`：页面与文章布局
- `_includes/`：可复用模板片段
- `less/`：样式源码
- `css/`：编译后的样式
- `js/`：前端脚本
- `img/`：站点图片与文章配图
- `pwa/`：PWA manifest 和图标
- `sw.js`：Service Worker
- `_config.yml`：站点配置

## 部署说明

- 当前仓库用于 GitHub Pages 部署
- `CNAME` 文件保存了自定义域名 `zhudong.site`
- 评审完成后，从仓库默认分支发布变更

## License

许可证见仓库中的 [LICENSE](./LICENSE) 文件。
