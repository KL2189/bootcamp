# daily-prep — spec v1

WHEN: Evening run (manual for v1)

PULL FROM CALENDAR:
- Tomorrow's events
- Keep: meetings with other humans (internal included — internal is the point)
- Drop: solo focus blocks, lunch, holds, declined invites

PULL FROM FATHOM:
- For each meeting's attendees, find calls from this week + last week
- Cap ~3 transcripts; feed raw (window is small enough for one-pass synthesis)

SYNTHESIZE (per meeting):
- Mine transcripts for commitments + open loops
- Generate agenda items
- QUOTE the source line, don't paraphrase
- LINK back to the call (date / timestamp)
- If no clear loops in window: say "go in open" — never fabricate

OUTPUT:
- Title: "Here's what's ahead"
- One H2 per meeting: time + who + meeting name
- One context line under each (quoted last-time reference)
- Agenda items as checkboxes [ ] — tick live in the meeting
- Sorted chronologically

SAVE + OPEN:
- ~/prep/ folder, date-stamped filename (2026-05-21.md)
- File-exists guard (don't overwrite)
- open "$FILE" on completion

SUCCESS = I act on it without verifying it. Trust is the product.
