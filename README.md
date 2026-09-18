# Email Triage Starter Kit

Turn a connected Gmail inbox into a personalized, read-only Morning Brief in ChatGPT.

This is a setup kit, not a hosted email service. Each person connects and authorizes their own Gmail account, chooses their own categories and schedule, and receives their brief inside ChatGPT.

**No coding is required.** Most people should be able to complete the setup in about 15–30 minutes by following the steps below in order.

## What it does

- Reviews recent received email and produces a prioritized Morning Brief.
- Retrieves the full message body when a subject or preview is not enough to assess a potentially important email.
- Uses categories chosen by the user rather than a one-size-fits-all inbox taxonomy.
- Includes source-email links when available.
- Supports a recurring task after a manual test has been reviewed.

## What it does not do

- Send or draft email.
- Delete, archive, label, mark spam, or unsubscribe from email.
- Create calendar events or change Gmail account settings.
- Apply to jobs, purchase anything, or take other external actions.

## Who it is for

People who want a useful recurring brief from their own inbox without giving the setup permission to alter that inbox.

## Requirements

- A ChatGPT account where Gmail and Scheduled tasks are available.
- A Gmail account the user can connect themselves.
- A willingness to review one manual run before scheduling.

Availability can vary by account, plan, region, and workspace settings. Check before beginning.

## Start here

1. Read the [Quick Start](quick-start.md).
2. Complete the [Configuration Worksheet](configuration-worksheet.md).
3. Copy the [Reusable Setup Prompt](setup-prompt.md) into a new ChatGPT chat and replace its brackets with your choices.
4. Run it once manually and review the result.
5. Schedule it in the same chat only after the manual brief is useful.

## Suggested default categories

- Act First
- Needs Response
- Upcoming / Time-Sensitive
- FYI
- Reading / Useful

You can rename, remove, reorder, or add categories. For example: Career / Opportunities, Clients, Family, Finance, or Travel.

## Trust and control

Read [Trust & Data Handling](trust-and-data-handling.md) before connecting Gmail. Read [Stop & Disconnect](stop-and-disconnect.md) to disable a task or disconnect Gmail later.

## Repository map

- [Configuration Worksheet](configuration-worksheet.md)
- [Reusable Setup Prompt](setup-prompt.md)
- [Quick Start](quick-start.md)
- [Trust & Data Handling](trust-and-data-handling.md)
- [Stop & Disconnect](stop-and-disconnect.md)
- [Example Brief](example-brief.md)
- [Changelog](CHANGELOG.md)
