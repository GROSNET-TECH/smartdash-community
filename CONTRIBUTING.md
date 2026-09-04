# Contributing

Smart Dash is closed-source, so there is no code to send us. What is useful here is everything
else: a bug you can reproduce, a feature you can describe, or an answer to somebody else's
question.

None of it is required. For account or billing help, email **support@getsmartdash.com** — that is
the guaranteed channel, and the only one with an answer time attached.

## Where things go

| You want to | Go to |
|---|---|
| Ask "how do I…" | [Discussions → Q&A](../../discussions/categories/q-a) |
| Float an idea before it is a request | [Discussions → Ideas](../../discussions/categories/ideas) |
| Show what you built | [Discussions → Show and tell](../../discussions/categories/show-and-tell) |
| Report something broken | [New issue → Bug report](../../issues/new/choose) |
| Request a capability | [New issue → Feature request](../../issues/new/choose) |
| Report a vulnerability | [SECURITY.md](SECURITY.md) — not a public issue |

## What makes a bug report actionable

The bug template asks for these because without them a report usually cannot be reproduced:

- **App version** — Settings → About.
- **Platform and OS version**, and the device.
- **The protocol involved**, if a source is: HTTP, WebSocket, SSE, Socket.IO, MQTT or BLE.
- **What you did, what you expected, what happened.** In that order.
- **A screen recording** for anything about layout, widgets or live values. A still rarely shows it.

Two things that help more than they sound like they would:

- The **Connection Monitor** (dashboard header) shows each source's state and the raw payloads
  arriving from your device. If data is not appearing, what it shows is usually the answer.
- The **shape of your payload**, not its contents. Replace real values with fake ones and keep the
  structure — that is the part that matters, and it means you are not pasting credentials into a
  public issue.

Never paste an API key, password, token or a private endpoint address into an issue or a
discussion. Both are public and permanently indexed.

## What happens next

Issues are read, labelled and triaged, but this is a best-effort channel rather than a support
queue with a clock on it. `confirmed` means we reproduced it; `needs-info` means we could not and
are waiting on you; `shipped` means the fix is in a released version. Fixes reach you through the
App Store and Google Play, so a store review sits between a merged fix and your phone.

## Pull requests

There is no source code in this repository, so there is nothing to build against. A PR fixing a
typo in these files is welcome. Anything about the documentation itself belongs on
[the docs site](https://getsmartdash.com/docs) — open an issue here and we will take it from there.
