# Subsystem Tour

One section per subsystem. Every screenshot below is captured from a sanitized demonstration vault — a fictional family, fictional finances, fictional messages — running the real plugins. GIFs are still being recorded; remaining placeholders are marked.

---

## Select Home

The front door. A native homepage plugin with an app dock, a single-line quick capture, and a Daily Verse card drawn from a 247-verse curated rotation — with a one-tap **Reflect** action that journals the verse and your thought straight into the day's log. Mobile layout is first-class; a bento variant exists behind a setting.

![Select Home](media/home-desktop.png)

The capture line goes straight into the day's journal:

![Capture to journal](media/capture-journal.gif)

## Select Menu

The launchpad — a plain Markdown note that behaves like an app screen. A dock of the daily surfaces up top, then a launcher card for every subsystem that doesn't earn a dock slot, each with its state and a one-line pitch. Because it's just a note, agents update it the way they update anything else: by editing text.

![Select Menu](media/select-menu.png)

## Select Tasks + Board

A task application over ordinary Markdown checkboxes — no new task model, ever. Rows edit natively, subtasks nest, projects and people cross-link. The Board view adds a drag-and-drop kanban that is **pull-only** by design (the failure mode of every kanban is becoming the inventory). Its **Select lane** is the headline: drop a card there and an agent sweeps it within five minutes, drafts the work, and parks the card in Waiting with a link to a reviewable result note — including a "Needs from you" section for what it couldn't do.

![Select Tasks](media/tasks.png)

The Select lane, end to end — a card enters the lane, Select drafts the work, the card parks in Waiting with the draft linked, and the draft ends with what it needs from you:

![Select lane](media/select-lane.gif)

## Media Log

The oldest subsystem and the origin of the whole project. Share a link from any device; an always-on server captures it — text first, so a crash can never drop a post — into one durable Markdown note per item. A library surface browses 2,800+ items with live embeds, tag/source/month filters, and per-item actions. A 1,517-post saved-media history was imported through the same production writer, inheriting every guarantee the pipeline had earned.

![Media Library](media/media-library.png)

> 🎬 coming: phone share → item appears in the library

## Comms

Select has its own email address — and, since August, its own native iMessage line, running under a second account on the server so it texts from a real identity. Inbound mail hits a gateway on the server: allowlisted senders → AI triage → routed to schedule ingestion, self-filing to known destinations, note capture, or ignore — every decision audited, and message bodies treated as data, never instructions. On the chat channels, **conversation is the default door**: anything not command-shaped gets a grounded, free-form reply (with photos read into words at the transport edge, and voice memos transcribed locally), while an Outbound audit shows every message Select sends — including the refused ones. **Missed Messages** watches iMessage for owed replies, resolves phone numbers to real names, and offers inline reply drafts delivered by an isolated, allowlisted sender. A channel registry governs every channel's enabled/reply flags in one place.

![Comms](media/comms-system.png)

## Select Routing

The layer that makes every channel one channel. Whether a message arrives as a Siri dictation, an iMessage, a Telegram chat, a quick-capture line typed on the phone, an emailed instruction, or a sentence inside a recorded thinking session, it funnels into the same parse-and-route core — **Select Routing** — and behaves identically. A voice memo is a text that started as breath; the owner should never have to remember which surface understands which phrasing.

```mermaid
flowchart LR
    voice["🎙 Voice<br/>Siri · dictation · voice memos"] --> core
    chat["💬 Chat<br/>iMessage · Telegram"] --> core
    cap["⌨️ Quick capture<br/>desktop · phone"] --> core
    mail["✉️ Email<br/>instructions"] --> core
    think["🧠 Thinking Time<br/>transcripts"] --> core
    core["Select Routing<br/>words fast path → schema-bound intent parse"]
    core --> doors["Deterministic doors<br/>task · agenda · calendar · person ·<br/>property · finance · dev card · commitment"]
    core --> convo["Conversation<br/>the default door"]
```

The design has three load-bearing rules:

- **Words are a fast path, the model is the parser, the doors stay deterministic executors.** Cheap word-matching routes the obvious cases free; on a miss, a schema-bound intent pass names a door from the closed set and fills its slots — it never gets to write anything itself. Every write goes through the same deterministic primitives, person resolution never involves a model, and a trust gate means only a hand-marked inner circle can be matched by bare first name. Anything not command-shaped falls through to conversation, so a question is answered instead of mis-filed.
- **Channel parity is a hard rule, enforced by a gate.** One shared vocabulary and one fixture suite pin two synchronized implementations — server-side (voice, chat, email) and in-app (capture surfaces) — and a release gate replays **350+ fixture checks across twenty channels, in both implementations, with no writes and no network**. A routing behavior change that lands in one channel and not the others fails the release.
- **Misses become fixtures, never vocabulary.** When a message takes the wrong door, the fix is not another trigger word (that buys one phrasing and leaves the failure class alive) — the correction is pinned as a regression fixture that both implementations must pass forever. Every routed action has a deterministic undo, and new doors ship behind kill switches that are rollbacks, not waiting periods.

## AI Router

The spend and steering console for every AI call in the ecosystem. One shared config decides which model serves each surface (brief, triage, voice, test calls); a budget governor warns, downshifts to a cheaper model, and hard-stops; and every call lands in a shared ledger with its cost — so "add another AI surface" is a calm decision instead of a gamble. Spend readouts also surface in the Comms system console.

![AI Router](media/ai-router.png)

## Calendar + People

A read-only calendar layer ingests the family's calendars into a Today/Upcoming view and a week grid with a now-line — click any event to spawn its note. **Select People** is a CRM that demands zero data entry: mention someone anywhere in the vault and their dossier accrues — I-owe / waiting-on / agenda, a deep-linked mention timeline, calendar-fed contact history, and a Text action wired to Missed Messages.

![People](media/people-dossier.png)

![Calendar](media/calendar-week.png)

## Voice

Three escalating layers: the morning **Daily Brief** arrives as spoken audio (with a truncation guard that refuses to ship implausibly short files); **Ask Select** turns phone dictation into filed vault notes over a key-only, command-restricted tunnel — "Hey Siri" to librarian in one LTE round trip; **Thinking Time** records longer sessions, transcribes, auto-files daily items, and gates any project edit behind approval with a full action ledger.

> 🎬 coming: Siri shortcut → note lands in the vault

## Finances

Raw institution exports drop into a watched inbox folder; adapters normalize them into an atomic ledger — two years of transactions, every account balance, every investment position. Surfaces: net worth by institution with business-account toggles, month signals, income, and a stock benchmark seeded with true purchase lots reconciled to the penny, judged against an index from actual entry dates. Since August it's transaction-deep: every aggregated figure clicks through to its exact rows, the owner's own knowledge (payees, categories, rates the provider won't report) overlays the ledger at read time without ever rewriting it, and itemized retailer charges decompose into AI-categorized line items — with every view still reconciling to the cent.

![Finances](media/finances-overview.png)

## Intentions

The yearly-goals review, rebuilt around **consent instead of staleness**: the review deals one goal or project at a time against its rendered note, and every verdict — next small step, snooze with a horizon, milestone, close — stamps the note and writes a journal line, so silent abandonment is structurally impossible. Session state rebuilds from the daily log itself; a mid-session restart recovered all nine decisions on its first live use.

![Intentions review](media/intentions-review.gif)

## Journal

Daily logs as a continuous timeline with a mini-month sidebar — today's entry is the real file in a live editor, past days mount the same editor on click. It replaced a twelve-year-old monthly-log convention the day it shipped.

![Journal](media/journal.png)

## Dev Dashboard

The dev cycle as a product. Agent recommendations are filed as cards the moment they're made — landing in a Recommended column the owner promotes from. Shipping requires an evidence note: status, what shipped, verification screenshots, and a numbered "your next step." A review room walks the Shipped column one card at a time with approve / needs-work / not-sold / reject routes. This board is how everything else in this document got built.

![Dev Dashboard](media/dev-dashboard.png)

![Dev Review](media/dev-review.png)

## Also in the family

The tour above is the daily core, not the full roster. Sharing the same kit, style, and vault records:

![Projects](media/projects.png)

- **The project cockpit** (shown above) — a heartbeat pulse per project, an importance × momentum map, and a triage deck where every stalled project leaves with a decision; now one mode of the Intentions room, its third home found after shipping standalone.
- **Podcast Runner** — submit an episode URL, get a staged, highlighted summary note with per-run cost accounting — opening with a Listen Decision brief: listen in full, listen to these timestamped stretches, or skip, and what you're not missing.
- **Select Docs** — OCR-first document intake: receipts, invoices, and scanner output, staged, routed, and searchable — with quote deadlines extracted into a standing expired-decisions queue.
- **The Mastermind** — the coaching portal grown into a commitment system: every coach a CRM dossier with sessions, prep, and open promises; commitments have owners (a coach's own promises don't count as the owner's kept word); and AI seats spawn read-only agents that investigate the whole vault from the server.
- **Select Bible** — a Bible study subsystem: reading tracks, a free-reading interface with verse-tagged notes, and sermon capture — deliberately AI-free in version one, and the first app graded by the new single-app review format.
- **Server Watch** — the home server takes hourly screenshots of its own console and runs changed frames through a perceptual-diff-then-vision check, because status files only report what code thought to measure.
- **The Style Guide** — Select's visual languages documented side by side with live specimens, so twenty plugins read as one product.
