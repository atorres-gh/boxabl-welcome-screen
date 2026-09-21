# BOXABL Welcome Screen

Factory lobby TV + ops console. Live: https://boxablwelcomescreen.grok.me/

Grok App Builder project id: `01a044b3-f676-7e01-9b36-f51cdb12d5c3`

## What this repo is

Reconstructed **iterable source** from the published grok.me app (no source maps shipped). Matches:

- Palette navy `#184273`, orange `#FFA400`, ink `#0B1D36`
- Guest list with VIP toggle, reorder, hold-yesterday
- Lobby preview (single column vs split when >15 and no VIP)
- Skykit display name `F1 - Office: Guestlist`
- Publish writes `/skykit.png` in production
- Calendly + Frontdesk sync (Outlook `@boxabl.com`)
- Persist key `boxabl-welcome-ops-v9`

`public/index.html` is a standalone ops+preview you can open or drop into Grok Build.

## Sister apps

- Tools hub: https://github.com/atorres-gh/boxabl-fabulous-tools-hub
- Tour intake: https://github.com/atorres-gh/boxabl-tour-intake-form

## Iterate from a company Grok account

Clone, then in Grok Build:

> Continue BOXABL Welcome Screen from this repo. Keep the lobby TV, VIP layout rules, Skykit publish, and Calendly/Frontdesk import. Palette navy #184273 orange #FFA400. House-A mark. No emoji, no purple.

Then publish from that chat (Vercel / grok.me).
