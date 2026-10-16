---
name: reply-classification
description: Use when candidate replies arrive to sort each into a status, update the tracker, and propose the next step.
---
# Reply classification

Read each reply; assign exactly one class; propose the next step. Ambiguous → flag for the recruiter, don't guess.

| Class | Signals | Next step | Status |
|---|---|---|---|
| Interested | "tell me more", shares number, proposes time | Hand to recruiter with packet; offer times | Interested |
| Info-sent | Asks for JD/comp/details | Draft reply with approved info only | Info-sent |
| Not-now | "happy where I am", "maybe next year" | Thank them; set reminder (default 6 months) | Not-now |
| Referral | Names someone else | Thank; add referral as New with source noted | Awaiting + New |
| Wrong-person | Not the right profile / role mismatch | Polite close; note why to improve the cut | Rejected |
| Unsubscribed | "remove me", "stop", hostile | Confirm removal once, never contact again | Unsubscribed (terminal) |
| Auto-reply | OOO, bounce | Shift follow-up date; fix address on bounce | Awaiting |

## Status machine
New → Qualified/Rejected → (recruiter names) Approved-to-contact → Awaiting → Interested | Not-now | Info-sent | Unsubscribed → (recruiter) Submitted. Paused search → On-hold. Unsubscribed and Rejected are terminal.

## Output
Daily triage list: name — class — one-line quote — proposed next step — draft ready (y/n). Repeat rejection reasons twice → propose a new Pass 1 knockout.
