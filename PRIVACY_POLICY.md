# Chitti Privacy Policy

**Effective date: November 9, 2026**

This Privacy Policy explains how Chitti ("the Bot") handles information when it is used in Discord servers. Chitti is maintained by **MR KRISHNA** ("we", "us", or "the maintainer").

This document describes the Bot's general data practices. Server owners decide which features to enable and are responsible for informing their members about server-specific logging and configuration. This policy is not legal advice.

## Information the Bot processes

Depending on which features a server enables and which commands people use, Chitti may process:

- Discord account, server, channel, role, and message identifiers, names, and mentions.
- Server configuration, such as command prefixes, log destinations, welcome settings, tickets, roles, and feature preferences.
- Command input and the information needed to carry out a command.
- Moderation and audit information, including the target, moderator when available, reason, and action time.
- Message content and attachment links when needed for message commands, moderation, or configured message logs. Deleted-message logs may include a transcript and attachment URLs.
- Membership, invite, and voice-state events. Voice logging can include channel joins, leaves, moves, server mute/deafen, self mute/deafen, camera, streaming, and stage status. **The Bot does not record or store voice audio.**
- Information users choose to submit in tickets, forms, games, or other Bot features.

The Bot only receives Discord events and data made available through its configured Discord permissions and intents. Some features will not work if the necessary permissions or intents are unavailable.

## How information is used

Information is used to operate requested commands and features, save server settings, provide moderation and safety tools, maintain invite or feature state, generate configured logs, troubleshoot failures, and protect the Bot and its users from abuse.

Chitti does not sell personal information. The maintainer does not use message content collected by the Bot to train a proprietary machine-learning model. If a server uses an AI feature, the relevant prompt and message context may be sent to the external AI provider configured for that Bot deployment so it can produce a response. That provider's own terms and privacy policy apply to its processing.

## Storage and service providers

Bot data may be stored in MongoDB when configured and available. If MongoDB cannot be reached, this deployment can fall back to persistent JSON files on the machine running the Bot. The server operator controls that deployment and its database credentials, backups, access, and retention.

Chitti also relies on Discord to provide the Bot and deliver messages, and may use external providers configured by the operator. For example, music requests may be processed by a configured Lavalink server and audio source providers; AI requests may be processed by a configured AI API provider. Data sent to those providers is subject to their own policies. The Bot does not control their systems or retention practices.

## Sharing and disclosure

Information is shared only as needed to provide the feature being used:

- With Discord, as part of normal Bot operation and delivery of logs or responses.
- With the database host selected by the operator.
- With an AI or music provider when the corresponding feature is used and configured.
- With server members who can see a configured log channel, ticket, or command response.
- When required to comply with law, enforce applicable terms, or protect users, the service, or the public.

Server administrators control who can access their server's channels, logs, backups, and Bot configuration.

## Retention and deletion

Information is kept while it is needed to operate the Bot features, preserve server configuration, maintain logs or backups, or address operational and safety issues. Retention varies by feature and by the server operator's database and backup practices; this deployment does not promise a universal deletion period.

Server administrators can remove or change feature settings and log destinations. They may also delete relevant Bot data using available Bot tools or by managing the database and local data files for their deployment. To request help with data held by this deployment, contact the maintainer using the contact details below and include the relevant Discord user ID, server ID, and data request. Do not send passwords, tokens, or other secrets. Requests may be limited by technical needs, other users' rights, backups, or applicable law.

## Security

The maintainer uses reasonable measures appropriate to the deployment, but no online service or storage system can be guaranteed completely secure. Operators should protect Bot tokens, database credentials, webhook URLs, and local data and backup files, and grant the Bot only the permissions it needs.

## Children

Chitti is not designed to knowingly collect information directly from children outside the rules and age requirements of Discord and applicable law. Discord account holders must comply with Discord's minimum age requirements.

## Changes to this policy

This policy may be updated as the Bot's features or data practices change. The latest version will be published in this repository with a revised effective date. Continued use after an update means the updated policy applies to future use, subject to applicable law.

## Contact

For privacy questions or requests, contact the maintainer, **MR KRISHNA**, through [Discord](https://discord.com/users/848781953284571137). If the Bot is operated by someone other than the repository maintainer, contact that operator about data held by their deployment.
