# Meeting Notes → CRM Entry

## Problem
Sales teams spend 20–30 minutes writing structured CRM entries after meetings. Notes are often messy and inconsistent.

## Solution
Use AI to convert raw notes into a structured CRM entry with consistent fields.

## Prompt

Summarize the following meeting notes into structured CRM fields.

Return:

Company:
Contact person:
Key needs:
Budget signal:
Next step:

Meeting notes:
{{meeting_notes}}

## Result

Raw notes pasted into the prompt produced a structured CRM summary in under 30 seconds.

Example output:

Company: Nordic Retail AS  
Contact person: Lars Hansen  
Key needs: automate reporting workflow  
Budget signal: medium  
Next step: schedule product demo

## Learnings

Structured prompts produce far more consistent output than open-ended prompts.  
Explicit field names reduce hallucination.
