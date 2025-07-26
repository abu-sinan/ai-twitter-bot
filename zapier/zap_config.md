# ⚙️ Zapier Automation Guide

## Trigger:
Every 12 hours using "Schedule by Zapier"

## Action 1:
**Code by Zapier**:
- Load a random topic from a Google Sheet or `topics.txt`

## Action 2:
**Webhooks by Zapier** (POST):
- Send the topic and prompt to Gemini 2.0 Flash
- Input:
  - `topic`: randomly selected
  - `prompt_template`: use `prompts/prompt_template.txt`
- Output: tweet text

## Action 3:
**Buffer**:
- Add the Gemini-generated tweet to Buffer
- Choose your preferred posting schedule (10AM & 10PM)

## Notes:
- No Twitter/X API required
- Fully no-code (except one tiny Code by Zapier step)