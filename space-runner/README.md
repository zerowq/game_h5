# 🚀 Space Runner — 太空跑酷

纯 HTML5 Canvas 实现的横版跑酷小游戏，无需任何依赖，单文件即可运行。

## 玩法

- 点击/触摸屏幕控制角色跳跃
- 躲避障碍物，尽可能跑得更远
- 分数越高越好

## 技术栈

- 纯 HTML5 + CSS3 + JavaScript
- 无第三方依赖
- 响应式设计，支持移动端

## 本地预览

```bash
# 直接用浏览器打开
open space-runner/index.html

# 或用简单 HTTP 服务器
cd space-runner
python3 -m http.server 8080
# 访问 http://localhost:8080
```

## 部署

### Cloudflare Pages
直接推送此目录到 GitHub，在 Cloudflare 绑定仓库即可自动部署。

### 任意静态托管
`index.html` 是完整游戏，上传到任何静态网站托管服务即可。
