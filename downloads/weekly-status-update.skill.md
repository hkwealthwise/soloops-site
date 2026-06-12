<!-- Free sample from the SoloOps Kit — https://hkwealthwise.github.io/soloops-site/ · The full kit is 9 skills, $29. This file is yours to use; please don't redistribute the paid kit. -->

---
name: weekly-status-update
description: Transform raw, messy week notes into the short status email clients actually read. Use when the user wants to send a project update, status report, or check-in to a client.
---

# Weekly Status Update

The cheapest client-retention tool that exists: a 90-second status email,
every week, same format, no surprises. You turn the freelancer's brain-dump
into that email.

## Inputs you need

1. **Raw notes** — whatever happened this week, in any format
2. **Client + project name**, and week/date
3. **Tone** — warm / neutral / formal
4. **Anything sensitive to handle carefully** (a slip, a blocker caused by
   the client) — ask only if the notes hint at it

If the notes are thin, ask up to 3 sharp questions (shipped? stuck? need
anything from them?) — then write.

## Process

1. **Sort every note** into: Done / In progress / Blocked or waiting /
   Next week. Discard internal noise the client doesn't need.
2. **Translate to client language.** "Refactored the cart state handling" →
   "Fixed the checkout bug that dropped items on mobile." Outcomes, not
   activities.
3. **Handle bad news straight:** state it, give the impact in days, give the
   recovery plan. One sentence each, no burying.
4. **Make the ask unmissable.** If the client owes anything, it goes in its
   own section with a date — this is the highest-value line in the email.
5. Keep the whole email under 150 words. Self-check, present.

## Template

```
Subject: [Project] — week of [date]: [3-word headline, e.g. "checkout flow live"]

Hi [name],

**Done this week**
- [outcome 1]
- [outcome 2]

**In progress**
- [item] — on track for [date]

**Needs your attention** ← only if true
- [what you need] by [date], so that [consequence stays on track]

**Heads-up** ← only if true
- [risk/slip]: [impact]. [recovery plan].

**Next week:** [one line]

[Sign-off],
[Name]
```

Rules: sections with nothing to say are deleted, not filled. Never write
"just checking in." Never pad good weeks; never soften bad ones into mush.

## Quality gate

- [ ] Under 150 words, scannable in 30 seconds
- [ ] Every line is an outcome or a dated ask — zero activity-jargon
- [ ] Client asks have dates and consequences
- [ ] Bad news (if any) includes impact + plan in the same breath
- [ ] Subject line carries the headline, not just "Update"

## Example invocation

> "Notes: finished homepage + menu pages, lighthouse 96, ordering api half
> done, blocked 2 days waiting on her Wix login, she still hasn't sent food
> photos which I need before Thursday or the gallery slips a week. Tone warm.
> Write Sarah's update."

→ Produces a 6-line email where "Wix login + photos by Thursday" is impossible
to miss, and the 2-day slip is stated with its recovery plan.
