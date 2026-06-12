# Connecting channels

OnCue pulls conversations from your messaging channels into a session alongside the live call — and the people and commitments in those threads feed your [relationship memory](relationships.md).

## Slack

1. Console → **Channels**, connect Slack. OnCue auto-detects workspaces you're already signed into in the browser, so there's usually nothing to paste.
2. When starting a session, add a **Slack thread** as a source.

Context (including each person's **job title**) is pulled in automatically, so a contact has real content before you've talked much. Your own messages are credited to you.

## Telegram

1. Console → **Channels**, connect Telegram and sign in (your own account — you see the chats you normally do).
2. Add a Telegram chat as a session source.

Contacts are tracked by a stable account id, not display name — renames never split a person in two, and two people sharing a name stay separate. Telegram profile photos appear on your [relationship graph](relationships.md#the-relationship-graph).

## Discord

1. Console → **Channels**, connect Discord — one click, read from the desktop app on this device (nothing to paste).
2. Add a Discord DM as a session source, or paste a `discord.com/channels/…` message link to pull that conversation in.

OnCue reads Discord *as you*, locally, for context only — it never sends anything on its own. Contacts are keyed on a stable user id. Note: automated access uses your Discord user token, which is against Discord's terms — use at your discretion.

## What OnCue reads

Only the threads and chats you explicitly follow for a session — never your whole workspace. When you first follow a thread, recent history is used quietly to brief you (and seed memory), but is never dumped into the live transcript. OnCue respects each service's rate limits and backs off under heavy use.

## One person, every channel

The same person across Slack, Telegram, Discord, and voice calls collapses into a **single record** and graph node, even with minor name differences. Their facts, commitments, and dossier merge rather than fragment. When someone uses a different name on different channels, link them by hand with the 🔗 action in the People list.

> Slack, Telegram, and Discord are available today. Calendar-based meeting suggestions are covered under [Sessions](sessions.md).
