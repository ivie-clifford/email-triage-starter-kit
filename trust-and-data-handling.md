# Trust & Data Handling

## What this kit is

This repository contains instructions and prompt templates. It does not run an email service, receive your Gmail credentials, or collect your inbox content.

## What happens when you use it

You connect Gmail within your own ChatGPT account. The configured chat reads the email needed to create the brief under the permissions you approve. The brief is delivered in ChatGPT.

## Safety boundary in v0.1

The setup is read-only. It must not:

- send or draft messages;
- delete, archive, label, mark spam, or unsubscribe;
- create calendar events;
- change account settings; or
- take external actions based on an email.

## Your controls

- Review Gmail permissions before connecting.
- Test manually before creating a schedule.
- Review scheduled results and adjust the configuration when evidence warrants it.
- Disable the task or disconnect Gmail whenever you want. See [Stop & Disconnect](stop-and-disconnect.md).

## Important limitation

This is a triage aid, not a guarantee that every important email will be surfaced. Check time-sensitive, financial, health, legal, security, and application-related information directly in Gmail.
