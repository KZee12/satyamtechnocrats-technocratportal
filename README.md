# Satyam Technocrats — Technocrat Portal
**...innovative dimension in automation**

Central hub for all internal tools, forms, and resources. One link — everything in one place.

---

## Live URL
`https://kzee12.github.io/satyamtechnocrats-technocratportal`

Pin this in the internal WhatsApp group. Will migrate to `satyamtechnocrats.com` under the Technocrat Login section once the main website is deployed.

---

## Repo Structure

```
/
├── index.html                    → Portal homepage (the hub)
├── README.md                     → This file
│
├── escalation-form/
│   └── index.html                → Pre-Escalation Checklist (Live)
│
├── progression-log/
│   └── index.html                → Progression Log (Coming Soon)
│
└── correspondence-log/
    └── index.html                → Correspondence Log (Coming Soon)
```

---

## Tools

### Forms

| Tool | Status | Description |
|------|--------|-------------|
| Pre-Escalation Checklist | ✅ Live | Mandatory form before escalating any problem to a senior |
| Progression Log | 🔜 Coming Soon | Log project progress milestones and activity updates |
| Correspondence Log | 🔜 Coming Soon | Record all external correspondences with clients, vendors, partners |

### CRM

| Tool | Status | Description |
|------|--------|-------------|
| Sales CRM | ✅ Live | Master leads database — cloud Excel file (to be migrated to HubSpot / AnyDB) |

---

## How to add a new tool

1. Create a new folder: `tool-name/`
2. Place the tool's HTML file inside as `index.html`
3. Add a card for it in the root `index.html` under the appropriate section — change `soon` class to active and update the `href`
4. Update this README

---

## Hosting

Currently on GitHub Pages at `kzee12.github.io/satyamtechnocrats-technocratportal`.
Migration to `satyamtechnocrats.com` planned once the main website is live — tools will be accessible via the Technocrat Login section.

---

*Satyam Technocrats*
