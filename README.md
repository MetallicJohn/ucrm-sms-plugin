# UCRM SMS Plugin

UCRM/UISP plugins for sending SMS notifications to clients.

## Versions

| Version | Folder | Description |
|---------|--------|-------------|
| **v1** | `v1-africas-talking/` | Africa's Talking only |
| **v2** | `v2-multi-provider/` | Multi-provider: Africa's Talking, UjumbeSMS, BlessedText, Talksasa, WebFamSMS |

## Quick start

1. Download the version you need (or clone this repo).
2. Zip the contents of the `src/` folder.
3. In UCRM/UISP: **System → Plugins → Upload**.
4. Enable the plugin and fill in credentials.
5. Enable webhooks for the events you want.

## v2 Features
- Provider dropdown
- Correct WebFamSMS API
- Send Test SMS menu page with button
- Kenyan number normalization
