# That One AI Podcast — RUN89

## Asset
**TOAP-TXT-002 — Audience Signal Before Audio**

**Hook:** Before we render Episode 1, tell us what deserves to be heard first.

That One AI Podcast now asks visitors to choose one first-episode topic without providing an email address. The preference is stored as an anonymous pre-release `AudienceSignal` and is used only as a production-prioritization signal.

**CTA:** Choose one topic. No email required.

## Customer Truth
A script is not an episode, and an internal episode concept is not audience demand. Before spending production effort, the show should learn which topic visitors most want first while keeping that signal separate from a release claim.

## Production Readiness
The Base44 Home page presents four launch-topic choices when no playable episode exists. A selection records topic key plus campaign attribution, but no PII. The UI explicitly says the signal is not evidence that an episode is produced, scheduled, or released.

## Current Release Baseline
At RUN89 review: 4 durable Episode records, all `draft`, all with `audio_url=null`; therefore 0 verified audio-backed released episodes. `AudienceSignal` begins at 0 records before live traffic.

## Build Receipt
- Base44 checkpoint: `6a9f72dcf42b9b633ab3fd33`
- Base44 commit: `2f6c1794ddb58586ad239537b7398435e2b868fd`
- Final application build: exit `0`
- Audio rendered: no
- Public episode/RSS/directory receipt: not verified
- Production deployment: not independently verified

## Winner Rule
Do not call a topic a winner from one or a few selections. Use anonymous preference counts only to prioritize production after a meaningful sample, then keep production, audio verification, hosting, RSS distribution, and public directory verification as separate states.
