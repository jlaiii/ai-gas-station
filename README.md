# ⛽ AI Gas Station

**Shop around. Don't overpay for AI tokens.**

A fun, animated comparison site showing AI provider token pricing — using the gas station metaphor.

**Live site:** [jlaiii.github.io/ai-gas-station](https://jlaiii.github.io/ai-gas-station)

## What's This About?

AI coding tools like Claude Code, Codex CLI, and Cursor all burn tokens — but the provider behind the scenes charges wildly different prices. This site visualizes the price gap between providers using a gas station theme:

- ⛽ **Regular (87)** — Budget tier: DeepSeek v4-flash, Gemini 3 Flash, GPT-5.4 mini
- ⛽ **Plus (89)** — Mid tier: DeepSeek v4-pro, Claude Haiku, Gemini 3 Pro
- ⛽ **Premium (93)** — Pro tier: Claude Sonnet, GPT-5.4
- ⛽ **Ultra (98)** — Top tier: Claude Opus, GPT-5.5

## The Numbers Are Wild

| Provider | Output $/1M tokens |
|----------|-------------------|
| DeepSeek v4-flash | $0.28 |
| DeepSeek v4-pro | $0.87 |
| Claude Sonnet 4.6 | $15.00 |
| GPT-5.5 | $30.00 |

**The cheapest model is 107x cheaper than the most expensive.**

## Running Locally

```bash
git clone https://github.com/jlaiii/ai-gas-station.git
cd ai-gas-station/docs
python3 -m http.server 8080
# Open http://localhost:8080
```

## Data Sources

Pricing data sourced from official provider pages (May 2026):
- [DeepSeek Pricing](https://api-docs.deepseek.com/quick_start/pricing)
- [Anthropic Pricing](https://claude.com/pricing)
- [OpenAI Pricing](https://openai.com/api/pricing/)
- [Google Gemini Pricing](https://ai.google.dev/pricing)
