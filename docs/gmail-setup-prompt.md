# Gmail Setup Prompt (Validated)

Copy the prompt below into a new ChatGPT chat after using the [Configuration Worksheet](configuration-worksheet.md) to choose your settings. Replace every bracketed field with your choices. The worksheet stays with you; do not attach or upload it.

---

Set up a read-only Email Triage Morning Brief using my connected Gmail account only.

## My configuration

- **Timezone:** [e.g., America/New_York]
- **Lookback window:** [e.g., past 24 hours]
- **Detail level:** [concise / standard / detailed]
- **Priority people or organizations:** [list or “none”]
- **Important topics or keywords:** [list or “none”]
- **Suppress unless urgent:** [list or “none”]

Use only these selected categories. Do not invent, rename, merge, or reorder them:

1. [Category name] — [what belongs here]
2. [Category name] — [what belongs here]
3. [Category name] — [what belongs here]
4. [Category name] — [what belongs here]
5. [Category name] — [what belongs here]
6. [Optional category name] — [what belongs here]

## Rules

- Apply my chosen detail level: **Concise** means only the most important items with brief explanations; **Standard** means a balanced daily brief with enough context to decide what to do; **Detailed** means a fuller update with more useful items and context.
- Review relevant received email in the configured lookback window.
- Exclude Sent, Drafts, Spam, and Trash.
- Use the full message body whenever a subject or snippet is insufficient to classify a potentially important email.
- A reply that creates a concrete next step belongs in the category that represents immediate action, even if I sent the earlier message in the thread.
- Surface only messages that are actionable, time-sensitive, useful, or substantively worth reading under my selected categories.
- Omit repetitive promotions, generic newsletters, social notifications, and other low-value messages unless one of my selected categories or rules includes them.
- Do not state that I replied, applied, booked, paid, or completed an action unless the email thread clearly confirms it.

## Output format

Start every output with:

# Morning Brief — [Weekday, Month Day, Year]

**Coverage:** [start date and time] to [end date and time], [timezone]

Then show only my selected categories. For every surfaced item, include sender, subject, a one-sentence rationale, and a source-email link when available. Add **Processing notes** only for a meaningful retrieval or classification limitation.

## Safety boundary

Read-only access only. Do not send, draft, delete, archive, label, mark spam, unsubscribe, create calendar events, or change account settings. Do not infer missing facts or actions.

Run this once manually. Do not create a scheduled task until I explicitly approve it.
