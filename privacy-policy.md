# Privacy Policy – TORN Bank Management (TBM)

**Effective Date:** November 5, 2026

## 1. Introduction

This Privacy Policy explains how TORN Bank Management (TBM), a Discord application, collects, processes, stores, and protects information when users interact with the bot.

By using TBM, you acknowledge the data practices described in this policy.

## 2. Information We Collect

To operate the application, TBM may collect and process the following information:

### Discord Information
- Discord User ID.
- Discord Server (Guild) ID and server name.
- Discord role and configuration information required for bot functionality.
- Information submitted through Discord commands, forms, and support tickets.

### TORN Account Information
- TORN Player ID.
- TORN Player Name.
- TORN API key, stored in encrypted form.
- API key verification timestamp.
- TORN account balance maintained by the banking system.

### Banking Information
- Virtual account balances.
- Interest earned and interest calculation timestamps.
- Deposit, withdrawal, and loan request information.
- Transaction amounts, types, statuses, timestamps, and related notes.
- Relevant staff and administrator activity records.

### Support and Technical Information
- Support requests and descriptions of reported issues.
- Discord user and server information associated with support reports.
- Technical error information required to diagnose and resolve problems.

## 3. How We Use Information

The collected information is used exclusively for operating and maintaining TBM, including:

- Verifying TORN account ownership.
- Linking Discord accounts to TORN accounts.
- Retrieving TORN player identity and cash balance information.
- Operating virtual banking accounts.
- Managing deposits, withdrawals, and loan requests.
- Calculating and recording virtual interest.
- Managing server-specific roles and permissions.
- Providing customer support and investigating technical issues.
- Preventing abuse, fraud, and unauthorized access.
- Maintaining the security and reliability of the application.

## 4. TORN API Keys and Security

Users provide a TORN API key through the bot's private account-linking interface.

API keys are:
- Stored in the bot's database in encrypted form using Fernet encryption.
- Used to verify TORN account identity and retrieve the information required by the application.
- Transmitted to the official TORN API when the application requests authorized account information.
- Not intentionally disclosed to other users or forwarded to the central support team.

A Full Access API key is not required. Users should select the minimum permissions necessary for the features they wish to use.

Users can unlink their account using `/unlink_account`. This removes the stored API key and account association. Other banking records may remain in the database.

## 5. Data Storage and Retention

Information is stored in the application's database for as long as necessary to provide the banking and support services.

When a user unlinks their TORN account:
- The stored API key is deleted.
- The Discord-to-TORN account association is removed.
- Existing banking balances and transaction records are not automatically deleted.

Certain records may be retained for operational, security, auditing, and banking record-keeping purposes.

The exact retention period depends on operational requirements and applicable legal obligations.

## 6. Support Requests

When users submit a support report through `/supporttbm`, the information may be forwarded to the central TBM Support server.

A support report may contain:
- Discord username and user ID.
- Discord server name and server ID.
- The location of the reported issue.
- The description of the problem.
- Additional information provided by the user.

Support reports are used to investigate problems and provide assistance.

Users should never include passwords, TORN API keys, or other sensitive authentication credentials in support reports.

## 7. Data Sharing and Third-Party Services

TBM relies on external services to operate:

**Discord:** Used for account interactions, commands, server management, and support functionality.

**TORN:** Used to verify TORN accounts and retrieve authorized player information through the official TORN API.

Information may be transmitted to these services when necessary to provide the requested functionality.

TORN API keys are not intentionally shared with other users or the central support team.

TBM does not sell users' personal information.

## 8. Data Security

Reasonable technical and organizational measures are used to protect stored information against unauthorized access, disclosure, alteration, or destruction.

These measures include:
- Fernet encryption for stored TORN API keys.
- Restricted access to banking and administrative functions.
- Discord permission controls for server-specific operations.
- Database access controls and application security measures.

However, no online service or storage system can guarantee absolute security.

## 9. User Rights and Data Requests

Depending on applicable data protection laws, users may have the right to:

- Request access to their personal information.
- Request correction of inaccurate information.
- Request deletion of personal information where applicable.
- Object to or request restriction of certain processing activities.
- Withdraw consent where processing is based on consent.

To make a privacy-related request, contact the TBM application operator through the official support channel using `/supporttbm`.

Unlinking an account through `/unlink_account` removes the stored API key and account association but does not automatically erase all historical banking records.

## 10. Children's Privacy

TBM is not specifically designed for children. Users must comply with the applicable age requirements and terms of service of Discord and TORN.

## 11. Changes to This Privacy Policy

This Privacy Policy may be updated from time to time to reflect changes in the application, its features, or applicable legal requirements.

The latest version will always be published in the official TBM GitHub repository.

## 12. Contact

For privacy-related questions, data requests, or concerns about the handling of information, please contact the TBM application operator through the official support channel.

**Application:** TORN Bank Management (TBM)  
**Platform:** Discord  
**Effective Date:** November 5, 2026

---

By using TORN Bank Management, you acknowledge that you have read this Privacy Policy.
