# UI 资源库 Skill / UI Resource Library

从 [Designeer](https://designeer.xyz/) 与 [UINice](https://uinice.com/) 精选的 **UI / 设计工程资源库**，做成可复用的 Agent Skill：按需求（落地页、SaaS、动效、图标、设计系统、AI 工具）快速选 **一个** 最合适的资源，而不是从零搜索。

Curated UI / design-engineering resources as an agent skill. Pick by need (landing, SaaS, motion, icons, design systems, AI tools) instead of searching from scratch.

## 来源 / Sources

| Source | URL | What we took |
| --- | --- | --- |
| Designeer | https://designeer.xyz/ | Full public catalogue via `llms-full.txt` (422 tools, 17 sections) |
| UINice | https://uinice.com/ | 169 kits across Motion / Components / Design Systems / Templates / Icons, with outbound project URLs |

社区提及 / Featured in: [Designeer teaser](https://x.com/ianneo_ai/status/2108732478043402320) · [UINice](https://x.com/khorn62885776/status/2108747666964586842)

名称与一句话说明来自公开聚合页；链接指向原项目。与上述站点无隶属关系。

## 仓库内容 / Contents

| File | Purpose |
| --- | --- |
| `SKILL.md` | Agent recipe + curated shortlists (Codex / Claude / Grok Bot) |
| `catalog.md` | Full markdown tables by category |
| `resources.json` | Structured full catalog for tooling |
| `README.md` | This file |

**去重后唯一资源 ≈ 547**（Designeer + UINice，按 URL 合并）。

### 分类数量 / Counts

- Design Galleries / Inspiration: **78**
- Components: **165**
- Motion: **51**
- Design Systems: **25**
- Templates: **18**
- Icons: **40**
- Interface / Tokens / Type / Color: **23**
- AI Design Tools / Agents & MCP: **35**
- 3D / Shaders / Visuals: **13**
- Development / Deploy: **29**
- Utilities / Desktop / Capture: **61**
- Reading: **33**

> 同一资源可出现在多个分类（例如既是 Components 又是 Motion）。

## 怎么用 / How to use

### Grok Bot
1. 安装本 skill（`ui-resource-library`）后，在对话里用 `/` 或 `@` 调用。
2. 说明你的界面目标（例如「SaaS 定价页 + 轻动效」），让助手按 `SKILL.md` 路由表选资源。

### Codex / Claude Code / 其他
1. 把本仓库放进项目，或把 `SKILL.md` 拷到助手的 skills 目录。
2. 需要完整列表时读 `catalog.md` 或 `resources.json`。
3. **一次优先只用一个主工具**；缺口再用第二个（例如组件库 + 图标集）。

### 典型路由

- 落地页 → Inspiration → Templates →（可选）Motion → Icons  
- SaaS → Components / Design Systems → Icons  
- 动效营销 → Motion（只选一个库）  
- AI 对话 UI → AI Elements / assistant-ui  

## 更新 / Refresh

```bash
# Designeer machine-readable full list
curl -sL https://designeer.xyz/llms-full.txt -o designeer-llms-full.txt
# UINice: re-scrape category pages (/motion /components /systems /templates /icons)
# then re-resolve each /site/<slug> for the outbound project URL
```

## License

Catalog text is factual link aggregation for personal/agent use. Individual projects keep their own licenses — always check the destination repo before shipping.
