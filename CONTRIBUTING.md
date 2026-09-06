# Contributing

Corrections matter more on this list than on most. Prices and engine coverage in this category change monthly, and we are a vendor in our own table, so outside eyes keep it honest.

## A note on our bias

RankSpot maintains this list and competes with most of the tools on it. That is disclosed at the top of the README, and it is the reason this file exists in the form it does.

We will merge a PR that makes a competitor look better than RankSpot, as long as it is accurate. We will not merge one that makes a competitor look worse without a source. If you think an entry is slanted, open an issue and say so plainly.

## What gets listed

A tool qualifies if it does at least one of these:

1. **Measures** brand presence in AI answers across one or more engines.
2. **Improves** it, through content generation, delivery to crawlers, or concrete recommendations.
3. **Supports** the work, llms.txt tooling, AI crawler analytics, AI readiness auditing.

## What does not get listed

- Agencies and consultancies. This is a list of tools.
- Traditional rank trackers that added an "AI" label without tracking any AI engine.
- Waitlists and launch announcements. Ship it first.
- Anything we cannot verify the existence of.

## Adding a tool

Open a PR that adds one row. Fill every column, and if you cannot verify one, write `Not published` rather than guessing.

```
| [Tool](https://example.com/) | ChatGPT, Perplexity, AIO | Daily | $49 | Yes | No |
```

- **Engines**: the specific engines, on the entry plan. If coverage is gated by tier, say so, as the Otterly and Profound rows do.
- **Refresh**: how often prompts re-run. Not "real time" unless it genuinely is.
- **From**: cheapest paid monthly price. Prefix with `~` if the vendor does not publish it. Say what the entry plan includes if the prompt allowance is unusually small.
- **API** and **MCP**: which tier, if gated.

**Cite the vendor page** in your PR description. We check every figure against the vendor's own pricing page, not against a comparison blog, because comparison blogs copy each other's stale numbers.

## Correcting a price

Open a PR or an issue with a link to the vendor page showing the current figure. This is the most useful contribution you can make here, and it is the thing that rots fastest.

## Self-submissions

Submitting your own tool is fine. Say so in the PR, fill the columns factually, and expect the marketing language to get edited out. We list competitors, so we will list you.
