# H5 小游戏合集

批量生产的轻量级 H5 休闲游戏，适合部署到：
- Cloudflare Pages（单个项目，多游戏）
- TikTok H5 Channel
- 微信小程序（需适配）
- 任意静态网站托管

## 🎮 游戏列表

| 游戏 | 访问路径 | 描述 |
|------|---------|------|
| [Space Runner](space-runner/) | `/space-runner/` | 太空跑酷，横版跳跃闯关 |

## 🚀 部署到 Cloudflare Pages

1. 在 Cloudflare Dashboard 创建 Pages 项目
2. 连接 `zerowq/game_h5` 仓库
3. 配置：
   - **Framework preset**: `None`
   - **Build command**: 留空
   - **Output directory**: 留空（根目录）
4. 部署完成后访问：
   - 游戏大厅: `https://your-project.pages.dev/`
   - Space Runner: `https://your-project.pages.dev/space-runner/`

## 📁 目录结构

```
game_h5/
├── index.html          ← 游戏大厅首页
├── css/
│   └── style.css       ← 大厅样式
├── space-runner/       ← 每个游戏一个目录
│   ├── index.html
│   └── README.md
├── snake-game/         ← 新游戏目录（待添加）
│   ├── index.html
│   └── README.md
└── .gitignore
```

## ➕ 添加新游戏

1. 在根目录创建新文件夹（如 `snake-game/`）
2. 放入 `index.html`（游戏主文件）
3. 提交到仓库，Cloudflare 自动部署
