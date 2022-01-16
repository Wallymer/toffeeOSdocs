---
title: Supported Email Standards
---

## Supported Email Standards
We're happy to support the most up-to-date standards for email security, fetching, and especially privacy. We require SSL be enabled on user's IMAP4/POP3/SMTP servers when sending or receiving email.

unicorn supports the following:
- mailboxes hosted on Hosted Exchange/Microsoft 365 for Business (as of unicorn 1.6.4)
- mailboxes hosted on Exchange Server 2013, 2016, 2019
  - Exchange Server 2010 has reached end-of-life and is no longer supported by Microsoft.
  - Support for Exchange Server 2013 will now be removed in November 2022.
  - For security reasons, we recommend upgrading to Exchange Server 2016 or later to continue checking your email using unicorn.
- IMAP4 w/ SSL (recommended)
- POP3 w/ SSL (not recommended)
- SMTP w/ SSL

*in unicorn 1.6.4, we began recommending IMAP4 (with SSL) connections to fetch mail from email servers. We may enforce the use of IMAP4 in future versions of unicorn, including the final public release of toffeeOS 1.
