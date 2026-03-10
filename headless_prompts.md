# Headless-Style Prompts

Short, direct, self-contained instructions for clean, single-shot output.

### Quick Utility / One-Shot Tasks
1. `Summarize the following text in exactly 3 bullet points. Output only the bullets, no introduction. Text: [paste text here]`
2. `Convert this markdown to clean HTML. Preserve code blocks and links. Input: [paste markdown] Output only the HTML.`
3. `Generate a bash one-liner that [describe task very precisely, e.g. finds all .js files modified in last 7 days and prints their full paths]. Output only the command, nothing else.`
4. `Write a Python function that takes a list of dicts and returns a new list sorted by the 'priority' key descending, with ties broken by 'created_at' ascending. Include type hints and docstring. Output only the function.`

### Structured / JSON Output
5. `Analyze this error log and respond in JSON format with keys: "error_type", "likely_cause", "suggested_fix", "confidence" (0-100). Log: [paste log] Output only valid JSON.`
6. `Extract all email addresses, URLs and phone numbers from this text as a JSON array of objects with keys "type" and "value". Text: [paste text] Output only JSON.`
7. `Create a detailed SEO title + meta description pair (max 60 chars title, 155 chars description) for this page content: [paste content] Format as JSON: {"title": "...", "description": "..."}`

### Creative / Content Generation
8. `Write a 180–220 word product description for [product name] that sounds premium and benefit-focused. Style: luxury brand voice. Output only the paragraph.`
9. `Generate 5 clickbait-style but truthful YouTube titles for a video about [topic]. Number them 1–5. Output only the list.`
10. `Write a concise, sarcastic error message for when a user forgets to fill in the required field "username". Max 15 words. Output only the message.`

### Code / Dev Helpers
11. `Refactor this JavaScript function to use async/await instead of .then(). Make it cleaner and add error handling. Original: [paste code] Output only the refactored function.`
12. `Write a regex that matches US phone numbers in formats (123) 456-7890, 123-456-7890, 1234567890. Output only the regex pattern as a string.`
13. `Generate a Git commit message in conventional commits format for these changes: [paste git diff or description]. Output only the commit message.`

### Analysis / Reasoning
14. `Rate how maintainable this code is on a scale 1–10 and explain in exactly 2 sentences why. Code: [paste code] Format: Score: X/10\nReason: [sentence1] [sentence2]`
15. `Classify this customer support ticket as one of: bug, feature request, billing, account issue, other. Then give 1-sentence next action. Ticket: [paste ticket] Output format: Category: ...\nAction: ...`
