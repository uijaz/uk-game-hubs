# Contributing to UK Game Hubs

Thanks for helping map the UK's game dev scene! 🙌

---

## For Non-Technical Contributors (No coding required!)

### Submit via GitHub Issues

1. Go to the [Issues tab](https://github.com/uijaz/uk-game-hubs/issues)
2. Click **"New Issue"**
3. Choose either:
   - **"Add a New Hub"** – fill out the form with your hub details
   - **"Suggest an Update"** – tell us what changed
4. Submit the issue

We'll review it and add your contribution!

---

## For Technical Contributors (JSON + Git)

If you're comfortable with JSON and Git, you can submit a Pull Request directly.

### 1. Edit `data/hubs.json`

Each hub follows this format:

```json
{
  "id": "hub-name",
  "name": "Display Name",
  "description": "Brief overview of the hub",
  "studios": ["Studio 1", "Studio 2"],
  "events": ["Event 1", "Event 2"],
  "links": {
    "website": "https://...",
    "discord": "https://...",
    "linkedin": null,
    "youtube": null,
    "bluesky": null,
    "eventbrite": null,
    "meetup": null,
    "luma": null,
    "facebook": null,
    "instagram": null,
    "tiktok": null,
    "x": null
  }
}
```

### 2. Hub Structure

Each hub sits inside a **Region → City** hierarchy:

```
regions
  └── East of England
        └── cities
              └── Peterborough
                    └── hubs
                          └── People in Games | PinG
```

### 3. Available Link Types

| Key | Display |
|-----|---------|
| `website` | 🌐 Website |
| `discord` | 💬 Discord |
| `linkedin` | 🔗 LinkedIn |
| `youtube` | 📺 YouTube |
| `bluesky` | 🦋 Bluesky |
| `eventbrite` | 🎟️ Eventbrite |
| `meetup` | 📅 Meetup |
| `luma` | ✨ Luma |
| `facebook` | 📘 Facebook |
| `instagram` | 📸 Instagram |
| `tiktok` | 🎵 TikTok |
| `x` | 🐦 X |

**Note:** If a link doesn't exist, use `null` instead of removing the key.

### 4. Regions

- Greater London
- South East
- South West
- East of England
- West Midlands
- East Midlands
- North West
- North East
- Yorkshire & Humber
- Scotland
- Wales
- Northern Ireland

---

## Submit Your Changes

1. Fork the repo
2. Make your changes to `data/hubs.json`
3. Submit a Pull Request to the `main` branch

---

**Every contribution helps make this better!** 🎮