# The Select Timeline

Select keeps its own history: every ship goes into a changelog, and the changelog is periodically distilled into a narrative timeline. This is the public cut of that document — same events, same dates, with personal details removed.

**Span:** December 27, 2025 → September 23, 2026.
**Shape:** a vision, six months of quiet groundwork, three weeks in which nearly everything below was built, a fortnight of facing outward and hardening — then seventeen days of depth: truth-telling reviews, transaction-deep finances, and a conversation spine with its own phone line — and five weeks of making that spine the only one, making the tests honest, and opening new rooms on top of it.

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

## Phase 7 — Depth, truth, and a phone line of its own (August 3–19, 2026)

Less new territory, more truth. The system stopped adding rooms and started proving the ones it had.

- **Aug 4–7** — **The ledger learns honesty.** Loan credits posing as income are excluded at the model layer; a "needs eyes" queue is tuned against real data before it ships (the naive rules would have flooded five times as many rows); the full transaction archive imports; and a retailer export that parsed twenty thousand rows "cleanly" while capturing no money at all is caught and rebuilt — a clean run and a correct run are different claims.
- **Aug 5–6** — **The review becomes an institution.** A standing authoring standard, a review library, embedded prototypes, checkable decision desks — and Review #4's honest thesis: *truth without traction*, printing a zero where the owner's own follow-through hadn't happened. One over-correction (a stated taste hardened into mandatory machinery) lasted eleven minutes and became a rule: preferences are direction, not law.
- **Aug 6** — **Executing the review.** A three-mode task room, conflict-safe event stores under the busiest records, and a control-plane doctor that found a real regression in its own first pass. A no-write routing contract gate goes in front of every capture entrance and immediately catches three defects that had been shipping silently.
- **Aug 7–8** — **The build queue becomes a machine.** Four back-to-back sessions drain the column from 48 cards to zero, and "work the queue" is codified to mean the whole column.
- **Aug 7–16** — **Going public, round two.** The dev-cycle kanban becomes the second public plugin release, under a new standard: every release ships a guide written for humans and agents together, with screenshots only ever captured from the fictional demo vault. One history-wide privacy gate — working tree plus every reachable commit, with an adversarial self-test — runs identically at manual check, pre-push, and CI. When it flagged metadata in already-published history, the history was rewritten through the live gate; the check was never weakened.
- **Aug 8–12** — **The council becomes a mastermind.** Coach seats grow into CRM dossiers; session notes mint commitments with owners (a coach's own promises don't count as the owner's kept word); and AI seats stop answering from a summary — each ask spawns a read-only agent that investigates the whole vault from the server.
- **Aug 10** — **Select gets its own phone line.** A native iMessage identity on a second server account, every outbound word audited in one stream (including refused sends — an audit that hides blocked attempts isn't an audit), and conversation becomes the default door on every chat channel: nine measured seconds from text to grounded reply.
- **Aug 10–15** — **The household loop.** A 5 AM task email to the spouse with tap-to-reply completion buttons, mapped by per-send manifest to exact vault lines; the weekly family agenda moves to Friday and closes its loop — authenticated replies from either spouse append to the exact agenda note.
- **Aug 12** — **The monorepo reckoning.** A content-level audit finds five branches of real work that never merged while the manifests read *higher* version numbers than the branches they were missing. New law: version numbers are not merge state.
- **Aug 12–16** — **The bar is indistinguishability.** **Select Routing** — the one channel-agnostic parse-and-route brain behind voice, chat, email, and capture alike — stops patching gaps with trigger words: a schema-bound intent pass parses meaning while deterministic doors stay the only executors, and misses become regression fixtures pinned across both of its synchronized implementations. A texted photo that "came through blank" exposes that the messaging placeholder character isn't whitespace (every emptiness guard was dead code); a day of mishandled texts traces to a daemon running three-day-old code. The owner names the bet: the conversation spine is the future, and the bar is not being able to tell Select's chat from a first-class one.
- **Aug 15–16** — **Finance, transaction-deep.** Every aggregated figure on the finance surfaces now clicks through to its exact rows; the retailer's twelve thousand item lines are AI-categorized for under a dollar, decomposing a giant "shopping" bucket into what was actually bought; two hundred scanned checks get names with privacy-bounded evidence images.
- **Aug 16** — **The multi-agent review.** Three different AI engines audit the same estate, critique each other's reviews, and merge into one plain-language decision desk — rewritten so every item states objectives and side effects in the owner's language, build specs folded separately. The desk's checked items are executed the same night.
- **Aug 11–19** — **Ship, measure, iterate — in miniature.** A Bible study subsystem ships; the first single-app review grades it without mercy (nine for records architecture, one for lived adoption — the usage ledger doesn't flatter); and its first roadmap feature ships from that verdict.

> *Lesson kept: code on disk is not code in memory — a daemon that never reloads can quietly eat every message for three days.*

## Phase 8 — One spine, and tests that tell the truth (August 20 – September 23, 2026)

The conversation bet from Phase 7 was cashed in: every chat path collapsed into one line, the router learned to be honest about what it had done, and the testing layer was rebuilt until a red result meant something. Then, with the spine trustworthy, new rooms opened.

- **Aug 21–26** — **Main is production truth again.** Deployed plugins had drifted from the main branch — one release changelogged but never deployed, fixes stranded on unmerged branches. A convergence pass brings every deployed bundle to a byte-for-byte match with a fresh build of main, and a new rule makes agents prove their base tree matches the deployed bundle before editing anything.
- **Aug 25** — **One prompt a day.** The morning brief, delivered by iMessage, becomes the only message Select starts on its own; push nudges retire. Before the switch, two live drills pass: a server reboot and a signed-out messaging account.
- **Aug 26** — **One chat spine.** The Telegram channel is retired — switched off in the registry, restorable in two steps — and iMessage becomes the single chat line, with a daily self-ping proving delivery and a sweep that recovers texts that died while the line was down. One working session produces eight waves of routing upgrades: a per-door intent schema so the model can't invent slots, receipts that name where a write landed, a reply contract, memory that reaches past the session with approval, split dictation stitched back into one message, and a glossary of the owner's own shorthand.
- **Aug 26–27** — **A language of its own.** The **Select Lexicon** collects the words coined with the agents — modes of thinking, component names, retired terms — first mined from 130+ agent transcripts; a naming door adds a row whenever something is named in any channel.
- **Aug 30** — **Time windows gate safety, never comprehension.** Every message is read against its thread's recent history, so late replies and corrections still land after timers expire. A correction door ("No — …" undoes and re-routes), a guess band that keeps uncertain items out of canonical records, and an unclear-message contract: anything misunderstood is filed verbatim, with a task that checks itself off once a replay handles it. Document attachments parse through one shared engine on email and chat alike. The weekly household meeting gets a live mode of its own.
- **Aug 31 – Sep 1** — **A third engine joins the review.** Comprehensive Review #6 is written by a third AI vendor's model, with a thesis the others hadn't named: *the conversation is a channel; others made it a workplace.* Nine recommendations, each with a prototype image.
- **Sep 7** — **Beyond one sender.** The iMessage line grows a bounded household access tier below the owner — shared-life records and conversation with isolated memory, but never code, configuration, money, or the owner's private thread — pinned in the routing contract, with a read-only audit panel that shows every sender's tier and never a message body. The morning task email becomes two-way: *Done* and *Not mine* per task, parsed with no AI call.
- **Sep 8** — The media library gets capture-time tag suggestions from a closed vocabulary (budget-capped, kill-switched, fail-open) and a keyboard-driven sweep through the untagged backlog.
- **Sep 8–17** — **Accounting-grade agency.** A rental-business surface ships read-only with drill-through to every ledger line, and a long records reconstruction runs across many sessions and two AI engines through a shared handoff file. The rules it set: every external write backed up first, batched, recorded in a hash-chained audit log, and undoable by batch or entry; corrections held as unposted proposals until one whole-picture review covers them all; evidence kept with checksums and proven by independent verifier scripts.
- **Sep 19** — **Verification becomes infrastructure.** A nightly self-test proves agents can still drive the server's app and names the step that broke when they can't; a shared papercuts log records every tooling friction for every engine; and the rule is written down that *a broken verification path is the task, not a blocker to report.* The same day, a review of the text channel finds the intent parser had failed on every call for ten days after the model provider began rejecting its response schema — rebuilt the same day.
- **Sep 19** — **The write fence.** An unsandboxed test had been filing fake tasks into the owner's real daily log whenever the suite ran, while four separate change records waved it off as a "pre-existing failure." Tests now run behind a fence that fails any write to the real vault by name, and the suite goes fully green for the first time in four weeks.
- **Sep 19–20** — **Select Learn.** Every subject being studied becomes a class — syllabus, notebook, timeline, and tagged captures in one readable note — fed identically from text, voice, quick capture, and the page. First version to eleventh in two days.
- **Sep 20** — **Select Media.** A watchlist, a watched log, streaming subscriptions, a music shelf, and **Tonight**: three titles playable right now on services already paid for. A *started* door lets "started watching X" work from any channel, and receipts stop confirming completions that never wrote anything.
- **Sep 20–23** — **Outreach gets a room.** Select Marketing tracks one question for a professional practice's social presence: does posting start conversations? The same week, the cloud storage fills and workstation edits silently stop reaching the server and the phone for three days — until a storage-quota check, now the first thing agents run when another machine looks stale, named the cause.

> *Lesson kept: a green test suite with a known failure is a red test suite — and a send counter is not a delivered message.*

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
- An import that parsed twenty thousand rows with zero exceptions captured no money at all — the aliases predated the export format, so a "clean" run was financially empty.
- A chat daemon ran three-day-old code because a deploy never restarted it — the intent router was enabled on disk but never loaded. It now watches its own sources and reloads itself.
- A messaging platform's attachment placeholder isn't whitespace, so every "empty message" guard was dead code — photos read as blank, and voice memos had silently never fired since shipping.
- The new privacy gate's first pass over already-published history found personal metadata in seven public commits — fixed by rewriting the public history through the live gate, never by weakening the check.
- A shipped feature went unnoticed for a week because the host app's own stylesheet out-cascaded its checkboxes — "never built" and "renders invisibly" file identical bug reports.
- The lived-use metric was counting the agent's own verification footsteps as evidence of the owner's use — any metric meant to measure the human must be deaf to the agent.
- A message send reported success while the messaging account was signed out, and nothing arrived. Delivery is now proven by a daily round trip to itself, never by a send counter.
- A merge failure hidden inside a shell pipeline left a release tag pointing at unmerged code, so the deploy shipped nothing. Every step's exit code is checked on its own now, and every deploy is hash-verified.
- A routing "dry run" still wrote a record through a fallback path — found by a verification probe; dry runs are now write-free end to end.
- The intent parser failed on every call for ten days after the provider began rejecting its response schema. The fallbacks were good enough that nothing was lost — which is exactly why nobody noticed.
- A test wrote fake tasks into the real daily log for two weeks while four change records called it a "pre-existing failure." Now a test that touches the real vault fails by name, and a known red is treated as red.
- The system confirmed task completions that had never written anything. Receipts now come from the write result itself; ambiguity refuses instead of guessing.
- A plugin method named `load()` silently overrode the host app's own lifecycle hook. The build and smoke tests passed; only a live runtime check on the server caught it.
- The cloud storage filled, and for three days edits made on the workstation silently never reached the server or the phone — agents now check the quota first whenever another machine looks stale.

## By the numbers

All live counts from the real system, September 23, 2026:

**The record**
- **935** changelog entries — every ship, logged by the agent that shipped it
- **538** Dev Dashboard cards: **210** reviewed, **52** *lived* (proven by seven-plus days of real use), **119** shipped awaiting review, **50** honestly killed (not-sold or rejected)
- **110** session debriefs · **205** timeline entries across **73** narrative arcs

**The build**
- **24** plugins in one monorepo, from **~59,000** lines of agent-written source — **23** of them on the phone
- **9** shared agent skills, one store, read live by every agent
- **679** routing-contract checks across **31** channels, replayed before every release
- **2** public plugin releases and this showcase — the only public surfaces, by design, each behind a history-wide privacy gate

**The life inside it**
- **~19,000** files in the vault (about 9,000 of them Markdown notes) · **244** daily logs
- **3,168** captured media items as native notes
- **197** people records · **61** projects under management

**The runtime**
- **35** scheduled jobs on the home server, each with a heartbeat — plus a second-machine watcher and an external dead-man's switch watching the watchers
- **2** machines · **N** interchangeable agents · **1** source of truth
- One AI budget governor: **$10/month** with a hard stop — the entire assistant layer runs inside it, and un-costed calls are estimated so the cap can't be blinded

---

*Distilled from the system's own changelog and narrative timeline, updated September 2026.*
