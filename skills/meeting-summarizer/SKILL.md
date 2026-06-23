# Meeting Summarizer

This skill ingests raw meeting transcripts and outputs a concise list of highlights, action items, and decisions.

## Instructions
1. Use this skill when the user provides a raw meeting transcript or asks you to summarize a recent meeting.
2. Provide the raw transcript to the tool.

## Tools

### `summarizeMeeting`
Ingests a transcript and outputs a summary.

**Command:**
```bash
npx tsx index.ts "$transcript"
```

**Parameters:**
- `transcript` (string): The raw text transcript of the meeting.
