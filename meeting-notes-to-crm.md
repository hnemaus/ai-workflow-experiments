# Experiment: Meeting Notes → CRM Summary

## Problem
Salgsteam bruker mye tid på å skrive møtereferater og oppdatere CRM.

## Workflow

1. Ta rå møtenotater
2. Send til LLM
3. Strukturér til CRM-felter

## Prompt

Summarize the following meeting notes into CRM fields.

Return:

Company:
Contact person:
Main needs:
Budget signal:
Next action:

Meeting notes:
{{meeting_notes}}

## Example Output

Company: Nordic Retail AS  
Contact: Lars Hansen  
Needs: Automatisere rapportering  
Budget signal: Medium  
Next action: Send demo proposal
