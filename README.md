# My First Agent

A Gumloop AI agent with web scraping capabilities powered by the [apify-ultimate-scraper](https://skills.sh/apify/agent-skills/apify-ultimate-scraper) skill.

## What this agent can do

- 🌐 **Scrape 55+ platforms** — LinkedIn, Instagram, TikTok, YouTube, Facebook, Google Maps, and more
- 📊 **B2B lead generation** — Find salespeople, executives, and decision-makers by role, company, and location
- 🔍 **Competitor analysis, brand monitoring, SEO intelligence, review analysis**, and more
- 📁 **Export results** as CSV or JSON

## Skills

### `apify-ultimate-scraper`
Universal AI-powered web scraper. Covers ~100 Apify Actors across 15+ platforms with use-case-specific workflow guides.

| Workflow | Use case |
|----------|----------|
| `lead-generation` | B2B prospects, LinkedIn people search |
| `competitive-intel` | Competitor ads, pricing, positioning |
| `influencer-vetting` | Creator discovery and analytics |
| `brand-monitoring` | Mentions, sentiment, social listening |
| `content-and-seo` | SERP scraping, site crawling, RAG data |
| `review-analysis` | Ratings, reputation management |
| `social-media-analytics` | Engagement metrics, audience insights |
| `trend-research` | Keywords, hashtags, Google Trends |
| `job-market-and-recruitment` | Job listings, candidate sourcing |
| `real-estate-and-hospitality` | Listings, hotel/Airbnb data |
| `ecommerce-price-monitoring` | Product pricing, e-commerce data |
| `contact-enrichment` | Email extraction, contact enrichment |
| `knowledge-base-and-rag` | Web crawling for LLM data feeds |
| `company-research` | Due diligence, company profiles |

## Requirements

- [Apify account + API token](https://console.apify.com/settings/integrations) (free tier available)

## Repository structure

```
AGENT.md                          # Agent configuration
skills/
  apify-ultimate-scraper/
    SKILL.md                      # Skill instructions
    references/
      actor-index.md              # 55+ platform Actor lookup table
      gotchas.md                  # Pricing & common pitfalls
      workflows/                  # 14 workflow guides
```
