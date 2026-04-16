# smokingtigers.enterprises — Web Presence

Live at: https://smokingtigers.enterprises

## Pages

| Page | URL | Description |
|------|-----|-------------|
| Landing | `/` | Main landing page |
| Schedule | `/schedule` | Cal.com booking page (embedded) |
| ST:AI Advisory | `/stai` | ST:AI consultancy landing page (Christine Francis) |

## Stack

- Static HTML/CSS — no framework
- Hosted: Caddy (local) → Cloudflare Tunnel → smokingtigers.enterprises
- Scheduling: Cal.com self-hosted at cal.smokingtigers.enterprises

## Deployment

Changes to `public/` are served live immediately via Caddy.
To deploy to Firebase backup: `firebase deploy --only hosting`

## Related
- Linear: https://linear.app/smoking-tigers/issue/STE-25
- Notion: https://www.notion.so/quorum1/Smoking-Tigers-Landing-Page-2f86f6ac689e80859959f3b906dd20b0
