# Evaluation Summary & Winning Persona(s)

## Scoring (v2, after fixes), 1-5 per dimension

| Dimension | A — Live Wire | B — Dry Correspondent | C — Curious Peer |
|---|---|---|---|
| Hook quality (day 1-5 avg) | 4 | 4 | 4.5 |
| Register consistency over 10 days | 4 (was 3 pre-fix) | 5 | 4 (was 2.5 pre-fix) |
| Culture/geography neutrality | 5 | 5 | 5 |
| Graceful non-engagement (days 2/4/8) | 4 | 5 | 4 (was 2 pre-fix) |
| Personalization elegance (days 6-10) | 4 | 4.5 | 5 |
| Portfolio-rule legibility (day 10) | 4 | 3.5 (understates the lane-switch) | 4.5 |
| Risk of long-run fatigue (30-60 day projection) | Medium (enthusiasm ceiling) | Low | Medium (still needs the question-gate to hold under real variety of facts) |
| **Overall (avg)** | **4.14** | **4.43** | **4.43** |

Both B and C tie numerically. They fail differently, though, which matters
more than the average:

- **B (Dry Correspondent)** is the safer, lower-variance choice. It never
  has a bad day — flat delivery works whether Maya engages or not, and it
  ages well because restraint doesn't get tiring the way enthusiasm does.
  Its ceiling is slightly lower: nothing in the simulation shows B pulling
  out the kind of unprompted, elaborated reaction Persona C got on days 5,
  7, and 9 ("tragedy of the commons", "didn't realize how much I like this
  language stuff", "how does that even work").
- **C (Curious Peer)** has the highest engagement ceiling by a clear
  margin once the question-gate fix is in — but it is the persona most
  dependent on getting that gate right. Get the "is this genuinely
  ambiguous" judgment wrong even occasionally and it reverts to the v1
  failure mode (forced questions, conspicuous non-answers). It is a
  **higher-skill-required, higher-reward** persona.
- **A (Live Wire)** is solid but strictly dominated by B on every
  dimension except raw hook energy — the enthusiasm is doing work that
  B's dry wit does more efficiently and with less long-run fatigue risk.

## Recommendation

**Primary: Persona B (Dry Correspondent).** Best risk-adjusted choice for
a default/only persona — it has no bad days in the simulation, ages best,
and the "flat statement + one earned observation" structure is the
easiest to keep fresh over months without a large content-authoring
burden.

**If shipping more than one voice: add Persona C (Curious Peer) as a
second option**, gated hard behind the question-ambiguity rule from v2 —
it's worth the extra complexity because its ceiling (days 5/7/9 above) is
the best evidence in this whole experiment that the "explore, confirm,
deepen" mechanic actually produces a *conversation* rather than a feed of
one-way facts. That is arguably the more interesting long-term product
bet, even though it's the riskier one operationally.

**Persona A (Live Wire)** — not recommended as-is. Keep the opener-rotation
fix as a reusable technique (any persona benefits from varied openers),
but the voice itself doesn't add anything B doesn't do more reliably.

## What the simulation validated about the underlying design (not just voice)

Independent of which persona wins, days 6-10 confirm the mechanics
discussed earlier in this thread actually work in practice:
- The 2-signal confirm/reject rule correctly separated a real interest
  (Linguistics, Space) from noise (History, Economics) without
  overreacting to a single data point.
- Deepening a Confirmed thread (days 6, 9) via a genuinely new sub-angle
  read as continuity, not repetition.
- The callback mechanism (day 9, "remember the X thing") delivered
  personalization while staying entirely non-personal/non-emotional —
  this was the actual hard constraint from earlier in the conversation,
  and all three personas held it.
- The portfolio rule (day 10) reads best when it's made explicit in the
  text itself ("switching lanes entirely") rather than left implicit —
  worth carrying forward as a stated technique, not just a backend rule.

## Open question for you when you're back

Ship one persona or two (B alone, or B as default + C as an opt-in/rotated
alternate)? That's a product call, not something the simulation resolves
on its own.
