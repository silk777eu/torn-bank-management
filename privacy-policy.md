---
layout: default
title: Privacy Policy
---

# Privacy Policy

Effective date: 5 November 2026 · Last updated: 5 November 2026

Controller details must be completed before publication.

Controller / operator: [FULL LEGAL NAME / BUSINESS NAME]

Postal address: [FULL POSTAL ADDRESS]

Contact email: [CONTACT EMAIL ADDRESS]

## 1. Who is responsible?

The controller responsible for processing personal data through TBM is the operator identified above. Complete these details before making this policy available to users. This policy describes processing visible in the supplied bot source code; hosting, backups, server logs and other infrastructure may involve additional processing that must be added by the operator.

## 2. Data processed

- Discord identifiers and server data: Discord user IDs, server (guild) IDs and names, channel and role identifiers, and configuration information needed to operate the bot.

- TORN account data: TORN player ID and player name, account-link status, API-key verification timestamp and an encrypted copy of the API key.

- Virtual banking records: recorded balance, lifetime interest credited, interest-credit timestamps, transaction/request type, amount, status, timestamps, related TORN identifiers, staff/customer Discord identifiers, and notes or details associated with requests.

- Support and diagnostic data: support form content, ticket messages, user and server identifiers, channel identifiers, reported issue location, expected result, error categories and diagnostic details. If a support message contains attachments, the bot forwards the attachment URLs to the central support channel.

## 3. Purposes and operation

Data is processed to link and verify accounts, operate virtual bank records and requests, calculate and record virtual interest, administer server-specific roles and channels, provide support, diagnose errors, prevent misuse and maintain the service.
The bot sends API requests to the official TORN API. It uses the supplied API key to verify the player's profile and, in relevant banking workflows, retrieve money information. The API key is therefore transmitted to TORN for those requests. It is not intentionally included in support reports.

## 4. Support reports and disclosures within Discord

When a user submits a support report or writes in a TBM support ticket, the bot forwards the report or message to a central TBM support channel on Discord. The forwarded information can include the message text, Discord user ID, server name and ID, channel information, issue location and, where supplied, expected result and attachment URLs. Automated diagnostic/error reports may also be sent to the central support channel and, in some cases, a local error channel on the server where the issue occurred.
Do not submit API keys, passwords or other secrets in support messages. Support information is visible to authorized members who can access the relevant support channels.

## 5. Storage and security

The supplied source code stores application records in an SQLite database. TORN API keys are encrypted in the database using Fernet. The encryption key is supplied separately through the operator's server environment configuration. The security of the data therefore also depends on access controls, hosting security, backups and protection of that environment variable.
No online system can be guaranteed completely secure. The operator should restrict access to the database, encryption key, backups, bot hosting account and support channels.

## 6. Retention and unlinking

The source code does not define a fixed deletion or retention schedule for banking, transaction, support or diagnostic records. The operator must establish and publish an appropriate retention period and delete or anonymize records when they are no longer needed, unless retention is required for a legitimate purpose or by law.
Using /unlink_account removes the Discord-to-TORN link and clears the stored encrypted API key and its verification timestamp. It does not delete the TORN account record, virtual bank balance, lifetime interest information or existing transaction records. A separate privacy request may be made using the contact details above; deletion may be subject to applicable legal requirements and the need to preserve relevant transaction records.

## 7. Recipients and third-party services

- Discord: provides the platform on which commands, server roles, channels and support messages operate.

- TORN: receives API requests, including the API key, to provide the requested profile and money information.

- Central TBM support personnel: can access information forwarded to the central support channels.

- Hosting and infrastructure providers: may process data as part of hosting the bot, database, backups and logs. The operator must identify the actual provider(s), their locations and any applicable data-processing arrangements before publication.

## 8. Legal basis and data protection rights

The operator must determine and document the applicable legal basis for each processing purpose under the laws that apply, including the GDPR where applicable. Depending on the circumstances, this may involve performance of a service arrangement, legitimate interests, consent or compliance with legal obligations. Do not rely on this generic description as a substitute for the operator's actual legal assessment.
Where the GDPR applies, users may have rights to request access, rectification, erasure, restriction of processing, data portability, or to object to certain processing. Where processing is based on consent, consent may be withdrawn. Users may also lodge a complaint with a competent data protection supervisory authority.
To exercise a right or ask a privacy question, contact: [CONTACT EMAIL ADDRESS].

## 9. International transfers

Discord, TORN and the operator's hosting or infrastructure providers may process data in countries outside the user's country. The operator must verify the actual locations and applicable transfer safeguards for the services used and update this section accordingly.

## 10. Children's privacy

TBM is not specifically designed for children. Users must meet the age requirements and comply with the terms of Discord and TORN.

## 11. Changes to this policy

This policy may be updated to reflect changes to the bot, its infrastructure or applicable legal requirements. The latest version will be published at this address with a revised effective date.

## 12. Contact

Privacy contact: [FULL LEGAL NAME / BUSINESS NAME], [POSTAL ADDRESS], [CONTACT EMAIL ADDRESS].
