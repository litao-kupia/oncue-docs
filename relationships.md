# Relationships & memory

OnCue's core is a **living memory of the people you work with**. It builds and updates
this automatically as you talk — no manual data entry — and uses it to make every
suggestion more personal and more useful over time. This is what compounds: the more you
use OnCue, the more it knows, and the better every reply and brief gets.

## People & dossiers

Anyone who appears in your conversations (live calls, Slack, Telegram) becomes a **person**
in OnCue. Each person accumulates a structured **dossier**:

* **Role** — what they do / their title (pulled from channel profiles too).
* **Style** — how they communicate.
* **Temper** — their temperament and emotional tenor.
* **Characteristics** — notable traits.
* **Relationship** — your dynamic with them, read especially from your direct messages.
* **Company** — the organization they belong to, extracted from conversations.
* **Facts** — durable, concrete details (projects, preferences, history…).

Open the **People** tab in the dashboard and click anyone to see their dossier. The list
**groups people by company** so colleagues cluster together. System accounts (Slackbot,
deactivated users, etc.) are filtered out automatically.

### Relationship strength

Every person carries a live health read — **Strong**, **Steady**, **Cooling**, or
**At risk** — shown as a coloured dot in the People list and a badge on their detail card.
It's computed from how recently you've been in contact and whether you owe them anything
overdue, so at a glance you can see which relationships are warming and which are slipping.

### What changed

When OnCue re-reads someone, it records a one-line **"what's new or different since last
time"** — a shift in role or mood, an emerging issue, a new development — and surfaces it at
the top of their detail card, so you walk in already knowing what moved.

## The relationship graph

The **Graph** tab (the default People view) shows **you at the center** of your network,
with everyone you talk to around you — using their Slack and Telegram avatars (initials as a
fallback). Connections between *other* people are inferred from recent conversations and
**colour-coded by sentiment** (e.g. a recent disagreement shows in red with a short label).
Each person's ring is **tinted by their company**, with a named legend, so organizations are
visible at a glance.

* **Hover** a node to highlight its ties and show the name (names hide by default; nodes
  gently float).
* **Click** a person for their dossier; **click a connection** to see what it's about.
* **Zoom** with the floating controls at the bottom-right, or **Ctrl + scroll**.
* **Save as image** or **Share** the graph — avatars are embedded so the export isn't blank.

The graph rebuilds from recent activity automatically (and on demand with **Refresh**).

## Identity across channels

The same person reached on Slack, Telegram, and in voice calls collapses into **one record
and one graph node**, even with minor spelling, accent, or punctuation differences in their
name. Merges are conservative — two records only fold together when there's corroborating
signal (a shared handle, the same company, or one being an empty stub) — so two different
people who share a name stay separate. When records do merge, their identities, facts,
commitments, and dossier are combined, never blanked.

## Reckon — refresh on demand (and automatically)

OnCue **auto-reckons** in the background after you've talked to someone — a few people per
cycle, newest activity first — so relationship memory stays current without you doing
anything.

You can also refresh on demand: click **✦ Reckon** on a person (or **✦ Reckon all**) to
rebuild their dossier from their latest messages — including your DMs, which it weighs
heavily for the relationship read. Reckoning **merges** with what's already known: new
information is preferred, but existing details are never thrown away.

## Commitments, briefs & nudges

Commitments you make and receive, pre-call and daily briefs, post-call follow-ups, and
proactive nudges all run off this memory. They have their own page:
[Commitments & briefs](commitments.md).

## Knowledge sources

Relationship memory works alongside your **knowledge base** — material OnCue reads to ground
replies. Add notes, files, folders, and PDFs in the **Knowledge** tab. You can also **paste a
link** (e.g. a company or team page): OnCue reads the page and folds it into your knowledge
base. Knowledge can be scoped per session, or used across all of them by default.

## Where it lives

It all stays **on your device**, synced to your own dashboard — never shared. Signing out
wipes the local data.
