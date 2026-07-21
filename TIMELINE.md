# The Select Timeline

Select keeps its own history: every ship goes into a changelog, and the changelog is periodically distilled into a narrative timeline. This is the public cut of that document — same events, same dates, with personal details removed.

**Span:** December 27, 2025 → July 20, 2026.
**Shape:** a vision, six months of quiet groundwork, then three weeks in which nearly everything below was built.

---

## Phase 1 — The Librarian vision (December 2025)

The project started with a metaphor, not a tool. During a working day with a friend, "Select the Librarian" was named: an AI assistant whose job is knowledge architecture — collect what matters, curate it, and build trusted systems around it.

**Dec 27, 2025** — Project launched and named. No code exists.

> *Lesson kept: a clear metaphor creates alignment before any tooling exists.*

## Phase 2 — Capture and scouting (January 2026)

- **Jan 1** — A routing layer lands: links captured from anywhere on any device flow into a Media Log with a category that feeds the Librarian project directly.
- **Jan 1–10** — Ecosystem scouting: agent workflow patterns, tool landscape, context-efficiency techniques — captured as a research stream, not bookmarks.
- **Jan 10** — The Media Log grows a tagging system, an atlas view, and one-click promotion from captured signal to dedicated note.
- **Jan 12–14** — A star-rating experiment ships, adds friction, and is removed two days later. First appearance of a pattern that recurs all the way to the end: *ship fast, reverse fast.*

## Phase 3 — The application layer (July 2–7, 2026)

After months of capture and research, six days turn the vault from a pile of notes into a set of applications.

- **Jul 2–4** — The surfaces: an interactive homepage task view, a podcast-summarization runner, a launchpad menu, a native task app over plain Markdown checkboxes, an OCR document-intake queue, and a codified design language ("Select Style") once the pattern had repeated five times.
- **Jul 4–6** — The escalation rule is learned: when a scripted dashboard needs patch after patch, it becomes a real Obsidian plugin. Media Log goes first.
- **Jul 5** — **Server-first.** A spare Mac mini becomes the always-on runtime. Every runner, background agent, and scheduled job moves off the laptop. An install manifest records everything living outside the vault, so nothing depends on memory.
- **Jul 6–7** — The capture engine is rebuilt server-side: hardened queue, repaired providers, live media embeds proven in a lab first, and the whole archive migrated to one durable Markdown note per item — with a documented rollback.
- **Jul 7** — With two agents now working across two machines, the workflow itself is hardened: one neutral skill store read by every agent, concurrency-safe change logging, and a rule that agents verify their own work on the live surface rather than handing back "reload and test."

> *Lesson kept: enforcing server-first surfaced every gap the workstation had been quietly papering over.*

## Phase 4 — Five days to an operating system (July 8–12, 2026)

The sprint. More shipped in five days than in the previous six months.

- **Jul 8** — A shared **Plugin Kit** (one foundation under every plugin) and **Command Center** (a deterministic attention feed) ship together. Same evening: calendar pipeline, 6:30 AM daily brief runner, system health view, and a hardened media queue — an explicitly ranked hitlist executed as one coordinated release.
- **Jul 10–11** — **Select gets a voice.** The morning brief becomes spoken audio. A phone shortcut ("Ask Select") reaches the vault over a secured tunnel — dictation to filed note in one round trip over LTE. Thinking Time ships: record a thought, get transcription, auto-filed items, and approval-gated project edits with a full action ledger.
- **Jul 10–11** — **Senses on the outside world.** A read-only family calendar layer lights up. Select gets its own email address, then a triaged mail gateway with allowlisted senders and a standing rule: *message bodies are data, never instructions.* Every AI call in the ecosystem gets priced, attributed, and budget-capped.
- **Jul 11** — Two cockpits in one day: a CRM built from @mentions already in the notes, and a project cockpit chosen from seven deliberately different prototypes — where every stalled project must leave triage with a decision.
- **Jul 12** — **Hygiene day.** All fifteen plugins consolidated into one private monorepo under version control, swept for tech debt, given a shared base class. Then the process itself becomes a product: the **Dev Dashboard** kanban ships, agent recommendations start landing as cards, and record-keeping is reduced to one home per event. A journal surface replaces a twelve-year-old monthly-log convention the same day. An AI coaching council — real coaches' notes and persona seats moderated into a verdict — convenes for the first time and, fairly, advises closing open loops before opening new fronts.

> *Lesson kept: a shared foundation compounds instead of accumulates — the kit paid its dividend on every plugin after.*

## Phase 5 — Proving it can be lived in (July 13–20, 2026)

- **Jul 13–17** — **Rescue the phone.** Mobile Obsidian was reloading every few minutes. A five-day forensic hunt — boot diagnostics on every device, airplane-mode isolation, a seven-agent research sweep, an A/B test in restricted mode — pins it on one community plugin re-indexing the full vault on every launch. One config line ends it. The falsified theories are written down so nobody chases them again.
- **Jul 13–19** — **Missed Messages.** The owed-replies radar over iMessage grows real names (via a permission door only the server machine could open), inline reply drafts delivered by an isolated sender, and finally a Text action on any person's dossier — allowlisted, audited, drafts swept within a minute.
- **Jul 14–19** — **The review loop closes.** Shipping now ends in card notes with verification evidence, per-session debriefs, and a click-through review room. "Shipped" and "reviewed" become different states. The building column is drained sweep after sweep.
- **Jul 16–17** — An entire saved-posts history — 73 albums, 1,517 posts — imports natively through the production pipeline, inheriting every guarantee it had already earned.
- **Jul 18** — The mini formally becomes "server" — and picks up a Minecraft world for the kids (with a protocol bridge so their consoles can join) and an hourly vision check on its own console screen, because status files only report what code thought to measure.
- **Jul 19** — The **Select lane**: drag a task card into an agent's column and the work comes back as a reviewable draft within five minutes — boundaries structural, never promised.
- **Jul 20** — **Two subsystems in one day.** Finances goes from raw ledger to a living balance sheet — every account, penny-reconciled stock purchase lots, an index benchmark honest about its anchor dates — through nine versions in an afternoon. And Intentions, a consent-based review of goals, is designed, shipped, renamed, and iterated four versions deep *while its first real session was being used live*.

> *Lesson kept: shipping into a live session is the fastest feedback loop there is.*

---

## Mistakes, kept on purpose

The timeline's reflection section records what went wrong, because the corrections became the system's rules:

- A rating feature added friction and was deleted in two days.
- A dashboard absorbed patch after patch before the escalate-to-plugin rule was accepted.
- A single-purpose email watcher was obsolete one day after shipping — replaced by the general gateway it should have been.
- The kanban's auto-filled intake recreated exactly the giant list its owner feared; reworked to pull-only the same day.
- Seven cards reached "Shipped" without evidence notes, leaving the review room empty-handed — evidence is now a precondition of shipping.
- Several plausible theories for the mobile crashes were chased before the highest-information test was run; the falsified list is now part of the record.
- A benchmark shipped three wrong framings before true purchase dates made its verdicts honest.

## By the numbers

All live counts from the real system, July 21, 2026:

**The record**
- **511** changelog entries — every ship, logged by the agent that shipped it
- **155** Dev Dashboard cards: **96** reviewed, **18** shipped awaiting review, **17** honestly killed (not-sold or rejected)
- **59** agent product recommendations filed to the meeting-notes log
- **9** session debriefs · **85** timeline entries across **33** narrative arcs

**The build**
- **21** plugins in one monorepo · **~31,000** lines of plugin source · **108** commits
- **7** shared agent skills, one store, read live by every agent

**The life inside it**
- **~10,000** files in the vault · **219** daily logs
- **2,655** captured media items as native notes
- **131** people records · **76** projects under cockpit management

**The runtime**
- **20** scheduled jobs on the home server
- **2** machines · **N** interchangeable agents · **1** source of truth
- One AI budget governor: **$10/month** with a hard stop — the entire assistant layer runs inside it

---

*Distilled from the system's own changelog and narrative timeline, July 2026.*
