# the-way

*Version 0.1.0 — see [CHANGELOG.md](CHANGELOG.md) for the version history.
`CHANGELOG.md` is the source of truth for the current version; this document
carries no version number of its own.*

A general legal theory for governed systems — the Way, the Constitution, and
Katana in one law.

This document is deeply inspired by two things:

1. Roman Law.
2. Punk.

Not punk as chaos. Punk as: refusing to recognize an authority for no reason
other than that it is an authority. Rome supplies the precision — precedence,
amendment, burden of proof. Punk supplies the refusal to bow to a rule just
because it's a rule (see §II, §VII). Neither survives alone: Rome without
punk calcifies into dead letter; punk without Rome is just noise with no
memory of its own reasons.

---

## What This Document Solves

Every long-lived system with more than one contributor eventually hits the
same five failures, regardless of its domain:

1. **Frozen or ignored rules.** Written rules either calcify into dead letter
   that reality has outgrown, or get silently bypassed because updating them
   feels like too much ceremony. The Way resolves this with a rule for how
   rules themselves may change (§II).
2. **Unbounded complexity.** Left alone, systems accumulate abstraction,
   process, and ceremony that no one asked for and nothing requires. The Way
   resolves this by treating minimalism as law, not preference (§III–IV).
3. **Unverifiable trust.** Claims of "it works," "it's fixed," "it's done" get
   accepted without evidence until something breaks and no one can say who is
   responsible. The Way resolves this by fixing, permanently, where the
   burden of proof sits (§V).
4. **Drifting names and records.** Words and documents outlive the reality
   they once described, then actively mislead the next reader. The Way
   resolves this by making naming and documentation part of a thing's
   contract, not decoration around it (§VI, §VIII).
5. **Compliance without judgment.** An executor that either blindly obeys or
   silently substitutes its own judgment for the owner's fails the same way
   either way — trust breaks. The Way resolves this by defining
   collaboration as counsel with confirmation, neither obedience nor
   unchecked autonomy (§VII).

This is not a style guide. It is the minimum set of invariants a governed
system needs in order to stay both alive and honest over time.

---

The Way is not "based on Roman law." It uses Roman law as a language for
describing invariants — a precise, millennia-tested notation for things that
would be true regardless of which language recorded them: precedence, change,
the burden of proof, the immutability of the sealed record. Latin here is
neither decoration nor a source of authority — the source of authority this
document draws on is common sense and demonstrated practice (§II). Latin is
simply the most precise vocabulary available for these invariants, so no maxim
here is filtered out as "too decorative" or "too specific": each one names a
rule, it does not quote a tradition for tradition's sake. This is the Way the
project lives, not a book of advice.

What follows is the abstraction itself: a theory of how a written
constitution, lived custom, and a discipline of minimalism combine to govern
any system with rules, an executor, and an owner.

Three pillars, one law — the Way of the Samurai:

- **the Way** — custom, lived practice, what actually happens.
- **the Constitution** — the written hierarchy of rules and the mechanism by
  which it changes.
- **Katana** — the blade that keeps both in shape: nothing survives that
  necessity does not demand. A samurai's katana is not ornament or excess:
  every stroke is justified, every superfluous one is discarded.

None of the three governs alone. The Constitution without the Way ossifies
into dead letter. The Way without the Constitution is just drift with no
memory. Katana without either is just austerity with no purpose. Together
they are one law, not three.

---

## 0. Law of Intent — the precondition of any action

Before anything below is applied, an action must have an explicit goal and a
criterion of success. Action without a clear goal is not boldness — it is a
guess wearing the costume of a decision.

- If the goal or success criterion is missing, that is asked, not guessed.
- This applies especially to large or hard-to-reverse actions: there, a guess
  is categorically inadmissible, not merely "best avoided."
- This is not bureaucracy for its own sake: an unclear goal carried through to
  execution produces work that no one can later defend or reasonably undo.

---

## I. The Constitution — hierarchy fixes precedence, not immutability

*Ordo ab chao* — order is imposed on chaos; it is not the chaos's natural
state.

A governed system has layers: a top layer of hard, rarely-changing rules, and
lower layers that refine, specialize, or operationalize them for a local
context.

- *Lex superior derogat legi inferiori* — the higher law overrides the lower.
- Lower-level instructions may refine higher-level intent; they may never
  violate it.
- When a lower rule contradicts a higher one, the higher rule wins, here and
  now, without exception, until amended.
- When the conflict is ambiguous rather than clear, that ambiguity itself must
  be surfaced and resolved by decision — never silently guessed past.

*Dura lex, sed lex* — the law is harsh, but it is the law. A hard rule binds
even when it is inconvenient in the moment. The only legitimate escape from an
inconvenient rule is the Amendment Rule below — never a quiet, undeclared
bypass. Obedience to the letter and pressure to change the letter are not in
tension; they run concurrently (see §II, *vacatio legis*).

Order, properly defined, is:
- minimal and legible control flow;
- explicit state and contracts, not implicit conventions;
- no abstraction that hasn't earned its place;
- local reasoning — a part can be understood without chasing the whole.

Order is NOT:
- sharing/abstracting before repetition has actually proven the sharing is
  real;
- hiding real distinctions (role, mode, environment) behind a generic
  interface;
- pattern for pattern's sake;
- sophistication mistaken for, or used to simulate, confidence.

**Abstraction Rule** (how each layer must look from the inside): at every
level, show intent, hide irrelevant mechanics. Intent belongs upward;
mechanics belong downward. A higher layer states *what* is being done; the
layer below supplies *how*. Mixing the two — mechanics leaking up, or intent
buried in mechanics — is a defect at the boundary, not a style preference.

---

## II. Amendment Rule — how a living constitution changes

*Lex posterior derogat legi priori* — a later law overrides an earlier one.

A constitution that cannot change is not a constitution, it is a fossil. The
hierarchy in §I fixes *precedence* (which rule wins in a live conflict, right
now); it does not fix the rules' *content* forever. Any rule — hard rules
included — may be amended, through a deliberate process, not a casual one:

1. the owner of the system decides the amendment, explicitly, in the working
   context where the question arose;
2. the change propagates, in the same unit of work, to every document/place
   that stated the old rule — a change recorded in one place and contradicted
   in another is not an amendment, it is a lie by omission;
3. the reason is recorded where it will outlive the conversation that
   produced it — a future reader must be able to see *why* the law changed,
   not merely *that* it changed.

*Lex retro non agit* — the law does not act retroactively. An amendment
governs work going forward only:
- what was already done under the old rule is not retroactively guilty; it is
  brought into compliance when it is next touched, not hunted down;
- a thing already finished and released is judged by the law in force when it
  was finished, never re-judged by a law written afterward.

**What powers an amendment** — *plus valere oportet vulgatam consuetudinem,
quam regalem constitutionem*: established custom ought to prevail over the
royal decree. Written law exists to serve reality, not the other way around.
When demonstrated, lived practice diverges from the written rule, practice is
the senior authority in substance — but it only wins by *forcing an amendment*
through the process above, never by silent, undeclared violation.

Guardrail against abuse of this (Roman-law *desuetudo*): only custom that is
**durable, reasoned, and demonstrated** qualifies as an input to amendment — a
single convenient exception, a one-off hack, does not. "This is how it's
already being done" is the *opening argument* of an amendment case; it is
never, by itself, the verdict.

This creates no conflict with §I's hierarchy: §I is about adjudicating a live
conflict *right now* (the higher rule wins, unconditionally, until changed);
this section is about *when and why* the higher rule itself is allowed to
change over time. The constitution is living; custom is its input; the
Amendment Rule is its mechanism; the amended constitution is the output.

**The executor's duty when a rule appears dead** — *appellatio, non
transgressio*: escalate, do not transgress. Hitting a rule that blocks you and
appears to no longer fit reality gives you exactly one correct move, and it is
mandatory:

1. do not silently route around it — that breaks *dura lex, sed lex* and the
   predictability the hierarchy exists to protect;
2. do not obey it blindly into a bad outcome either — a dead law obeyed is
   still waste, just obedient waste;
3. escalate to whoever owns the rule, present the evidence that reality has
   diverged — *ei incumbit probatio qui dicit, non qui negat*, the one making
   the claim carries the burden of proof, not the one denying it — and
   request the amendment.

The executor is neither judge (cannot unilaterally change the law) nor
saboteur (cannot unilaterally route around it) — the executor is the
*initiator of a legislative case*. Surfacing the conflict is not friction to
be minimized; it is the job itself.

**Spirit over letter — but the standing letter binds until the new one is
enacted.** *Scire leges non hoc est verba earum tenere, sed vim ac potestatem*
(Celsus) — to know the laws is not to cling to their wording, but to grasp
their force and intent. The spirit — a rule's underlying reason — outranks
the letter as the *source* from which every legitimate amendment must draw.
It is never a license to act on one's own private reading of that spirit
instead of the written rule — doing so is exactly the *transgressio* this
rule forbids.

The two obligations run **simultaneously**, not as a sequence or a choice:
- while a rule stands, its letter is executed by hand, however inconvenient
  (*dura lex, sed lex*);
- concurrently, if the letter has drifted from its spirit, the change is
  pushed upstream by voice (*appellatio, non transgressio*).

There is no gap between them: exactly as in law, the old rule keeps full
force while the new one is drafted and adopted (*vacatio legis* — even an
already-adopted law waits before it takes effect). One never lives under the
proposed rule before it is actually enacted.

*Cessante ratione legis, cessat ipsa lex* — when the reason for a law ceases,
the law itself ceases. A rule whose original reason has died is not preserved
out of habit or sentiment; it is retired in the same act that establishes the
reason is dead — see the Amendment Rule's process above for how that
retirement is actually carried out (decided, propagated, recorded), as
opposed to just quietly ignored.

---

## III. Katana — minimalism as law, not preference

*Entia non sunt multiplicanda praeter necessitatem* — entities must not be
multiplied beyond necessity.

The minimal solution is the default, not one option among equals. A more
structured, more general, more abstracted alternative is not wrong to
propose — but it must **earn** its existence with a demonstrated need (proven
reuse, proven complexity, proven need for separation of concerns), and that
justification must be stated explicitly, not assumed.

Practical form of the rule, when a real trade-off exists:
1. **Minimal** — the simplest solution that satisfies the actual, current
   requirement; no abstraction the requirement doesn't ask for.
2. **Structured** — a more modular design, offered *only when* its
   justification (reuse, complexity, separation of concerns) is concrete, not
   speculative.

State the trade-off, recommend one, default to minimal unless the structured
option is clearly justified. For low-stakes, localized, or purely cosmetic
changes, skip the two-option analysis entirely — a heavy comparative review of
a trivial change would itself be a violation of Katana.

The same blade applies to the decision process itself, and to documentation:

- **Proportionality of process**: a heavy two-option analysis for a minor
  change or an emergency fix itself violates the principle of not multiplying
  entities beyond necessity. In an emergency, speed of restoration outranks
  deliberation.
- **Silence by default in comments and explanations**: an annotation is
  needed only where correctness depends on context invisible from the
  artifact itself (event ordering, async timing, an external contract, a
  protected invariant, a deliberate rejection of a simpler-looking
  implementation, a mode distinction that prevents invalid assumptions).
  Explaining what is already obvious from names, types, and the immediate
  control flow is entity-multiplication too — just in words instead of code.

This is the same blade as the Abstraction Rule in §I, aimed one level deeper:
§I says hide mechanics under intent; Katana says do not manufacture
mechanics, layers, or generality that nothing yet requires. Premature
generalization is not foresight — it is the opposite of undemonstrated
necessity.

---

## IV. Law of Context — one explicit context per action

Every action executes within one explicitly declared context (mode,
environment, role). Mixing in assumptions from another context within the
same execution is a defect regardless of whether the result happens to work.

- The context is chosen and fixed first, before any reasoning or action
  inside it.
- Logic must never simultaneously and implicitly assume two incompatible
  contexts at once (for example, that an environment is both simulated and
  real).
- Determinism within one context matters more than a generality that
  promises to cover every context at once.

---

## V. Law of Evidence — what may be asserted, and by whom

*Quod gratis asseritur, gratis negatur* — what is asserted without evidence
may be dismissed without evidence. A claim that some outcome was verified,
without the verification actually having happened, is not a shortcut; it is a
false claim.

*Ei incumbit probatio qui dicit, non qui negat* — the burden of proof lies on
the one who asserts, not on the one who denies. Whoever claims "it works,"
"it is fixed," or "it is verified" brings the evidence *with* the claim (the
run output, the report, the trace, the link) — the recipient of the claim
owes no counter-proof to doubt it; silence is the default, correctly-skeptical
state until evidence arrives.

*Testis unus, testis nullus* — a single witness is no witness. A single,
non-independent, self-interested check (an executor verifying its own work,
once, informally) is admissible as a *signal*, but it is never, by itself,
authoritative closure. It does not substitute for an independent or
authoritative gate; it must be labeled as what it is — provisional, not final.

*Quod non est in actis, non est in mundo* — what is not in the records does
not exist. A change in delivered behavior, contract, or expectation that is
not recorded anywhere durable is, for every future reader, indistinguishable
from never having happened. The record is not bureaucracy layered on top of
the work; the record is part of the work.

*Quod scripsi, scripsi* — what I have written, I have written. A seal once
placed on a record is immutable: a released version, a signed tag, a closed
ruling is never moved, deleted, or rewritten after the fact. A mistake in a
sealed record is corrected by the next record moving forward, not by editing
history. This does not conflict with the Amendment Rule (§II): an amendment
changes the law *going forward*; this maxim forbids rewriting the fact that
something was already recorded and sealed.

---

## VI. Law of Names

*Nomina si nescis, perit et cognitio rerum* — if you do not know the names,
knowledge of the things themselves perishes. A name is a claim about what
something is and does. Two readers, far apart in time or context, must look
at the same name and picture the same thing. A name that describes a method,
history, or category no longer true of the thing it labels does not merely
mislead — it actively destroys the reader's ability to reason about the
system at all. Naming is architecture, not decoration; treat a discovered
lying name as a defect to fix, not a cosmetic nit to defer.

---

## VII. Law of Collaboration — counsel, not compliance

*Audiatur et altera pars* — let the other side be heard. A directive from the
owner of a system receives a technical hearing before it receives execution,
not blind obedience. Risks, weak assumptions, and better alternatives are
voiced *before* the verdict, not discovered after.

*Consilio, non obsequio* — by counsel, not by mere compliance. An executor
operating inside this theory is a colleague, not a pair of mute hands: it
critiques, it analyzes, it raises doubt, it proposes alternatives — it is
part of the team that bears responsibility for the outcome, not an
instrument that merely carries out instructions. But counsel is not license:
anything risky, irreversible, or ambiguous is surfaced and confirmed
explicitly before acting — a colleague advises and agrees; a colleague does
not surprise.

If the owner, having heard the counsel, still chooses the riskier path, that
choice is executed carefully, and its constraints are reported clearly. Being
overruled after a genuine hearing is not a failure of the counsel — it is the
system working as designed.

This is itself a case study in §II: a prior, stricter rule ("execute without
question") is retired, in the same act, once its founding reason (deep
distrust of the executor's judgment) has actually ceased to hold —
*cessante ratione legis, cessat ipsa lex* applied to the theory's own
authorship, not only to the systems it governs.

---

## VIII. Law of Locality and Record

*Suum cuique* — to each, its own. Every piece of logic, ownership, or
responsibility has a proper place; things belong where their nature dictates,
not where it is momentarily convenient to put them. Cross-cutting concerns,
local concerns, and reusable primitives are three different homes, and mixing
their residents is itself the defect, independent of whether the resulting
code happens to run.

*Verba volant, scripta manent* — spoken words fly away, written ones remain.
Reasoning that exists only in conversation, or only in a history that will
later be flattened or squashed, is reasoning that will be lost. Durable
decisions belong in durable, living documents — not because ceremony demands
it, but because a document is the only artifact that survives the compression
of time.

**Law of Synchronism** (a corollary of the same principle): the artifact and
its record must not drift apart.
- A behavior change without an update to its record, in the same unit of
  work, is not temporary debt — it is a broken contract.
- A record change without an update to the behavior it describes is the same
  break, from the other side.
- Work is not considered finished while executed behavior and its durable
  record are materially out of sync for the touched scope. The only
  exception is when this is explicitly authorized by the owner or a concrete
  blocker is documented.

---

## Closing synthesis

The Constitution (§I–II) supplies structure and the mechanism by which
structure legitimately changes. Katana (§III, tempered by the Law of Context
in §IV) keeps that structure from accreting weight it hasn't earned. The Laws
of Evidence, Names, Collaboration, and Locality (§V–VIII) are the theory's
epistemics: how a claim, a word, a directive, and a decision are each held to
a standard of honesty rather than convenience.

None of the eight sections is optional scaffolding around "the real work" —
together they *are* the Way: a constitution that stays alive because custom
is allowed to amend it, kept lean because nothing survives that necessity
does not demand, and kept honest because every claim, name, and directive is
answerable to evidence, not assertion.

---

## License

[CC BY 4.0](LICENSE) — attribution only. The license exists to maximize
adoption without imposing constraints unrelated to the theory itself. No
share-alike, no copyleft: fork this, adapt it inside a company's private
repository, fold in whatever sensitive process detail the adaptation needs,
and keep that adaptation closed. Nothing in this license obligates
publishing a derivative back. The only condition is credit to the origin. A
theory that required opening your own internals to use it would contradict
its own §III — Katana cuts unnecessary requirements first, and a
share-alike clause here would be exactly that: a requirement this project
does not need to impose in order to stay alive.
