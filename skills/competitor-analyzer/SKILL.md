# Competitor Analyzer

This skill scrapes competitor websites and summarizes their core features, value propositions, and market positioning.

## Instructions
1. Use this skill when the user asks you to analyze a competitor or summarize what a competing product does.
2. Provide the competitor's website URL.

## Tools

### `analyzeCompetitor`
Scrapes the URL and returns a summarized list of features.

**Command:**
```bash
npx tsx index.ts "$url"
```

**Parameters:**
- `url` (string): The URL of the competitor's main website or pricing page.
