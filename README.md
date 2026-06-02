# Shiyu 的资料导航站

这是一个可以直接部署到 GitHub Pages 的静态资料导航站。

## 文件说明

- `index.html`：首页
- `style.css`：样式
- `script.js`：搜索、分类筛选、卡片渲染逻辑
- `data.json`：资料数据，只需要改这里就能更新网站
- `.nojekyll`：让 GitHub Pages 按静态文件发布

## 如何修改内容

打开 `data.json`，按下面格式新增内容：

```json
{
  "title": "资料标题",
  "category": "分类",
  "tags": ["标签1", "标签2"],
  "level": "重点",
  "url": "https://example.com",
  "desc": "资料描述"
}
```

## 如何部署到 GitHub Pages

1. 进入仓库 `Settings → Pages`
2. Source 选择 `Deploy from a branch`
3. Branch 选择 `main`
4. Folder 选择 `/(root)`
5. 点击 `Save`
6. 等待几分钟后访问：`https://tongshiyu92500-cmd.github.io/my-resource-nav/`

## 注意

请只发布你自己拥有权利或可以合法公开的资料。不要发布未授权影视、小说、课程、软件破解等侵权资源。
