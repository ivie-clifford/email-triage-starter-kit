# Outlook Pilot — Manual Test

Use this path if your email is in Outlook. It is a **manual, read-only pilot**: do not create a recurring task until this first brief works and you have reviewed it.

## 1. Check that you can connect Outlook Email

In ChatGPT, open **Settings → Apps** (or Connections) and look for **Outlook Email**.

- If you can connect it, continue.
- If your employer or Microsoft requests administrator approval, stop and ask your administrator. Do not try to bypass the restriction.
- If Outlook Email is not listed, this route is not available for your account yet.

## 2. Choose your settings

Choose your timezone, lookback window, priority people or organizations, important topics, exclusions, categories, and detail level. You can write these down in a note; do not upload anything to ChatGPT.

## 3. Run this one-time prompt

Copy this into a new ChatGPT chat and replace the bracketed fields:

---

Run one read-only Email Triage Morning Brief using my connected Outlook Email account only. Do not use Gmail, other connected apps, prior chat context, external files, or existing Email Triage configurations. Do not create a scheduled task.

Review relevant email received in the past [lookback window]. Exclude Sent Items, Drafts, Junk Email, and Deleted Items. Use the full message body whenever a subject or preview is insufficient to classify a potentially important email.

My detail level is [concise / standard / detailed]. My priority people or organizations are [list or “none”]. My important topics or keywords are [list or “none”]. Suppress [list or “none”] unless urgent.

Use only these categories. Do not invent, rename, merge, or reorder them:

1. [Category name] — [what belongs here]
2. [Category name] — [what belongs here]
3. [Category name] — [what belongs here]
4. [Category name] — [what belongs here]
5. [Category name] — [what belongs here]
6. [Optional category name] — [what belongs here]

Start with:

# Morning Brief — [Weekday, Month Day, Year]

**Coverage:** [start date and time] to [end date and time], [timezone]

For every surfaced item, include sender, subject, a one-sentence rationale, and a source-email link when available. Add **Processing notes** only for a meaningful retrieval or classification limitation.

Read-only access only. Do not send, draft, delete, archive, label, mark spam, unsubscribe, create calendar events, change account settings, or infer missing facts or actions.

After the brief, report: whether Outlook Email access worked; number of messages reviewed; number of full-body retrievals; any permission or retrieval limitation; and whether this configuration is ready for a scheduled test. Do not schedule anything until I explicitly approve it.

---

## 4. Decide what happens next

If the brief is useful and the validation reports no material limitation, you may ask ChatGPT in that same chat to schedule one low-frequency test run. If it fails, record only the connection or permission issue—never email content—and keep using the Gmail route or revisit when your Outlook access changes.
