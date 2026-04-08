# 智能补货模块 Demo - 部署指南

## 文件说明

- `index.html` - 演示入口页面（导航首页）
- `P01_补货工作台.html` - 补货工作台
- `P03_补货策略编辑页.html` - 策略编辑页
- `P04_补货建议池.html` - 补货建议池
- `P06_预警中心.html` - 预警中心
- `P08_数据分析看板.html` - 数据分析看板
- `README.md` - 项目说明

## 本地预览

直接在浏览器中打开 `index.html` 即可查看演示。

无需任何服务器环境，所有资源使用 CDN 加载。

## 在线部署方案

### 方案1：GitHub Pages（推荐）

1. 创建一个新的 GitHub 仓库
2. 将这些文件上传到仓库根目录
3. 进入 Settings → Pages
4. Source 选择 "Deploy from a branch"
5. Branch 选择 "main"，文件夹选择 "/ (root)"
6. 保存后等待几分钟，访问 `https://你的用户名.github.io/仓库名/`

### 方案2：Vercel（推荐）

1. 注册 Vercel 账号 (vercel.com)
2. 导入 GitHub 仓库 或 直接上传文件夹
3. Framework Preset 选择 "Other"
4. 点击 Deploy
5. 获得 `.vercel.app` 域名链接

### 方案3：Netlify

1. 注册 Netlify 账号 (netlify.com)
2. 拖拽文件夹到 Deploy 区域
3. 自动获得 `.netlify.app` 域名链接

### 方案4：Gitee Pages（国内访问快）

1. 创建 Gitee 仓库
2. 上传文件
3. 进入 服务 → Gitee Pages
4. 选择部署分支
5. 获得 `gitee.io` 域名链接

## 分享链接格式

部署成功后，分享以下链接给面试官：

```
https://你的域名/index.html
```

或直接进入某个页面：

```
https://你的域名/P01_补货工作台.html
https://你的域名/P03_补货策略编辑页.html
...
```

## 注意事项

1. 所有页面使用 CDN 资源，确保网络可访问外网
2. 建议使用 Chrome/Edge 浏览器访问
3. Demo 数据为 Mock 数据，刷新页面会重置
4. 如需修改文案或样式，直接编辑 HTML 文件即可

## 技术栈

- React 18 (CDN)
- Tailwind CSS (CDN)
- Font Awesome 图标
- 单文件 HTML，零构建

## 配色方案

- 主色：天青 #6C9BCA
- 辅助色：榴萼黄 #F9A633
- 成功：青绿 #53B886
- 错误：朱红 #C45C4A
