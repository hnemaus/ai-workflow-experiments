# AI Workflow Experiments

Practical experiments showing how AI can replace manual, time-consuming tasks in everyday work. Each experiment follows the same format: Problem → Solution → Prompt → Result.

Built by **Hanne Emaus** — informatikk student at UiO, exploring AI for productivity.

---

## Experiments

### 1. Meeting notes → CRM entry
**Problem:** Writing up customer meeting notes takes 20–30 minutes and varies in quality.
**Solution:** Paste raw notes into a structured prompt.
**Result:** Consistent, professional CRM entry in under 2 minutes.
→ See `experiments/01_meeting_to_crm/`

### 2. Long report → Executive summary
**Problem:** A 40-page report needs to be read before a 9am meeting.
**Solution:** AI extracts key findings, decisions, and action points.
**Result:** Actionable 1-page summary in 60 seconds.
→ See `experiments/02_report_summary/`

### 3. Customer feedback → Insight themes
**Problem:** 200 survey responses sitting unread in a spreadsheet.
**Solution:** AI clusters responses into themes and ranks by frequency.
**Result:** Clear theme map ready for strategy discussion.
→ See `experiments/03_feedback_themes/`

### 4. Job posting → Tailored cover letter draft
**Problem:** Writing cover letters from scratch is slow and often generic.
**Solution:** Feed job posting + CV to AI, get a tailored first draft.
**Result:** 80% done draft in 2 minutes, 20% human personalisation.
→ See `experiments/04_cover_letter/`

---

## Format used in each experiment

```
# Experiment name

## Problem
What task was slow, inconsistent, or painful?

## Solution
What AI approach was used?

## Prompt
[The exact prompt used]

## Result
What came out? How long did it take?

## Learnings
What worked, what didn't, what to try next?
```

---

## How to run these

No installation needed for the prompt-based experiments. Just copy the prompt and paste into ChatGPT or Claude.

For Python scripts:
```bash
pip install anthropic python-dotenv
# Add ANTHROPIC_API_KEY to .env
python script.py
```

---

## Skills demonstrated

- Workflow analysis and automation thinking
- Prompt engineering for real use cases
- Problem → Solution → Result documentation
- Understanding of how AI fits into commercial work
