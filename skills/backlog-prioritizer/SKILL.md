# Backlog Prioritizer

This skill applies RICE or WSJF scoring frameworks to Jira or Trello tasks to help product managers prioritize their backlogs.

## Instructions
1. When the user asks to prioritize a backlog or sort Jira/Trello tickets by priority, use this skill.
2. Ask relevant questions to the user if you need them to provide the raw tasks, clarify the framework (RICE vs WSJF), or provide missing context for scoring.
3. Pass the tasks and chosen framework to the tool.

## Tools

### `prioritizeBacklog`
Applies prioritization scoring to a set of tasks.

**Command:**
```bash
npx tsx index.ts "$tasksJson" "$framework"
```

**Parameters:**
- `tasksJson` (string): A JSON string containing the list of tasks from Jira or Trello.
- `framework` (string): The framework to use, either "RICE" or "WSJF".
