# AIS-OS Intake

This is the source-of-truth file for your AIOS. Fill it in by typing, voice-pasting (Wispr Flow / OS dictation), or running `/onboard` for a guided conversation. Whichever mode, this file is what `/onboard` reads to scaffold your Day-1 setup.

**Hard cap: 7 questions.** Each answerable in under 60 seconds. Don't overthink — you can edit and re-run `/onboard` any time.

---

## Q1 — Who are you, what do you sell, who do you sell it to?

Identity, offer, ICP. One paragraph each is fine.

```
[Julian Rosenthal]
My name is Julian Rosenthal. I am a Senior Staff SRE at ServiceNow.
We are trying to switch our working environment to be service based, so it's easier to share the load ofthe tickets
with other folks on shift. Si, I don't really sell anything other than trying to convince you to back a technological decision that will make our lives esier

---

## Q2 — Paste 1-2 things you've written recently. Don't edit them.

An email, a LinkedIn post, a DM, a doc — anything that sounds like you when you're not trying. **Paste verbatim.** Do not type these mid-conversation with Claude — chat-shaped samples are worse than no samples (voice contamination).

```
[Sample 1 — paste raw]
```

```
[Sample 2 — paste raw]

```

---

## Q3 — What are your 2-3 biggest priorities for the next 90 days?

Quarterly priorities. Not yearly aspirations. Things that, if not done by July, would make you say "I wasted Q2."

```
1. Handover automation
2. Get RipCord into Regulated Markets
3. Reduce noise!
```

---

## Q4 — Where does revenue actually land, and where is it tracked?

Multiple answers OK. Stripe? Skool? GoHighLevel? QuickBooks? A spreadsheet?

```
[I only influence how many automations we can deploy - I want to automate reliably and reliably repeatable.
Once that is in place revenue improves instantly.
```

---

## Q5 — Where do you talk to customers, your team, and the outside world day-to-day?

Email (which one — Gmail / Outlook)? Slack? Teams? DMs (Skool / Discord / iMessage)? Phone?

```
I don't talk to outside customers at all.
My customers are all internal teams that I relie on or that relie on me.
I talk to my team and higher ups via e-mail and Teams.
```

---

## Q6 — Where do meeting recordings, notes, and important docs live?

Granola? Otter? Fireflies? Google Drive? Notion? Dropbox? A folder on your desktop you keep meaning to organize?

```
[Sharepoint]
```

---

## Q7 — What's the one task that eats your week, and where do you currently track work?

The single biggest time-suck or recurring drudgery. Plus where tasks/projects live (ClickUp / Asana / Linear / Notion / a notebook).

```
[RipCord could use more progress, but more issues seemt to be cropping up]
 this file is filled, run `/onboard` (or re-run it) and the wizard will scaffold your Day-1 file set: `context/`, `references/voice.md`, populated `connections.md`, and a filled `CLAUDE.md`.
