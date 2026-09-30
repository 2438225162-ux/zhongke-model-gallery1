# Zhongke 公开图片图库

这是一个可直接发布到 GitHub Pages 的纯静态网站，仅包含 500 张模型图片，不包含 STEP、参数 JSON 或建模源代码。

## 发布

1. 在 GitHub 创建公开仓库 `zhongke-model-gallery`，不要初始化 README。
2. 在本目录打开 PowerShell。
3. 执行：

```powershell
git init -b main
git add .
git commit -m "Publish Zhongke image gallery"
git remote add origin https://github.com/你的用户名/zhongke-model-gallery.git
git push -u origin main
```

4. 打开仓库 `Settings → Pages`，将 Source 设置为 `GitHub Actions`。
5. 等待仓库 Actions 页面中的部署任务完成。

公开网址通常为：

```text
https://你的用户名.github.io/zhongke-model-gallery/
```
