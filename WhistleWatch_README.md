# WhistleWatch — User Guide
**Basketball Officiating Call Charting Tool** | TBarz16

---

## Overview

WhistleWatch is a browser-based film breakdown tool for charting and evaluating officiating decisions in NCAAW basketball. Open the HTML file in any modern browser — no installation, no login, no internet required. All data lives in your session until you export or close the tab.

---

## Setup

Before logging calls, fill in the game header fields at the top of the page:

- **Date** — auto-fills to today, adjust as needed
- **Home Team / Away Team** — these names flow through to the log and sidebar automatically
- **Crew Chief, Ref 2, Ref 3** — entering names here populates the "Called By" dropdown and labels the per-ref stats in the sidebar

---

## Logging a Call

Use the **Log a Call** form to enter each play. Fill in as many fields as are relevant, then hit **+ Log**.

| Field | What to enter |
|---|---|
| **Qtr** | Q1–Q4 or OT1/OT2 |
| **Game Clock** | Time remaining, e.g. `4:22` |
| **Call Type** | See call type reference below |
| **On Team** | Which team the call was assessed against |
| **Called By** | Which official made the call (or left blank if unclear) |
| **Position** | Where the official was on the floor — Lead, Center, or Trail |
| **Coverage** | Whether the play occurred in their Primary or Secondary coverage area |
| **Verdict** | Your evaluation of the call (see Verdict System below) |
| **Notes** | Player name, context, situation — anything useful for review |

Clock and Notes fields clear automatically after each entry. All other selections hold their last value so you can log quickly without resetting every field.

To remove a logged entry, click the **✕** button on the right side of any row.

---

## Call Type Reference

**Personal Fouls**
- Shooting Foul
- Player Control
- Ball Handler
- Illegal Screen
- Freedom of Movement
- Post Play (Defense)
- Rebounding

**Technical / Flagrant**
- Technical Foul
- Flagrant 1
- Flagrant 2

**Violations**
- Traveling, Double Dribble, Carry / Palming
- Out of Bounds, Backcourt
- Lane Violation, Goaltending / Interference
- 3-Second, 5-Second, 10-Second
- Shot Clock Violation
- Kicking Violation

**Stoppages / Other**
- Held Ball, Team Timeout, Media Timeout
- Replay Review, Clock / Timing
- Other

---

## Verdict System

The Verdict field captures your assessment of each play. Four options:

| Code | Meaning |
|---|---|
| **CC** | Call Correct — a call was made and it was the right one |
| **NCC** | No Call Correct — nothing was called and that was correct |
| **CI** | Call Incorrect — a call was made but shouldn't have been |
| **NCI** | No Call Incorrect — something should have been called but wasn't |

Verdicts display inline in the log and tally live in the **Verdict Tracker** in the sidebar.

---

## Sidebar Stats

The sidebar updates in real time as calls are logged:

- **Team Fouls** — running foul totals per team; turns yellow at 3, red at 5+
- **Calls by Quarter** — breakdown by call category across Q1–Q4; hottest quarter highlighted in orange
- **Calls per Ref** — how many calls each official made
- **Calls by Position** — distribution across Lead, Center, and Trail
- **Calls by Coverage Area** — Primary vs. Secondary breakdown
- **Verdict Tracker** — live counts of CC, NCC, CI, and NCI

---

## Exporting & Printing

At the bottom of the sidebar:

- **Export CSV** — downloads a spreadsheet with every logged call and all field values, suitable for further analysis in Excel or Google Sheets
- **Print Sheet** — opens a print view with the sidebar and entry form hidden, showing only the call log
- **Clear Session** — wipes all logged calls and resets counters (prompts for confirmation first)

---

## Notes

- WhistleWatch runs entirely in the browser. Data is **not saved** if the tab is closed or refreshed without exporting first. Export your CSV before closing.
- The file can be saved locally and reused for any game — just clear the session and update the header fields.
