# Fractional Jobs Feed

Automated daily crawl of fractional job listings from dedicated fractional job boards and general job boards.

## Feeds

All feeds are updated daily at 7:00 AM Dubai time (UTC+4).

| Feed | URL |
|-------|-----|
| **All Jobs** | `https://raw.githubusercontent.com/giankar/fractional-jobs/main/feeds/fractional-jobs.json` |
| **By Category** | `https://raw.githubusercontent.com/giankar/fractional-jobs/main/feeds/fractional-jobs-by-category.json` |
| **Time Series** | `https://raw.githubusercontent.com/giankar/fractional-jobs/main/feeds/time-series.json` |

## Job Schema

| Field | Description |
|-------|-------------|
| `id` | Unique identifier |
| `title` | Job title |
| `company` | Company name |
| `location` | Location |
| `url` | Direct link to the job posting |
| `source` | Source website |
| `functional_role` | CMO, CFO, CTO, COO, Product Manager, Sales, Marketing, Operations, Design, Engineering, Data, Finance, HR, Legal, Other |
| `industry` | SaaS, FinTech, HealthTech, E-commerce, AI/ML, EdTech, Real Estate, Consumer, Enterprise, Media, Crypto/Web3, Climate, Other |
| `commitment` | Time commitment |
| `compensation` | Salary/rate info |
| `description` | Brief description |
| `posted_date` | When posted |
| `discovered_date` | When the crawler found it |

---

Powered by [Zaro](https://zaro.ai)
