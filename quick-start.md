# Quick Start

This kit creates a read-only Morning Brief from your email in ChatGPT. It does not send, draft, delete, archive, label, or otherwise change email.

## 1. Choose your email provider

| Provider | Setup file | Status |
| --- | --- | --- |
| Gmail | [Gmail Setup Prompt](gmail-setup-prompt.md) | Validated |
| Outlook Email | [Outlook Setup Prompt](outlook-setup-prompt.md) | Pilot — test manually first |

If you use a work Outlook account, your employer may need to allow the Outlook connection.

## 2. Confirm access

In ChatGPT, open **Settings → Apps/Connections** and confirm that your chosen email provider is available to connect.

For Outlook, stop here if your organization blocks the connection or requires administrator approval.

## 3. Choose your preferences

Read [Configuration Worksheet](configuration-worksheet.md) and decide:

- the email provider you are using;
- your timezone and lookback window;
- concise, standard, or detailed output;
- categories, priority people, keywords, and items to suppress.

The worksheet is a planning aid. You do **not** need to download, upload, or attach it.

## 4. Run a manual brief

Open the appropriate setup file, copy its prompt into a new ChatGPT chat, and replace the bracketed configuration choices with yours.

- Gmail: [Gmail Setup Prompt](gmail-setup-prompt.md)
- Outlook: [Outlook Setup Prompt](outlook-setup-prompt.md)

Review the first output carefully before creating any schedule.

## 5. Schedule only after review

Create a recurring task only when:

- the email connection works;
- the brief is useful and correctly categorized;
- the output includes the expected date and coverage window; and
- you are comfortable with the connected-email permissions.

## 6. Adjust as you learn

Update your copied prompt when you want different categories, priorities, output detail, or suppression rules. The repository files remain your reusable starting point.
