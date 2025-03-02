# 在GitHub Pages上设置姑苏爱情故事

## 步骤 1: 组织您的仓库

您的仓库应该有以下结构:
```
gusulovestory/
├── index.html
├── game.js
├── README.md
```

所有三个文件都已在您的仓库中，这很完美。

## 步骤 2: 创建 GitHub Pages 站点

1. 前往您的GitHub仓库
2. 点击"Settings"标签
3. 滚动到"GitHub Pages"部分（或在左侧菜单栏中点击"Pages"）
4. 在"Source"下，选择"Deploy from a branch"
5. 选择"main branch"（或者如果您使用的是"master"分支）
6. 点击"Save"

GitHub现在会提供一个网址，您的网站将在那里发布（URL为`https://mrfeixiang.github.io/gusulovestory/`）。

## 步骤 3: 检查您的网站

- 等待几分钟让GitHub部署您的网站
- 访问提供的URL以确保一切正常工作
- 测试您的游戏功能

## 步骤 4: 自定义域名（可选）

如果您想使用自定义域名:
1. 在GitHub Pages设置中输入您的自定义域名
2. 在您的域名提供商处设置适当的DNS记录
3. 在您的仓库中添加一个包含您域名的CNAME文件

## 疑难解答

如果您的网站没有出现:
- 确保index.html在根目录中
- 检查是否在GitHub Pages设置中选择了正确的分支
- 等待几分钟，因为GitHub Pages部署可能需要一些时间
- 检查您的仓库设置中GitHub Pages部分是否有任何错误

如果您的游戏不起作用:
- 打开浏览器开发者工具(F12)检查JavaScript错误
- 确保game.js文件的路径正确
- 验证所有文件名与代码中的引用匹配
