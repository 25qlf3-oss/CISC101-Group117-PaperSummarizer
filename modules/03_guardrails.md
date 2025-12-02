# Change Log
- Added strict evidence mode.
- Added standardized warnings for missing or short sections.

Module 3: guardrails
- check missing or empty sections
- flag sections with less than 50 words
- prevent hallucinations
- apply chunking if the section is long

## Strict Evidence Mode

Variable:

IF evidence_mode == "strict":
- Only use claims directly stated in the paper.
- Do NOT infer missing logic.
- If insufficient content, output:

"The source text does not provide enough detail to summarize this section in strict evidence mode."

## Section Warnings

If section is missing or empty:
"Section skipped: no usable text was provided."

If section < 50 words:
"Section very short: summary may be incomplete."
