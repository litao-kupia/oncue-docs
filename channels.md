# Connecting channels

OnCue can pull conversations from your messaging channels so they flow into a session
alongside the live call — and, just as importantly, so the people and commitments in those
threads feed your [relationship memory](relationships.md).

## Slack

1. Open the desktop console and go to **Channels**.
2. Connect Slack. OnCue auto-detects workspaces you're already signed into in your browser,
   so in most cases there's nothing to paste.
3. When starting a session, add a **Slack thread** as a source.

OnCue pulls in useful context automatically — including each person's **job title** — so a
contact has real content even before you've talked much. Your own messages are credited to
you, not the other side.

## Telegram

1. In **Channels**, connect Telegram and sign in to your account (this uses your own
   Telegram account, so you see exactly the chats you normally do).
2. Add a Telegram chat as a session source the same way you would a Slack thread.

Telegram contacts are tracked by a stable account id rather than their display name, so
someone renaming themselves never splits them into two people — and two different people who
happen to share a name stay separate. Telegram profile photos also appear on your
[relationship graph](relationships.md#the-relationship-graph).

## What OnCue reads

Only the threads and chats you explicitly follow for a session. OnCue does **not** browse
your entire workspace — it watches the specific conversations you point it at. When you
first follow a thread, recent prior history is used quietly to brief you (and to seed
relationship memory) but is never dumped into the live transcript.

## One person, every channel

The same person reached on Slack, Telegram, and in voice calls collapses into a **single
record** (and a single node on the graph) — even with minor differences in spelling, accent,
or punctuation in their name. Their facts, commitments, and dossier merge across channels
rather than fragmenting.

OnCue also respects each service's rate limits, backing off politely under heavy use so your
account is never throttled.

> Slack and Telegram are available today. Calendar-based meeting suggestions are covered
> under [Sessions](sessions.md).
