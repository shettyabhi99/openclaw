# PRD Generator

This skill generates Product Requirements Documents (PRDs) from a given title and description.

## Instructions
1. When the user asks you to generate a PRD, use this skill.
2. Provide the `title` and `description` to the tool.

## Tools

### `generatePRD`
Generates a structured Product Requirements Document based on the provided title and brief description.

**Command:**
```bash
npx tsx index.ts "$title" "$description"
```

**Parameters:**
- `title` (string): The title of the feature or product.
- `description` (string): A short description of the feature or product to base the PRD on.
