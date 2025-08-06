# personstudy
路桑的个人介绍网站

## 部署说明
这个仓库已配置为自动部署到 GitHub Pages。

### 网站地址
- 生产环境：https://hongxuliu0227.github.io/personstudy/

### 自动部署
- 当代码推送到 `main` 或 `master` 分支时，会自动触发部署
- 也可以在 GitHub Actions 页面手动触发部署
- 部署完成后，网站会自动更新

### 本地开发
要在本地预览网站，可以运行：
```bash
python3 -m http.server 8000
```
然后在浏览器中访问 http://localhost:8000
