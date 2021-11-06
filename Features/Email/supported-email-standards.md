## Supported Email Standards
We're happy to support the most up-to-date standards for email security, fetching, and especially privacy. We require SSL be enabled on user's IMAP4/POP3/SMTP servers when sending or receiving email.

unicorn supports the following:
- mailboxes hosted on Exchange Server 2013, 2016, 2019
  - Microsoft 365/Exchange Online not currently supported.
  - Exchange Server 2010 has reached end-of-life and is no longer supported by Microsoft.
  - For security reasons, we recommend upgrading to Exchange Server 2016 or later to continue checking your email using unicorn.
    - We will continue to support Exchange Server 2013 until at least February 1, 2022, at which point, we will remove support for it from unicorn releases in all rings.
- IMAP4 w/ SSL (recommended)
- POP3 w/ SSL (not recommended)
- SMTP w/ SSL

*in unicorn 1.6.5, we began recommending IMAP4 (with SSL) connections to fetch mail from email servers. We may enforce the use of IMAP4 in future versions of unicorn, including the final public release of toffeeOS 1.
