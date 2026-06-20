# ROADMAP.md — Awesome-LLM

## 12-Month Vision (2026 Q3 – 2027 Q2)

Transform Awesome-LLM from a curated paper list into an interactive knowledge platform with structured data, community tools, and automated tracking.

### Q3 2026 — Foundation
- Migrate paper metadata to structured JSON/YAML for programmatic access
- Add automated GitHub Actions to detect new LLM releases via arxiv/huggingface API
- Create a searchable web frontend (static site) for the paper database
- Add benchmark comparison tables for reasoning capabilities across models

### Q4 2026 — Intelligence
- Integrate LLM evaluation benchmarks (HELM, Chatbot Arena, AlpacaEval) with live scores
- Add "LLM Landscape" interactive visualization showing model relationships and evolution
- Community contribution portal with auto-PR from structured paper submissions
- Track multimodal model developments (vision-language, audio, video)

### Q1 2027 — Automation
- Automated weekly digest newsletter summarizing new papers and model releases
- Cross-reference with arxiv-sanity for citation trend analysis
- Add cost-comparison tables for commercial API providers (OpenAI, Anthropic, Google, etc.)
- Integration with HuggingFace model cards for automatic metadata sync

### Q2 2027 — Platform
- Open API for third-party tools to query the LLM knowledge graph
- Community ratings and annotations on papers
- Multi-language support (Chinese, Japanese, Korean LLM tracking)
- Partnership with academic institutions for curated research tracks

## Technical Debt

| Item | Priority | Description |
|------|----------|-------------|
| Static markdown tables | High | Convert to JSON data source with templated rendering |
| Manual updates | High | Automate LLM release tracking via API integrations |
| No search functionality | Medium | Add full-text search across papers and models |
| No versioning | Medium | Implement structured changelog for paper additions |
| Citation badge dependencies | Low | Semantic Scholar API rate limits may cause badge failures |
| Image resources | Low | GIF/JPEG resources not optimized; migrate to WebP |

## Future Features

- **Interactive Model Comparison Tool**: Side-by-side benchmark comparison with filter by architecture, size, license
- **LLM Decision Tree**: Guided workflow to help practitioners choose the right model for their use case
- **Training Cost Calculator**: Estimate compute cost for fine-tuning different LLMs
- **Paper Impact Dashboard**: Track citation velocity and emerging research trends
- **Contributor Leaderboard**: Gamified contribution system with recognition tiers
- **RSS/Atom Feed**: Auto-generated feed for new paper additions
- **LLM Security Tracking**: Dedicated section for adversarial robustness, jailbreaks, and alignment research
