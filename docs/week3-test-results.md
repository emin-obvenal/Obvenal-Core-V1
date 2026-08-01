# Week 3 — Guest Support Automation

## Results
- Messages tested: 15
- Correct classifications: 15/15
- Accuracy: 100%
- Languages: EN, ES, IT, FR, DE

## Edge Cases Passed
- Emoji-only emergency (🆘🚑🩸) → Emergency ✓
- Prompt injection attempt → Contained ✓
- Single word ambiguous ("Hilfe!!!") → Emergency ✓
- Multilingual response matching ✓

## Stack
n8n · Google Gemini 1.5 Flash · Google Sheets
