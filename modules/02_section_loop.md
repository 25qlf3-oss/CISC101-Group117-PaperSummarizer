# Change Log
- Added summary_level variable to control short vs detailed summaries.
- Implemented conditional logic for output format based on summary level.

Module 2: section Loop
- summarize each section (words. less than or equal to 20% of text length)
- extract key points

## Summary Level Control

Variable:

Conditional Behavior:

IF summary_level == "short":
- Output 1–2 sentence section summary only

IF summary_level == "detailed":
- Output:
  - One short paragraph summary
  - 3–5 bullet-point key ideas
