# Contributing to UK Game Dev Hubs

Thanks for helping map the UK's game dev scene! 🙌

## How to Add or Update a Hub

### 1. Edit `data/hubs.json`

Each hub follows this format:

```json
{
  "id": "city-name",
  "name": "Display Name",
  "region": "Region Name",
  "type": "Major Hub",
  "description": "Brief overview of the scene",
  "studios": ["Studio 1", "Studio 2"],
  "events": ["Event Name (Month)", "Another Event (Monthly)"],
  "links": {
    "website": "https://...",
    "discord": "https://...",
    "twitter": "https://..."
  }
}