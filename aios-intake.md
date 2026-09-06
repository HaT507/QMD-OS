# AIS-OS Intake

This is the source-of-truth file for your AIOS. Fill it in by typing, voice-pasting (Wispr Flow / OS dictation), or running `/onboard` for a guided conversation. Whichever mode, this file is what `/onboard` reads to scaffold your Day-1 setup.

**Hard cap: 7 questions.** Each answerable in under 60 seconds. Don't overthink — you can edit and re-run `/onboard` any time.

---

## Q1 — Who are you, what do you sell, who do you sell it to?

Identity, offer, ICP. One paragraph each is fine.

```
IDENTIDAD:
[Your answer here]

OFERTA:
[Your answer here]

ICP:
[Your answer here]
```

---

## Q2 — Paste 1-2 things you've written recently. Don't edit them.

An email, a LinkedIn post, a DM, a doc — anything that sounds like you when you're not trying. **Paste verbatim.** Do not type these mid-conversation with Claude — chat-shaped samples are worse than no samples (voice contamination).

```
[Paste sample 1 here — email, post, or DM. Raw and unedited.]
```

```
[Paste sample 2 here]
```

---

## Q3 — What are your 2-3 biggest priorities for the next 90 days?

Quarterly priorities. Not yearly aspirations. Things that, if not done by [end of quarter], would make you say "I wasted this quarter."

```
[Your answer here — list 2-3 concrete outcomes]
```

---

## Q4 — Where does revenue actually land, and where is it tracked?

Multiple answers OK. Stripe? PayPal? Bank transfer? A spreadsheet? Your accounting tool?

```
DONDE CAE EL DINERO:
[Your answer here]

DONDE SE REGISTRA:
[Your answer here]
```

---

## Q5 — Where do you talk to customers, your team, and the outside world day-to-day?

Email (which one — Gmail / Outlook)? Slack? Teams? DMs? WhatsApp? Phone?

```
[Your answer here]
```

---

## Q6 — Where do meeting recordings, notes, and important docs live?

Granola? Otter? Fireflies? Google Drive? Notion? Dropbox?

```
[Your answer here]
```

---

## Q7 — What's the one task that eats your week, and where do you currently track work?

The single biggest time-suck or recurring drudgery. Plus where tasks/projects live (ClickUp / Asana / Linear / Notion / a notebook).

```
TOP PAIN:
[Your answer here]

DONDE RASTREAS EL TRABAJO:
[Your answer here]
```

---

When this file is filled, run `/onboard` (or re-run it) and the wizard will scaffold your Day-1 file set: `context/`, `references/voice.md`, populated `connections.md`, and a filled `CLAUDE.md`.
