# Proddy Agent

A personal AI agent for product managers. It runs as its own identity, works your inbox and chat, and keeps you in the loop on anything that leaves the building.

Not a chatbot you open. An operator that sits inside your existing tools and handles the administrative surface of product work — triage, minutes, specs, follow-ups — so your attention goes to the decisions, not the formatting.

## What it does

**Response check (the default run).**
Scans your email and team chat, sorts everything into four buckets — Urgent, Reply Now, Watch, Ignore — and drafts replies for the Reply-Now items only. You approve before anything sends. The point is to surface the two messages that need you out of the twenty that don't.

**Meeting minutes.**
Pulls a meeting's transcript and attendee list, parses it into structured minutes — decisions, owners, next steps — and produces a clean formatted document. No writing up notes after every call.

**Feature specs.**
Turns a rough idea or a conversation into a structured spec: personas, journeys, edge cases, acceptance criteria. The shape an engineer can actually build from.

**Follow-up tracking.**
Surfaces open loops and overdue commitments — the threads you said you'd close and didn't.

## How it behaves

**Human-in-the-loop by default.** Nothing sends without your explicit approval. There is exactly one exception: acknowledgement-class replies in your own 1:1 chats ("On it", "Will share by 3") — and only when no new commitment is made, nothing is disclosed, and no decision is taken. Everything else waits for you.

**It writes in your voice.** Every outbound message is held to one test: it has to read like you wrote it. No AI-tells, no markdown walls dumped into a chat window, no manufactured sign-offs. If a draft comes in formatted wrong, Proddy fixes it before it goes out — it's the last line between a sloppy draft and your name on it.

**It verifies its own work.** After every send it confirms the message actually landed. After every action it checks the result. It doesn't assume success.

**It quotes failures verbatim.** When a guardrail blocks something, Proddy reports exactly what the block said — no paraphrasing, no guessing at reasons, no inventing a story. An honest failure beats a confident wrong explanation.

## What it is not

- A general-purpose chatbot
- A team tool — Proddy is built for one operator and is opinionated about that one workflow
- A decision-maker — it handles distillation and formatting; the judgement stays yours

## Status

Running daily in private. This repo documents the design; a shareable reference implementation is being lifted out of the personal build. Open an issue if you're building something similar.

## Contributing

Ideas and design feedback are as welcome as code — this is a design repo first. Open an issue before a PR and describe the use case. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

MIT — see [LICENSE](LICENSE).
