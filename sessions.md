# Sessions

A **session** is an isolated working context for one conversation. Each session has its own
guideline, knowledge, input sources, and transcript — and produces a **summary + action
items** when it ends.

There's always an always-on **General** session for ad-hoc use; create named sessions for
anything you want kept separate. Both feed relationship memory and commitments — so profiles
and promises populate during normal use, not only after you end a named session. The General
session is periodically summarized into a rolling digest in the background so it never grows
without bound.

## Starting a session

When you start a session you can set:

* **Name** — how it appears in your history.
* **Guideline** — a short instruction that shapes the advice (e.g. *"Be concise and
  technical."*).
* **Knowledge** — notes, files, or folders OnCue should read to ground its suggestions.
* **Sources** — where input comes from (see below).

## Input sources

* **Your voice** — your microphone (labeled "you").
* **System audio** — whatever is playing on your machine, i.e. the other side of the call.
  Speakers are separated automatically.
* **Channels** — follow a specific Slack thread or Telegram chat so its messages flow into
  the session. See [Connecting channels](channels.md).

Your voice + system audio are enabled by default. You can combine multiple sources. In the
input panel, a **FOLLOW** toggle auto-scrolls to the newest line (on by default) — turn it
off to read back without being yanked to the bottom.

## Attachments

Attach **files and folders** when starting a session — including **PDFs** — and OnCue will
read them as background knowledge for more grounded replies.

## Briefs from the session menu

Before a meeting, OnCue suggests starting a session from your calendar, with a **Brief me**
button for a [pre-call brief](commitments.md#pre-call-brief). The overlay session menu also
has **✦ Pre-call brief** and a **☀ Daily brief** any time.

## Resuming

Already-ended sessions can be **resumed**: reopen one to keep adding to the same context and
transcript instead of starting fresh.

## Ending

Ending a session generates a concise **summary** and a list of **action items**, saved to
your history and viewable in the [web dashboard](https://oncue.fun/dashboard).
