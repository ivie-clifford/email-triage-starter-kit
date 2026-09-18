# Outlook Setup Prompt (Pilot)

Use this if your email is in Outlook. It follows the same configuration flow as Gmail, but Outlook access must be validated with one manual, read-only run before you create a schedule.

Before starting, check **Settings → Apps** (or Connections) in ChatGPT for **Outlook Email**.

- If it is available, connect your own Outlook account and continue.
- If Microsoft or your employer requests administrator approval, stop and ask your administrator. Do not seek a workaround.
- If Outlook Email is not listed, this route is not available for your account yet.

Complete the [Configuration Worksheet](configuration-worksheet.md), selecting **Outlook Email** as your provider. Keep the worksheet open or copy your choices into a note—do not upload it.

Copy the prompt below into a new ChatGPT chat and replace every bracketed field.

---

Set up one read-only Email Triage Morning Brief using my connected Outlook Email account only. Do not use Gmail, other connected apps, prior chat context, external files, or existing Email Triage configurations. Do not create a scheduled task yet.

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
- Exclude Sent Items, Drafts, Junk Email, and Deleted Items.
- Use the full message body whenever a subject or preview is insufficient to classify a potentially important email.
- A reply that creates a concrete next step belongs in the category that represents immediate action, even if I sent the earlier message in the thread.
- Surface only messages that are actionable, time-sensitive, useful, or substantively worth reading under my selected categories.
- Omit repetitive promotions, generic newsletters, social notifications, and other low-value messages unless one of my selected categories or rules includes them.
- Do not state that I replied, applied, booked, paid, or completed an action unless the email thread clearly confirms it.

## Output format

Start every output with:

# Morning Brief — [Weekday, Month Day, Year]

**Coverage:** [start date and time] to [end date and time], [timezone]

Then show only my selected categories. For every surfaced item, include sender, subject, a one-sentence rationale, and a source-email link when available. Add **Processing notes** only for a meaningful retrieval, classification, or permission limitation.

## Safety boundary

Read-only access only. Do not send, draft, delete, archive, label, mark spam, unsubscribe, create calendar events, or change account settings. Do not infer missing facts or actions.

Run this once manually. Afterward, report whether Outlook Email access worked, how many messages were reviewed, whether full-body retrieval was needed, any limitation that would prevent reliable recurrence, and whether this configuration is ready for one scheduled test. Do not create a scheduled task until I explicitly approve it.
