# 抓抓世纪项目设置指南

## 如何发布到GitHub

1. 首先，在GitHub上创建一个新的仓库，命名为 `zhuazhua-century`
2. 将以下命令中的 `你的GitHub用户名` 替换成你的实际用户名
3. 运行以下命令：

```bash
git remote add origin https://github.com/你的GitHub用户名/zhuazhua-century.git
git branch -M main
git push -u origin main
```

4. 启用GitHub Pages：
   - 进入仓库的 Settings 选项卡
   - 向下滚动到 "Pages" 部分
   - 在 "Source" 下拉菜单中选择 "Deploy from a branch"
   - 选择 "main" 分支和 "/" 文件夹
   - 点击 "Save"

完成后，你的小说将在 https://你的GitHub用户名.github.io/zhuazhua-century 上可用