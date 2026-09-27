# Fictional Test User: Maya Chen

Used to simulate 10 days of dispatches per persona (days 1-5 non-personal,
days 6-10 personalized) and to test the Operator's topic-selection state
model (Untested → Tentative → Confirmed / Rejected → Dormant).

- 32, senior product manager at a fintech startup, Austin.
- No stated interests up front — the whole point is that the Operator has
  to discover what lands from behavior, not from a profile she fills in.
- Simulated reactions are authored deliberately (see day-by-day plan below)
  so the resulting Confirmed/Rejected state is unambiguous and the
  personalization days have real signal to draw on.

## Planned signal pattern across days 1-5 (non-personal)

| Day | Domain | Engagement | Resulting state after day 5 |
|---|---|---|---|
| 1 | Space (a book's weird origin story) | **Engaged** (asks follow-up) | 1st positive signal |
| 2 | Alt-data economics | **Not engaged** (one-word reply) | 1st negative signal |
| 3 | Linguistics (direction-based language) | **Engaged** (asks a question) | 1st positive signal |
| 4 | History (etymology of "quarantine") | **Not engaged** (no reply) | 1st negative signal |
| 5 | Space (different angle, sub-topic) | **Engaged, strongly** (multi-message reply) | 2nd positive signal, spaced → **Confirmed** |

Result entering day 6: **Space = Confirmed** (2 spaced positive signals).
**Linguistics = Tentative** (1 positive signal, needs a 2nd before
confirming). **Economics = 1 negative signal** (not yet Rejected — the
rule requires 2). **History = 1 negative signal** (same).

## Days 6-10 (personalized) — designed to exercise every state transition

| Day | Move | Purpose |
|---|---|---|
| 6 | Deepen Space (sub-angle: orbital debris law) | Test "mining a Confirmed vein" without repeating the domain verbatim |
| 7 | Retry Linguistics, different angle | Test promotion Tentative → Confirmed on 2nd positive signal |
| 8 | Retry History, different angle, after a cooldown gap | Test demotion to Rejected on 2nd negative signal |
| 9 | Deepen Space again + explicit callback to day 1 | Test "remembering" without becoming personal/emotional |
| 10 | Untested new domain, personalized framing | Test the portfolio rule: don't let Confirmed topics crowd out new exploration |
