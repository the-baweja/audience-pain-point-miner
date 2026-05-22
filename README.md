# Audience Pain Point Miner — Voice-of-Customer Research for Meta Ads

**Mine real customer language from reviews, Reddit, and social media through a structured 5-step pipeline.**

Give Claude a brand or product name and it runs the full research chain — persona definition, source reconnaissance, engagement-sorted collection, adaptive categorization — and builds a pain point library with exact customer quotes ranked by how much the market validated them.

## Install

**Claude Desktop (Cowork):** download [`audience-pain-point-miner.skill`](https://github.com/the-baweja/audience-pain-point-miner/releases/latest) → Settings → Skills → drop it in.

**Claude Code:**
```
git clone https://github.com/the-baweja/audience-pain-point-miner.git ~/.claude/skills/audience-pain-point-miner
```

**Manual:** clone this repo into any skills directory your Claude setup reads from.

## What it does

You give it a brand or product. It runs the **Engagement-First Mining Method** — 5 sequential steps where each step feeds the next:

1. **Persona Definition** — builds or imports customer personas to guide the research (knows WHO to look for before mining)
2. **Source Reconnaissance** — scouts review sites, Reddit, social media, forums, and YouTube to find where the volume lives
3. **Engagement-Sorted Collection** — mines 75-150 data points sorted by upvotes, likes, and replies so the most validated pain points float to the top
4. **Adaptive Categorization** — lets the data tell you how to organize (by persona, emotion, funnel stage, or whatever clusters naturally) instead of forcing pre-built categories
5. **Ad-Ready Language Bank** — transforms raw quotes into hook banks, exact-language snippets, and ad angle suggestions ready for copywriters

## Output

A branded DOCX report with:

- Persona recap and research methodology
- Pain point map ranked by composite score
- Deep dives with 5-10 strongest quotes per category (ranked by engagement)
- Hook bank derived from real customer language
- Gold mine recommendations (top 5 highest-potential pain points)
- Safety net discoveries (pain points only direct research reveals)
- Copy-paste language bank with engagement scores

## Works alone or as a safety net

This skill is designed to work two ways:

- **Standalone** — give it a brand and it does everything from scratch
- **Safety net** — if you've already run the [Competitor Ad Spy](https://github.com/the-baweja/competitor-ad-spy) or [Ad Angle Generator](https://github.com/the-baweja/ad-angle-generator), this catches pain points that competitor-focused analysis misses by going directly to the people

## Customize Your Branding

Edit `references/branding.md` with your own brand colors, typography, and document structure. The skill reads this file to generate reports that match your brand identity.

## Example

Prompt:
```
Mine pain points for Alo Yoga.
They're a premium activewear brand competing with Lululemon.
Focus on what customers actually say about quality, pricing, and service.
```

Output: 5-step research chain completed, 92 data points collected across Trustpilot, Reddit, PissedConsumer, and Thingtesting, organized into 6 adaptive categories — each with engagement-ranked quotes, hook banks, and ad angle suggestions.

## Who this is for

Media buyers, creative strategists, brand owners, and performance marketers who want ad copy grounded in real customer language instead of guesswork.

This is skill 3 of 10 in the **AI Skills for Media Buyers** series by [Baweja Media](https://bawejamedia.com).

---

## Want Baweja Media to audit your ad account and explore opportunities to work together?

[→ Book a strategy call](https://webinar.sannidhyabaweja.com/vsl-lp-ind)

---

Built by [Baweja Media](https://bawejamedia.com) · MIT License
