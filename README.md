# H5 小游戏合集

批量生产的轻量级 H5 休闲游戏，适合部署到：
- Cloudflare Pages
- TikTok H5 Channel
- 微信小程序（需适配）
- 任意静态网站托管

## 游戏列表

| 游戏 | 描述 | 目录 |
|------|------|------|
| Space Runner | 太空跑酷，横版跳跃闯关 | [`space-runner/`](space-runner/) |

## 部署到 Cloudflare Pages

1. 安装 Wrangler: `npm install -g wrangler`
2. 每个游戏目录下会有对应的 `wrangler.toml`
3. 部署: `wrangler pages deploy ./space-runner --project-name=game-h5`

## 快速预览

直接在浏览器中打开 `space-runner/index.html` 即可游玩。
