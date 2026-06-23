# Roadmap Builder

This skill generates structured timelines and milestones for product initiatives.

## Instructions
1. Use this skill when the user asks you to map out a timeline, generate a roadmap, or define milestones for a set of tasks.
2. Pass the list of initiatives and the desired timeframe (e.g. Q3, H2, next 6 months).

## Tools

### `buildRoadmap`
Generates a structured roadmap.

**Command:**
```bash
npx tsx index.ts "$initiativesJson" "$timeframe"
```

**Parameters:**
- `initiativesJson` (string): JSON string containing the list of initiatives or epics.
- `timeframe` (string): The timeline constraint (e.g., "Q3 2026").
