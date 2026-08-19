# fog-bingham-2026-calendar

A public, subscribable iCalendar (.ics) file covering the San Francisco Fog RFC team itinerary for the **2026 Bingham Cup in Brisbane** — trainings, all Fog fixtures, ceremonies, dinners and socials.

## How to subscribe

Copy the GitHub Pages URL and paste it into your calendar app (Google Calendar, Apple Calendar, or Outlook) under **"Subscribe from URL"**.

[Public calendar file](https://fogrugby.github.io/fog-bingham-2026-calendar/calendar-fog-bingham-2026.ics)

> **Subscribe, don't import.** Subscribing keeps your calendar in sync as fixtures change. Importing takes a one-off snapshot that will go stale.

## What's inside

| | |
|---|---|
| **Events** | 28 |
| **Dates** | Mon 17 – Mon 24 August 2026 |
| **Timezone** | `Australia/Brisbane` (AEST, UTC+10, no DST) |
| **Refresh hint** | 1 hour (`REFRESH-INTERVAL` / `X-PUBLISHED-TTL`) |

Included:

- Both mandatory SF Fog training sessions, plus the optional Rugby Australia clinic
- **All nine Fog fixtures** — side, opponent, pool, ground and field number
- IGR AGM and the Captains & Team Managers meeting
- Opening and Closing ceremonies, with attire and theme
- Club Welcome Dinner, SF Fog Club Dinner, side dinners, Amanda Mark Cup social, Official Tournament Party
- Match Day Three knockouts and Sunday finals as day-long blocks

**Every match carries a 75-minute alarm** — that is the club's "report to your coach 1 hour 15 minutes before kickoff" rule, automated.

## Source of truth

Built from the *SF Fog | 2026 Fog Team Itinerary – Brisbane* (updated 17 August 2026).

Grounds and kickoff times can change day to day. **Rugby Xplorer is the official tournament app and the final word on match day** — this calendar is a convenience, not an authority.

Field locations and transport: <https://binghamcup2026.com/match-fields>

## Updating

Edit `calendar-fog-bingham-2026.ics` and commit to `main`. Subscribed clients pick the change up on their next poll — Google Calendar is typically slower than the one-hour hint, often up to 24 hours, so post anything urgent in WhatsApp as well.

Bump `SEQUENCE` on any `VEVENT` you materially change so clients treat it as an update rather than a duplicate.

## Licence

Same as the club's other public calendars. Free to share, fork and reuse.
