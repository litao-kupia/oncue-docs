# Relationships & memory

OnCue's core is a living memory of the people you work with, built and updated automatically as you talk — no data entry. The more you use it, the more it knows, and the better every reply and brief gets.

## People & dossiers

Anyone in your conversations (calls, Slack, Telegram) becomes a **person** with a structured **dossier**:

* **Role** — title / what they do (pulled from channel profiles too).
* **Style** — how they communicate.
* **Temper** — temperament and emotional tenor.
* **Characteristics** — notable traits.
* **Relationship** — your dynamic, read especially from your DMs.
* **Company** — extracted from conversations.
* **Facts** — durable details (projects, preferences, history).

Open the **People** tab and click anyone for their dossier. The list **groups by company**; system accounts (Slackbot, deactivated users) are filtered out.

* **Relationship strength** — a live health read (**Strong**, **Steady**, **Cooling**, **At risk**) from contact recency and whether you owe them anything overdue. Shown as a coloured dot in the list and a badge on the card.
* **What changed** — when OnCue re-reads someone, it records a one-line "what's new since last time" (a shift in role or mood, an emerging issue) at the top of their card.

## The relationship graph

The **Graph** tab (default People view) puts **you at the center**, everyone around you with their Slack/Telegram avatars (initials as fallback). Connections between *other* people are inferred from recent conversations and **colour-coded by sentiment** (a recent disagreement shows red with a label). Each ring is **tinted by company**, with a named legend.

* **Hover** a node to highlight ties and show its name (names hide by default).
* **Click** a person for their dossier; **click a connection** to see what it's about.
* **Zoom** with the bottom-right controls or **Ctrl + scroll**.
* **Save as image** or **Share** — avatars are embedded so the export isn't blank.

Rebuilds from recent activity automatically, or on demand with **Refresh**.

## Identity across channels

The same person across Slack, Telegram, and voice calls collapses into **one record and one graph node**, even with minor spelling/accent/punctuation differences. Merges are conservative — only with corroborating signal (shared handle, same company, or an empty stub) — so two people sharing a name stay separate. Merged records combine identities, facts, commitments, and dossier; nothing is blanked.

## Reckon — refresh on demand

OnCue **auto-reckons** in the background after you talk to someone (a few people per cycle, newest first), keeping memory current automatically.

You can also click **✦ Reckon** on a person (or **✦ Reckon all**) to rebuild their dossier from latest messages — including DMs, weighed heavily for the relationship read. Reckoning **merges**: new info is preferred, existing details are never discarded.

## Knowledge sources

Memory works alongside your **knowledge base**. Add notes, files, folders, and PDFs in the **Knowledge** tab, or **paste a link** (e.g. a team page) for OnCue to read and fold in. Knowledge can be scoped per session or used across all by default.

## Where it lives

On your device, synced to your own dashboard, never shared. Signing out wipes the local data.

Commitments, briefs, and nudges all run off this memory — see [Commitments & briefs](commitments.md).
