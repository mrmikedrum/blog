---
layout: page
title: OpenClaw Calendar Privacy Policy
permalink: /openclaw/privacy/
description: How the personal OpenClaw Calendar integration handles Google user data.
---

Effective October 13, 2026.

[OpenClaw Calendar]({{ '/openclaw/' | relative_url }}) is a personal integration operated by Mike Drum. This policy describes its handling of Google account and Calendar data.

## Information accessed and purpose

With the account holder’s authorization, the integration accesses basic account identity (such as email address), calendar names and sharing roles, and event information. Event information can include titles, descriptions, times, locations, attendees, and meeting links. Access includes calendars shared with the connected account, within their existing permissions.

This data is used to answer scheduling questions, summarize agendas, identify conflicts, and create or update events as requested. Calendar write access also permits deletion; event changes should be requested by the operator. The integration does not require Gmail or Google Drive access.

## Processing and sharing

The integration runs on the operator’s private computer and communicates with Google’s APIs. Relevant calendar information may be sent to the AI provider configured in OpenClaw to process a request. Calendar information may also appear in the assistant’s response on the channel the operator uses. Requests involving attendees or shared calendars may disclose event information through Google Calendar’s normal sharing and notification behavior.

Google user data is not sold, used for advertising, or intentionally published on this website. It is not used by the operator to train generalized AI or machine-learning models. Use and transfer of information received from Google APIs will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including its Limited Use requirements.

## Storage and retention

OAuth credentials are stored in encrypted credential storage on the operator’s computer, with access restricted to the service account. Relevant calendar content may be retained in assistant conversations, logs, caches, backups, or memory until those records are removed. Data sent to a configured AI provider is also subject to that provider’s applicable retention and processing settings. This integration does not promise a fixed automatic deletion period.

## Control and deletion

The account holder can revoke access at any time through [Google Account connections](https://myaccount.google.com/connections). Revoking access stops future authorized API access; it does not automatically delete prior conversations, local records, backups, or calendar events already created.

To request removal of locally retained integration data or ask about data handling, contact [mike@drum.zone](mailto:mike@drum.zone). Requests will be reviewed by the operator, including any applicable backup or service-provider retention limits.

## Website and changes

These public information pages are hosted on GitHub Pages, whose hosting infrastructure may process ordinary web-request information. They do not display private calendar data. Material changes to this integration’s practices will be reflected here with an updated effective date.

[Integration overview]({{ '/openclaw/' | relative_url }}) · [Terms of Use]({{ '/openclaw/terms/' | relative_url }})
