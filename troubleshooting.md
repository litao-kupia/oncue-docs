# Troubleshooting

## SmartScreen warning on install

Windows may flag the installer as from an unknown publisher. Choose **More info → Run
anyway**. (Code signing is on our roadmap.)

## My microphone isn't being transcribed

* Check that the right mic is set as your Windows **default input device**.
* If another app is exclusively using the mic, close it and restart the session.
* Confirm OnCue has microphone permission in **Windows Settings → Privacy → Microphone**.

## The other side isn't being transcribed

OnCue captures **system audio** (what's playing on your machine). Make sure call audio is
playing through your computer (not a disconnected headset), and that **System audio** is
enabled as a session source.

## Audio dropped mid-call

If your mic or system audio drops — an unplugged headset, a default-device switch, or a
transient glitch — OnCue now re-opens it automatically with backoff instead of going silent
until you restart. The audio warning clears once capture recovers.

## Advice or replies stopped appearing

* Check your [usage](plans.md) — on the Free plan, AI features pause when you hit your token
  limit.
* Confirm you're signed in and online; live advice needs a connection.

## The update didn't install

OnCue auto-updates on launch and re-checks periodically while running, so a long session
still picks up a new release. If an update can't apply, download the latest installer
manually from [oncue.fun/download](https://oncue.fun/download) and run it once.

## Still stuck?

Email **support@oncue.fun** with what you were doing and any on-screen message.
