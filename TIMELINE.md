# The Select Timeline

Select keeps its own history: every ship goes into a changelog, and the changelog is periodically distilled into a narrative timeline. This is the public cut of that document — same events, same dates, with personal details removed.

**Span:** December 27, 2025 → August 2, 2026.
**Shape:** a vision, six months of quiet groundwork, three weeks in which nearly everything below was built — then a fortnight of facing outward, hardening, and living in it.

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

## Phase 6 — Public, hardened, lived-in (July 21 – August 2, 2026)

- **Jul 21** — **This page goes public.** The showcase you are reading was commissioned in the morning and public before lunch: a fictional demo family's vault runs the real plugins over generated data (so screenshots can't leak — every byte is fiction), and the site's pages live in the private vault, auto-published every five minutes through a sanitization guard. Same day, the Media Log plugin becomes Select's first public code release, with a recipe for building your own companion runner.
- **Jul 21–22** — A travel plugin ships at night and is folded into the Intentions surface the next morning — *ship fast, reverse fast* now applies to whole plugins. A stock CRM lands on plain notes that outlive the plugin; when the build deviates from the approved prototype, the same-evening feedback round rebuilds it to match.
- **Jul 23** — **Hardening day.** A sweep of the security review's findings: live credentials found pasted in an old daily log are scrubbed and revoked, and the publisher gains secret-shape guards so the mistake is unrepeatable. The mail gateway starts verifying sender authentication (forged mail fails closed). Runner state writes become atomic. The vault's text core gets a nightly versioned off-site mirror — proven by a restore drill, not assumed.
- **Jul 23** — **Doctrine day, same day.** A usage ledger makes "done" mean *used*: cards only reach the final board column after their surface shows seven real days of use. Three subsystems are retired in an afternoon with full archive notes. The morning brief is rebuilt around *three real-world moves* — move a goal, keep a word, close a loop — fed by an engine that rescues tasks stranded in old daily logs. And a two-way Telegram channel goes live, gate by explicit gate, with voice memos transcribed locally so audio never leaves the machines.
- **Jul 25** — **Everything is an asset.** The property subsystem becomes the household's asset spine: every house system, vehicle, vendor, and policy a plain note with a stable grammar, service history that writes itself from daily-log mentions, and a generated House Book a future buyer could be handed.
- **Jul 26–27** — The AI provider key dies and every AI call silently fails for ~21 hours *while every heartbeat stays green* — the runners were healthy; their work was hollow. Two layers land in response: an external dead-man's switch and a ten-minute auth probe on the key itself. The silence is now capped at minutes, not days.
- **Jul 30–31** — A fourteen-card overnight sweep rebuilds the doing layer (a command dashboard, a portfolio board for strategic bets, two more honest retirements). The document system ships **seven versions in one day**, each from a real friction, ending as a searchable library — including one disclosed near-disaster where a script wiped the live queue and the restore, and the incident report, both made the record. Push nudges go live: three a day, each landing on a purpose-built twenty-second surface.
- **Aug 1** — **The forensics finale.** A share-sheet capture shortcut had been "done" for eight days without ever actually running — no headless import path existed, so nothing had ever verified. Five distinct bugs fall in one night, each diagnosed by comparing generated bytes against shortcuts that had worked for years. The rebuilt version guarantees a captured line always lands, whatever the payload.
- **Aug 2** — The launcher gains a **Talk to Select** section: six channels, each card saying when to reach for it. The system has enough senses that "which one do I use right now?" became a surface worth shipping.

> *Lesson kept: a heartbeat says the process ran, not that the work succeeded — probe the dependency, not just the pulse.*

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
- A capture shortcut was marked done for eight days without one real execution — five bugs were waiting behind the first import. New rule: signed and shipped without a runtime run is a hypothesis wearing a checkmark.
- Every AI call failed silently for 21 hours while all health checks stayed green — health now means the *work* succeeded, not that the process ran.
- A cleanup script truncated a live queue file before reading it; the restore came from that morning's automatic backup, and the incident report shipped in the changelog alongside the fix.
- Live credentials were found sitting in an old daily log — scrubbed, revoked, and turned into publisher-side guards so the same leak can never reach a public page.

## By the numbers

All live counts from the real system, August 2, 2026:

**The record**
- **574** changelog entries — every ship, logged by the agent that shipped it
- **233** Dev Dashboard cards: **104** reviewed, **35** *lived* (proven by seven-plus days of real use), **51** shipped awaiting review, **21** honestly killed (not-sold or rejected)
- **23** session debriefs · **114** timeline entries across **44** narrative arcs

**The build**
- **19** plugins in one monorepo — down from 21, because retirement is a feature
- **8** shared agent skills, one store, read live by every agent
- **1** public plugin release, and this showcase — the only two public surfaces, by design

**The life inside it**
- **~11,000** files in the vault · **220** daily logs
- **2,693** captured media items as native notes
- **144** people records · **77** projects under cockpit management

**The runtime**
- **19** scheduled jobs on the home server, each with a heartbeat — plus a second-machine watcher and an external dead-man's switch watching the watchers
- **2** machines · **N** interchangeable agents · **1** source of truth
- One AI budget governor: **$10/month** with a hard stop — the entire assistant layer runs inside it, and un-costed calls are estimated so the cap can't be blinded

---

*Distilled from the system's own changelog and narrative timeline, updated August 2026.*
