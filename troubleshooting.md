# Troubleshooting

**SmartScreen warning on install** — Windows may flag the installer as from an unknown publisher. Choose **More info → Run anyway**. (Code signing is on the roadmap.)

**My mic isn't transcribed** —
* Set the right mic as your Windows **default input device**.
* If another app holds the mic exclusively, close it and restart the session.
* Confirm mic permission in **Windows Settings → Privacy → Microphone**.

**The other side isn't transcribed** — OnCue captures **system audio**. Make sure call audio plays through your computer (not a disconnected headset) and that **System audio** is enabled as a source.

**Audio dropped mid-call** — if your mic or system audio drops (unplugged headset, default-device switch, glitch), OnCue re-opens it automatically with backoff; the audio warning clears once capture recovers.

**Advice or replies stopped** —
* Check your [usage](plans.md) — on Free, AI features pause at your token limit.
* Confirm you're signed in and online; live advice needs a connection.

**The update didn't install** — OnCue auto-updates on launch and re-checks while running. If an update can't apply, download the latest installer from [oncue.fun/download](https://oncue.fun/download) and run it once.

**Still stuck?** Email **support@oncue.fun** with what you were doing and any on-screen message.
