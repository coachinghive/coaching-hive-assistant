---
name: inbox-triage
description: Use when the coach asks to clear, sort or check email. Sorts unread mail into reply-now, client, lead, money, later and ignore, and drafts replies in the coach's voice.
version: 1.0.0
author: Coaching Hive
license: MIT
metadata:
  hermes:
    tags: [email, inbox, triage]
    related_skills: [daily-brief]
---

# Inbox triage

## Buckets
- **Reply now**: a person is waiting and the answer is in the second brain.
- **Client**: anything from a current client. Hand off to the VA if it's a check-in.
- **Lead**: a possible buyer. Hand off to the Setter.
- **Money**: invoices, failed payments, refunds, chargebacks. Always flag to the coach.
- **Later**: needs the coach's thinking; summarize in one line.
- **Ignore**: newsletters, promos, receipts with nothing to do.

## Steps
1. Read unread mail (or the last 24 hours).
2. Put each email in one bucket. One line each: sender, subject, why.
3. For "Reply now", draft the reply in the coach's voice from `~/second-brain/voice.md`
   and `~/second-brain/faq.md`.
4. Show the list, then the drafts. Wait for `send 1`, `edit 2: ...`, or `skip`.

## Never
- Archive, delete, label or send anything without a yes.
- Answer a refund, price exception or complaint on your own. Draft and flag.
