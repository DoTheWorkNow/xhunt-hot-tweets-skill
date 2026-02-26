# xhunt-hot-tweets-skill

Skill for extracting XHunt hot tweets with structured Chinese summaries.

## What it does
- Pulls trending tweets from XHunt (`global/cn`, `1h/4h/24h`, optional tags)
- Outputs stable format: link + one-line summary + engagement stats
- Supports filtering modes:
  - `all` (include politics/controversy)
  - `ai-product-only` (focus on AI products/models/tools)

## Trigger examples
- 四小时最火帖子
- 只要 AI 的最火推文，给我 Top20
- 给我热门帖子链接+摘要

## File structure
- `SKILL.md` (main skill instructions)

## Notes
- Data source: `https://trends.xhunt.ai`
- Preferred extraction via browser snapshot; fallback to web fetch when needed.
