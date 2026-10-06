# 🌐 Social Media OpenAPI Specs

OpenAPI 3.0 specifications for all 13 social media platforms supported by [Zernio](https://zernio.com).

Use these specs to explore, test, and build integrations with the APIs behind the most popular social media platforms.

## 📋 Platforms

| Platform | File | Endpoints | Source |
|----------|------|-----------|--------|
| Pinterest | `pinterest.yaml` | 236 | Official spec |
| Twitter/X | `twitter.yaml` | 147 | Official spec |
| Reddit | `reddit.yaml` | 50 | Official docs |
| Reddit Ads | `reddit-ads.yaml` | 109 | Official spec (OpenAPI 3.1) |
| YouTube | `youtube.yaml` | 42 | Official docs |
| Instagram | `instagram.yaml` | 36 | Official docs |
| Telegram | `telegram.yaml` | 34 | Official spec |
| Bluesky | `bluesky.yaml` | 34 | Official docs |
| Threads | `threads.yaml` | 29 | Official docs |
| Google Business | `googlebusiness.yaml` | 48 | Official docs |
| Facebook | `facebook.yaml` | 28 | Official docs |
| Snapchat | `snapchat.yaml` | 27 | Official docs |
| LinkedIn | `linkedin.yaml` | 27 | Official docs |
| TikTok (developer lane) | `tiktok.yaml` | 22 | Official docs |
| TikTok for Business | `tiktok-business.yaml` | 21 | Official docs + live verification |
| **Total** | | **890** | **13 platforms, 15 specs** |

> **TikTok ships two unrelated organic APIs.** `tiktok.yaml` is the developer lane on
> `open.tiktokapis.com` (Content Posting, Display, Research). `tiktok-business.yaml` is the
> TikTok for Business lane on `business-api.tiktok.com` (Accounts, publishing, comment reads,
> Business Messaging). They use different hosts, different portals, different auth headers and
> app-scoped identities that do not map onto each other, so an integration picks one.

## 🔍 Sources

- **Official specs**: downloaded directly from platform-maintained repositories (Pinterest, Twitter/X, Telegram) or the platform's own published spec (Reddit Ads, `https://ads-api.reddit.com/api/v3/openapi.json`)
- **Official docs** — Hand-crafted from official API documentation, covering all available endpoints
- **Official docs + live verification**: hand-crafted from official documentation and corrected against live production responses where the docs are absent or wrong

## 🚀 Usage

These specs work with any OpenAPI-compatible tool:

- **[Swagger Editor](https://editor.swagger.io/)** — Visualize and explore endpoints
- **[Postman](https://www.postman.com/)** — Import and test API calls
- **[Insomnia](https://insomnia.rest/)** — API client with OpenAPI support
- **Code generation** — Use [OpenAPI Generator](https://openapi-generator.tech/) to generate client SDKs

## 💜 About Zernio

**[Zernio](https://zernio.com)** is a social media API for developers. One unified API to publish content across all 13 platforms listed above. No need to wrangle individual platform APIs, OAuth flows, or rate limits yourself.

👉 **[Get started](https://zernio.com)** — Start building for free.

📺 **[Watch the demo](https://www.youtube.com/watch?v=2TzRQn-Ib_s)**

💡 **[Request a feature](https://late.featurebase.app/)**

## 🤝 Contributing

Found a missing endpoint or an error? PRs are welcome! Please make sure your changes follow the OpenAPI 3.0.3 specification.

## 📄 License

MIT
