# 1A1zP1eP5QGefi2DMPTfTL5SLmv7DivfNa — 比特币创世地址

> 中本聪的比特币创世地址致敬网站

🌐 **线上地址**: [1a1zp1ep5qgefi2dmptftl5slmv7divfna.com](https://1a1zp1ep5qgefi2dmptftl5slmv7divfna.com)

## SEO 策略

### 核心目标
当任何人在 Google 搜索 `1A1zP1eP5QGefi2DMPTfTL5SLmv7DivfNa` 时，本站排名 Top 1。

### 已实施的 SEO 优化

| 优化项 | 详情 |
|--------|------|
| **精确匹配域名 (EMD)** | 域名 = 地址小写形式，Google 最高权重信号 |
| **Title 标签** | 地址 + 关键词「比特币创世地址」+ 英文 |
| **Meta Description** | 包含地址、中本聪、创世区块、50 BTC 等关键词 |
| **Structured Data** | WebSite + FAQPage + BreadcrumbList (JSON-LD) |
| **Open Graph** | 完整 OG 标签 + 自制 OG 图片 |
| **Twitter Card** | summary_large_image |
| **Canonical** | 规范化 URL |
| **Hreflang** | zh-CN / en / x-default |
| **Robots.txt** | 允许抓取，指向 sitemap |
| **Sitemap.xml** | 包含 hreflang 交替链接 |
| **语义化 HTML** | H1/H2 结构化内容 |
| **富文本内容** | 1000+ 字中文 SEO 文案，覆盖长尾关键词 |
| **FAQ Schema** | 4 个常见问题，可触发 Google 富摘要 |
| **内链策略** | 链向 Blockchain.com 地址页 |
| **安全头** | HSTS / X-Frame-Options / CSP |
| **性能** | 零依赖，纯 HTML/CSS/JS |
| **移动端** | 完全响应式 |

### 目标关键词

**主关键词:**
- `1A1zP1eP5QGefi2DMPTfTL5SLmv7DivfNa`
- 比特币创世地址
- Bitcoin Genesis Address
- 中本聪地址

**长尾关键词:**
- 比特币第一个地址
- 创世区块地址
- Satoshi Nakamoto address
- 比特币创世区块
- Genesis Block Bitcoin
- 1A1zP1eP5QGefi2DMPTfTL5SLmv7DivfNa 余额
- 中本聪有多少比特币

### 竞争分析
目前 Google 搜索该地址，结果全是雪球、知乎、CSDN、腾讯云等平台的文章。**没有一个结果使用这个域名**。本站拥有：
1. 精确匹配域名 (最高 SEO 权重)
2. 地址本身就是域名 (URL 完全匹配搜索词)
3. 独立站 vs 平台文章 (域名权威性会随时间增长)

## 功能

- ⛓️ **实时链上数据** — 自动从 Blockchain.info 拉取地址余额和交易数
- 🌍 **21 语言感谢语轮播** — 中/英/日/韩/西/法/德/意/葡/俄/土/阿/希伯来/印地/印尼/泰/越/希腊/波兰/荷兰/波斯
- 📱 **响应式设计** — 完美适配手机/平板/桌面
- ⚡ **零依赖** — 纯 HTML/CSS/JS，无框架无构建
- 🎨 **比特币风格** — 纯黑背景 + 比特币橙 #F7931A

## 部署到 Cloudflare Pages

### 方式一：Git 连接（推荐）

1. Fork 或 clone 本仓库
2. Cloudflare Dashboard → Workers & Pages → Create → Pages
3. 连接 GitHub 仓库
4. 构建设置：无构建命令，输出目录 `.`
5. 部署

### 方式二：Wrangler CLI

```bash
npm install -g wrangler
wrangler login
wrangler pages deploy . --project-name=thank-you-satoshi
```

## 文件结构

```
├── index.html      # 主页面（含 SEO + 实时数据 + 多语言轮播）
├── og-image.png    # 社交媒体分享图
├── robots.txt      # 爬虫规则
├── sitemap.xml     # 站点地图
├── _headers        # Cloudflare 安全头 + 缓存策略
├── _redirects      # Cloudflare 重定向规则
├── wrangler.toml   # Cloudflare Workers 配置
├── LICENSE         # MIT
└── .gitignore
```

## License

MIT
