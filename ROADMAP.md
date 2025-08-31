# AnchorDad — Public Roadmap

> Status legend: 🟢 planned · 🟡 in progress · 🔵 in review · ✅ done

## Milestones (Epics)
- M0 — Foundation
- M1 — Today View MVP
- M2 — Journal & Quick Capture
- M3 — Daily Content Engine
- M4 — Nudges & Reminders
- M5 — Guided Onboarding
- M6 — Analytics + Privacy Tools
- M7 — Beta Invite System
- M8 — Minimal Community
- M9 — Routines & Templates
- M10 — Mobile Groundwork

## Schedule (Mermaid Gantt)
```mermaid
gantt
dateFormat  YYYY-MM-DD
title AnchorDad MVP Roadmap (Aug–Oct 2025)

section M0 — Foundation
Auth & DB                              :done, m0a, 2025-08-18, 3d
Settings (TZ + Windows)                :m0b, after m0a, 2d

section M1 — Today View MVP
One Big Thing (OBT)                    :m1a, 2025-08-25, 3d
Google Cal Read-only + Refresh         :m1b, after m1a, 4d
Show Next 3 Events                     :m1c, after m1b, 2d

section M2 — Journal & Quick Capture
Journal CRUD                           :m2a, 2025-09-04, 4d
Quick Capture                          :m2b, after m2a, 2d
Voice-to-Text (optional)               :m2c, after m2b, 2d

section M3 — Daily Content Engine
Stoic Quote + Dad Takeaway             :m3a, 2025-09-12, 2d
ADHD Tip of the Day                    :m3b, after m3a, 2d
Parenting Tip of the Day               :m3c, after m3b, 2d

section M4 — Nudges & Reminders
Web Push (VAPID)                       :m4a, 2025-09-18, 3d
Email Fallback (Resend/Postmark)       :m4b, after m4a, 2d
.ics Reminder Feed                     :m4c, after m4b, 2d

section M5 — Guided Onboarding
3-Step Setup Flow                      :m5a, 2025-09-25, 3d
Sample Data (empty calendars)          :m5b, after m5a, 1d

section M6 — Analytics + Privacy
Product Analytics (PostHog)            :m6a, 2025-09-30, 2d
Export/Delete My Data                  :m6b, after m6a, 2d

section M7 — Beta Invite System
Invite Code Entry                      :m7a, 2025-10-06, 2d
Admin: Invite Management               :m7b, after m7a, 2d

section M8 — Minimal Community
Weekly AMA Thread                      :m8a, 2025-10-09, 3d

section M9 — Routines & Templates
Add from Templates                     :m9a, 2025-10-14, 3d
Checklist Mode                         :m9b, after m9a, 2d

section M10 — Mobile Groundwork
Public API Layer                       :m10a, 2025-10-20, 3d
Expo Shell: Login + Today View         :m10b, after m10a, 3d
```

## Following along
- Project board: “AnchorDad — MVP Build”
- Issues are tagged by milestone and labels (today-view, calendar, journal, etc.)
