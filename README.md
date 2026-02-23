# Lenny Skills

A collection of 7 Manus Agent Skills extracted from 200+ episodes of [Lenny's Podcast](https://www.lennyspodcast.com/), featuring insights from world-class product leaders, growth experts, and startup founders.

## Overview

These skills were created by analyzing transcripts from Lenny Rachitsky's podcast, which features conversations with top product managers, growth leaders, and entrepreneurs from companies like Stripe, Airbnb, Meta, Netflix, Spotify, Duolingo, and more.

Each skill contains:
- **SKILL.md** - Core principles, frameworks, and usage guidelines
- **references/knowledge_base.md** - Full insights from podcast guests
- **references/frameworks.md** - Complete list of frameworks mentioned

## Skills

| Skill | Description | Episodes |
|-------|-------------|----------|
| [lennypodcast-product-management](./lennypodcast-product-management) | Product management wisdom covering discovery, delivery, prioritization, roadmaps, metrics, OKRs, and PM frameworks | 200+ |
| [lennypodcast-growth-marketing](./lennypodcast-growth-marketing) | Growth and marketing strategies covering user acquisition, retention, engagement, virality, PLG, monetization, and growth loops | 140+ |
| [lennypodcast-leadership-management](./lennypodcast-leadership-management) | Leadership and management wisdom covering team building, hiring, culture, feedback, 1:1s, performance management, and scaling organizations | 180+ |
| [lennypodcast-career-mastery](./lennypodcast-career-mastery) | Career development wisdom covering career growth, job searching, negotiation, skills development, networking, and personal branding | 190+ |
| [lennypodcast-ai-product-building](./lennypodcast-ai-product-building) | AI product development wisdom covering AI product strategy, LLM applications, ML integration, AI agents, and building AI-native products | 120+ |
| [lennypodcast-strategy-positioning](./lennypodcast-strategy-positioning) | Business strategy and positioning wisdom covering competitive positioning, market analysis, pricing strategy, category design, and strategic decision-making | 150+ |
| [lennypodcast-startup-playbook](./lennypodcast-startup-playbook) | Startup and entrepreneurship wisdom covering founding, fundraising, scaling, pivoting, product-market fit, and building companies | 160+ |

## Installation

To use these skills with Manus, copy the desired skill folder to your `~/skills/` directory:

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/lenny-skills.git

# Copy a skill to your Manus skills directory
cp -r lenny-skills/lennypodcast-product-management ~/skills/
```

## Usage

Once installed, Manus will automatically detect and use these skills when relevant to your task. You can also explicitly reference them:

```
"Use the lennypodcast-product-management skill to help me prioritize my product roadmap"
```

### Searching the Knowledge Base

Each skill includes a comprehensive knowledge base that can be searched:

```bash
# Search for specific topics
grep -i "prioritization\|roadmap" references/knowledge_base.md

# Find specific frameworks
grep -i "RICE\|OKR" references/frameworks.md
```

## Featured Guests

Insights are sourced from conversations with leaders including:

- **Product**: Marty Cagan, Shreyas Doshi, Lenny Rachitsky, Teresa Torres
- **Growth**: Brian Balfour, Elena Verna, Casey Winters, Andrew Chen
- **Leadership**: Claire Hughes Johnson, Julie Zhuo, Kim Scott
- **Strategy**: Hamilton Helmer, Roger Martin, April Dunford
- **Startups**: Paul Graham, Marc Andreessen, Reid Hoffman

## Source

These skills were extracted from [Lenny's Podcast](https://www.lennyspodcast.com/) transcripts using Manus AI. The original extraction task can be viewed at:
https://manus.im/share/KXPpTAB7qRNEIlAvobWDLq

## License

This repository contains curated insights from publicly available podcast content. Please respect the original content creators and refer to Lenny's Podcast for the full episodes.

## Contributing

Contributions are welcome! If you'd like to improve these skills or add new insights, please submit a pull request.
