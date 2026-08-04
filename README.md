# Thank You Satoshi Nakamoto

一个向比特币创造者中本聪致敬的极简网站。

## 风格特点

- 纯黑背景 + 等宽字体
- 比特币创世区块引用
- 21 种语言感谢语轮播动画
- 比特币橙 (#F7931A) 强调色
- 完全响应式设计

## 本地预览

```bash
# 直接用浏览器打开
open index.html

# 或用本地服务器
npx serve .
```

## 部署到 Cloudflare Pages

### 方式一：通过 Git 连接（推荐）

1. 将此仓库推送到 GitHub
2. 登录 [Cloudflare Dashboard](https://dash.cloudflare.com)
3. 进入 **Workers & Pages** → **Create application** → **Pages**
4. 连接你的 GitHub 仓库
5. 构建设置：
   - **Framework preset**: None
   - **Build command**: （留空）
   - **Build output directory**: `/`
6. 点击 **Save and Deploy**

### 方式二：通过 Wrangler CLI

```bash
# 安装 wrangler
npm install -g wrangler

# 登录 Cloudflare
wrangler login

# 部署
wrangler pages deploy . --project-name=thank-you-satoshi
```

### 方式三：直接上传

1. 将 `index.html` 打包为 zip
2. 在 Cloudflare Pages Dashboard 选择直接上传

## 技术栈

- 纯 HTML/CSS/JavaScript，零依赖
- 无构建步骤
- Cloudflare Pages 静态托管

## License

MIT
