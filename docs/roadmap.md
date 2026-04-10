# Roadmap — Where the Program Actually Is, What Opens Next, and What Must Be Earned First

> **KR note**  
> 이 문서는 Sal-Meter / CAIS / CCF kernel program의 현재 위치와  
> 다음 단계가 열리는 순서를  
> 과장 없이 구조적으로 보여주기 위한 문서입니다.
>
> This page is not a hype timeline.  
> It is a stage-order document.  
> It explains where the program actually is now, what must be completed before the next stage opens, and why broader opening remains downstream of kernel stabilization and lock review.  
> It is an operational orientation document, not a canonical authority document.

---

## Related Reading

**Read alongside this page:**

- [For PIs and Lab Leads](./for-pis-and-lab-leads.md)
- [Expected Reactions from PIs and Researchers](./expected-reactions-from-pis-and-researchers.md)
- [Where Help Is Most Needed](./where-help-is-most-needed.md)
- [What a Good Contribution Looks Like](./what-a-good-contribution-looks-like.md)
- [FAQ](./faq.md)
- [Authority Boundary](./authority-boundary.md)
- [Public Claims Guide](./public-claims-guide.md)
- [PI Quick Decision Pack](./PI_Quick_Decision_Pack.md)
- [Document Map](./document-map.md)

---

## 1. Why This Page Exists

A frontier program becomes misleading when people confuse:

- architecture with current status
- public visibility with real progress
- future opening with present opening
- ambition with earned stage transition

This page exists to prevent that confusion.

Its job is simple:

**to show the actual execution order of the current Sal-Meter kernel program, and to clarify what must be earned before the next door opens.**

This is not a generic timeline.
It is a stage-gated roadmap.

---

## 2. The Core Reading Rule

The roadmap should be read through one rule:

**the program moves forward only when the kernel becomes harder to fake, more stable to test, and more bounded to interpret.**

Movement does not mean:

- louder visibility
- more public excitement
- more speculative applications
- broader conceptual discussion
- more polished helper materials

Movement means:

- interface reality becomes clearer
- repeatability becomes stronger
- drift becomes more controlled
- leak becomes more visible or more constrained
- state-separability becomes more honest
- evidence survives tighter pressure
- stage language remains accurate

That is how this roadmap should be read.

---

## 3. The Current Public Execution Order

The current public execution order is:

**External Layer-0 → SICS Internal Phase 0 → Phase 1 → Phase 2a → Phase 2b → LOCK 1 / LOCK 2 review → post-lock SDK / broader opening**

This order is the correct present helper-level reading of the program.

It means the project is not being approached as:

- broad public rollout first
- open competition first
- consumer product first
- public app layer first
- large institutional deployment first

It is being approached as:

- kernel-first
- evidence-first
- lock-first
- internal stabilization before broad opening

---

## 4. Where the Program Actually Is Now

The current stage is:

**targeted External Layer-0 feasibility support + SICS internal Phase 0–2b kernel stabilization**

That means the project is currently centered on two simultaneous burdens:

### A. External Layer-0
A narrow chemistry-first feasibility burden focused on whether the iodine redox / thiol interface behaves in a way worth carrying further.

### B. Internal kernel program
A tightly controlled internal build path focused on making the kernel:

- reproducible
- bounded
- leak-aware
- protocol-disciplined
- transferable enough to survive later lock review

This is the real present.

It is not broad public opening.

---

## 5. What Is Not Active Right Now

The following are **not** the current priority stage:

- broad public open competition
- generalized external build race
- wide consumer device rollout
- mass public participation
- public SDK release
- open-ended commercialization
- broad external validation lanes
- large narrative expansion detached from kernel progress

Those belong later.

The current burden is still kernel stabilization.

---

## 6. External Layer-0 — What It Is For

External Layer-0 exists to answer an early, bounded question:

**does the chemistry-first interface burden deserve to be carried deeper?**

This stage is not about proving the whole stack.

It is about feasibility at the signal-interface boundary.

Typical Layer-0 work may include:

- iodine redox baseline behavior
- thiol / GSH-GSSG interaction mapping
- electrochemical feasibility checks
- early perturbation sensitivity
- stability and drift observation
- matrix compatibility exploration
- non-therapeutic signal-interface characterization

This stage is valuable because it prevents the program from pretending that interface reality can simply be assumed.

If Layer-0 fails cleanly, that is still useful.
It narrows the path honestly.

---

## 7. SICS Internal Phase 0 — G-Only Gate

Internal Phase 0 is the first internal kernel gate.

Its role is to test whether the G-axis can produce meaningful state separation under disciplined, fixed conditions.

At this stage, the burden is not “full consciousness measurement.”

The burden is narrower:

- can G-only measurement produce a real separation signal?
- can baseline logic be fixed?
- can GGI directionality remain consistent?
- can the session structure be stabilized?
- can SOP-level discipline be locked early?

The helper-level gate language for this stage is clear:

- at least one state-pair should show separability
- baseline / GGI / SOP logic must be fixed tightly enough to carry forward
- the signal must survive repeated pressure better than pure narrative optimism

This is the first real internal doorway.

---

## 8. SICS Internal Phase 1 — I-Only Reproducibility

Phase 1 turns to the iodine channel.

Its role is to establish whether the I-channel can be made reproducible enough to become a disciplined part of the kernel rather than a decorative idea.

The focus here includes:

- I₃⁻ target handling
- I-channel-only reproducibility
- coating / storage / measurement stability
- standard-curve discipline
- low-loss protocol execution
- data completeness
- fixed one-page operational logic where possible

The point is not elegance.

The point is reproducibility.

Phase 1 matters because a kernel cannot claim seriousness if one of its core channels remains conceptually attractive but operationally unstable.

---

## 9. SICS Internal Phase 2a — Twin Mini-Cell Leak and Cross-Talk Control

Phase 2a is where coexistence becomes real or collapses.

This phase asks whether the channels can live together without cheating.

Its burden includes:

- Twin Mini-Cell structure
- I/G separation
- cross-talk testing
- leak detection
- repeated cartridge comparison
- bidirectional isolation stress

This is one of the most important honesty gates in the whole roadmap.

A beautiful dual-channel concept means little if the channels contaminate one another and preprocessing hides the failure.

Phase 2a is where the architecture must prove that coexistence is not illusion.

---

## 10. SICS Internal Phase 2b — Human Pilot and Kernel Completion

Phase 2b is the internal human pilot stage.

At this stage, the program tests whether the kernel survives controlled human-session conditions strongly enough to count as an internally completed kernel candidate.

The point is not wide human deployment.

The point is whether the kernel, under bounded pilot conditions, can support:

- G + I same-session operation
- repeated state-module differentiation
- continued leak control
- reproducible packaging
- cleaner evidence integrity
- a coherent internal handoff into lock review

This is the last major internal stage before the lock gates decide whether broader opening is justified.

---

## 11. LOCK 1 — Interface Exists

LOCK 1 asks the hardest early structural question:

**does the interface actually exist as an experimentally defensible kernel?**

In the current helper framing, LOCK 1 is tied to internal Phase 0–2b completion and includes core gate conditions such as:

- meaningful state separation
- Twin structure leak / cross-talk remaining within fixed tolerance
- kernel-level protocol integrity surviving repeated review

Representative threshold language currently used in the helper structure includes:

- state separation around or above the program gate line
- Twin leak / cross-talk control at or below the fixed tolerance line

If LOCK 1 fails, broader opening should not be treated as meaningful.

Because then the interface itself has not yet earned the right to scale.

---

## 12. LOCK 2 — Interface Matters

LOCK 2 asks a different question.

Not merely:

**does the interface exist?**

But:

**does the interface matter enough, under real use logic, to justify broader external build and downstream integration?**

This stage is about practical significance rather than mere existence.

Typical LOCK 2 logic may involve questions such as:

- does the signal remain meaningfully usable?
- does it improve real downstream handling?
- does it support coherent interpretation rather than just raw detectability?
- does it survive context closer to application logic?
- does it justify SDK / broader external release?

If LOCK 1 is existence,
LOCK 2 is meaningfulness under more realistic downstream pressure.

Both matter.

---

## 13. The “1 Switch” — What Changes Only After the Locks

The switch is not a cosmetic milestone.

It marks a change of regime.

Before the locks, the program is:

- kernel-first
- internal-first
- evidence-protective
- pre-opening
- tightly bounded

After the locks, the program can begin to open different kinds of external surface.

That may include, in later stages:

- broader external validation structures
- replication-ready submission packs
- SDK-facing outputs
- broader builder participation
- wider app / form-factor experimentation
- post-kernel commercialization pathways

The switch is therefore not “more hype.”
It is the transition from **kernel proving** to **controlled external expansion**.

That transition must be earned.

---

## 14. What Comes After Successful Lock Review

Only after successful lock review does broader opening become structurally defensible.

Post-lock future lanes may include:

- external Phase 0 validation lanes
- broader replication packages
- submission-template standardization
- SDK-related expansion
- wider device-form experimentation
- non-exclusive build ecosystems
- broader operational or product-facing pathways

But these belong to the post-lock environment.

They should not be spoken of as though they define the present stage.

That is the mistake this roadmap exists to prevent.

---

## 15. What the Roadmap Is Protecting Against

This roadmap protects against five common distortions:

### 1. Future-stage inflation
Speaking as if post-lock opening were already present.

### 2. Public-opening confusion
Treating the current program as broadly open when it is still internal-first.

### 3. Architecture-equals-proof confusion
Assuming that because the roadmap is coherent, the kernel has already survived the gates.

### 4. Lock minimization
Treating LOCK 1 / LOCK 2 as ceremonial rather than structural.

### 5. Narrative substitution
Using future ambition to cover present evidentiary incompleteness.

The roadmap exists to keep sequence honest.

---

## 16. How a Serious PI Should Read the Roadmap

A serious PI should not read this roadmap as a promise of linear success.

It should be read as a discipline map.

The right questions are:

- where exactly is the current burden?
- what has already been earned?
- what remains unearned?
- what gate would my lab actually help de-risk?
- what would failure at this stage still teach the field?
- what later opening is being withheld on purpose until the kernel deserves it?

That is how a mature reader uses a roadmap.

---

## 17. How a Contributor Should Use This Roadmap

A contributor should use the roadmap to avoid false self-placement.

Before offering help, the contributor should ask:

- are we relevant to Layer-0, Phase 0, Phase 1, Phase 2a, or Phase 2b?
- are we trying to contribute to the kernel, or are we accidentally jumping to a post-lock surface too early?
- can our work reduce one real uncertainty at the correct stage?
- are we speaking publicly as if later stages are already open?

The roadmap is not merely informational.

It is a stage-discipline tool.

---

## 18. What This Roadmap Does Not Mean

This roadmap does **not** mean:

- that success is guaranteed
- that every stage will pass smoothly
- that the public competition is active now
- that broader opening has already been earned
- that helper materials create canonical authority
- that each phase automatically validates the entire architecture
- that future implications are already implemented

It means only this:

the program has a current order,
and the order is intentionally designed to keep the kernel from being released into narrative inflation too early.

---

## 19. Why the Roadmap Is Structured This Way

Because a project like this fails fastest when it scales before it stabilizes.

If broader opening comes too early:

- naming drifts
- claims outrun evidence
- weak modules get hidden by visibility
- readers confuse participation with validation
- helper surfaces get mistaken for proof
- the kernel loses the chance to become clean

The roadmap is therefore protective by design.

It is not slow for the sake of slowness.

It is sequenced for the sake of structural survival.

---

## 20. One-Line Summary

The current roadmap is internal-first and lock-gated by design: External Layer-0, then SICS internal Phase 0–2b kernel stabilization, then LOCK 1 / LOCK 2 review, and only after that broader opening.

---

## 21. Final Position

A real roadmap is not a dream list.

It is the order in which reality is allowed to answer.

This roadmap says:

first show that the interface is real,
then show that it matters,
then open the doors that depend on those truths.

Not before.

That sequence is not caution alone.

It is how a fragile kernel earns the right to become a future platform.

---

## Canonical Identity

**Origin Architect:** Jinho Lee, MD  
**ORCID:** https://orcid.org/0009-0005-3809-4588

**Affiliation:** Salpida Foundation / Salpida Institute of Consciousness Science (SICS)  
**Primary public hub:** https://salpida.foundation  
**Repository:** https://github.com/salpida-foundation/sal-meter-kernel-program  
**Canonical index layer:** https://github.com/salpida-foundation/salpida-canonical

---

## Boundary Reminder

This page is an operational orientation document.

It does **not** define canonical authority.  
It does **not** grant compliance status.  
It does **not** certify any system.  
It does **not** authorize naming rights.  
It does **not** convert repository visibility into proof.

For binding meaning, boundaries, naming, compliance, and interpretive control, follow the DOI-registered canonical layer.
