# Product Assets

Public asset hub for app websites, privacy policies, support pages, App Store metadata, screenshots, legal notes, and shared marketing resources.

This repository is intended to be safe for public hosting. Do not commit private credentials, unpublished account details, private customer data, or source files that should not be public.

## Apps

### USA Soccer Celebration Pack

Sticker pack app for iMessage.

- Subtitle: `USA Soccer Fan Stickers`
- App type: iMessage sticker pack
- Live website: [https://singh-karanpal.github.io/product-assets/index.html](https://singh-karanpal.github.io/product-assets/index.html)
- App Store Privacy Policy URL: [https://singh-karanpal.github.io/product-assets/privacy.html](https://singh-karanpal.github.io/product-assets/privacy.html)
- App Store Support URL: [https://singh-karanpal.github.io/product-assets/support.html](https://singh-karanpal.github.io/product-assets/support.html)
- Website source: [apps/usa-soccer-celebrations/websites](apps/usa-soccer-celebrations/websites)
- Privacy statement source: [apps/usa-soccer-celebrations/websites/privacy.html](apps/usa-soccer-celebrations/websites/privacy.html)
- Support page source: [apps/usa-soccer-celebrations/websites/support.html](apps/usa-soccer-celebrations/websites/support.html)
- App details: [apps/usa-soccer-celebrations/README.md](apps/usa-soccer-celebrations/README.md)
- App icon placeholder: [apps/usa-soccer-celebrations/assets/app-icon-placeholder.png](apps/usa-soccer-celebrations/assets/app-icon-placeholder.png)
- Screenshots: [apps/usa-soccer-celebrations/screenshots](apps/usa-soccer-celebrations/screenshots)

Suggested App Store keywords:

```text
soccer,usa,stickers,imessage,fan,goal,celebration,sports,america,futbol,match,chat,world
```

## Repository Structure

```text
product-assets/
├── apps/
│   ├── README.md
│   └── usa-soccer-celebrations/
│       ├── CHANGELOG.md
│       ├── README.md
│       ├── privacy.html
│       ├── support.html
│       ├── assets/
│       │   ├── README.md
│       │   └── app-icon-placeholder.png
│       ├── legal/
│       │   └── README.md
│       ├── screenshots/
│       │   ├── README.md
│       │   ├── imessage-conversation-01-goal-reaction.png
│       │   ├── imessage-conversation-02-match-day.png
│       │   ├── imessage-conversation-03-celebration.png
│       │   ├── imessage-conversation-04-fan-chat.png
│       │   ├── imessage-conversation-05-watch-party.png
│       │   └── imessage-conversation-06-victory.png
│       └── websites/
│           ├── index.html
│           ├── privacy.html
│           ├── support.html
│           └── styles.css
└── .github/
    └── workflows/
        └── deploy-usa-soccer-celebrations.yml
```

## GitHub Pages

The website for USA Soccer Celebration Pack is deployed from `apps/usa-soccer-celebrations/websites` through the GitHub Actions workflow in `.github/workflows/deploy-usa-soccer-celebrations.yml`.

Live pages:

- Website: [https://singh-karanpal.github.io/product-assets/index.html](https://singh-karanpal.github.io/product-assets/index.html)
- App Store Support URL: [https://singh-karanpal.github.io/product-assets/support.html](https://singh-karanpal.github.io/product-assets/support.html)
- App Store Privacy Policy URL: [https://singh-karanpal.github.io/product-assets/privacy.html](https://singh-karanpal.github.io/product-assets/privacy.html)

Use the support and privacy URLs above in App Store Connect.

## Copyright

Copyright © 2026 Karanpal Singh. All rights reserved.
