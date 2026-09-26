# Book-to-Content Repurposing

A folder-based ICM specialist that turns a finished or near-finished manuscript's own material into a launch/marketing content library — without inventing new claims and without ever blurring what the author actually said against what a marketing team is doing with it.

This formalizes the richest single-book evidence trail in the whole book-production gap: a real launch-ideas inventory naming ~40 already-existing launch visuals inside one manuscript, a real three-reel series proving the seam-legibility discipline in production, and a real eight-card caption set proving the production convention. It is not a theory of content repurposing — it's a repeat of what already shipped once, in full.

## What it produces

An example from a real book: four frames from a 27-second reel made for *Are You Actually Hungry?*. The spoken line is the author's own, from a yoga-teaching podcast. The first two frames carry a source chip and the line as a quote. The third is a separate beat in the brand's voice, marked as the application. The last is the end card with the standing disclaimer.

![Four frames from a reel: two showing the chip "FROM THE FEED YOUR YOGA PODCAST" over the quoted lines "You'll always be a proficient Led Zeppelin songwriter" and "We don't need to come up with new sequences", then a bridge frame reading "THE SAME IS TRUE OF DETOX", then an end card with the book question and a disclaimer](docs/example-applied-line-reel-frames.jpg)

The chip on this reel reads "FROM THE FEED YOUR YOGA PODCAST". The "A TEACHING LINE — APPLIED" chip named in [`examples.md`](examples.md) is from the earlier design draft for the same series. The rule is the same in both: the viewer can tell which words are the author's and which are the application.

## What this is

Four disciplines, run in sequence on any repurposing pass:

1. **Inventory** — catalogue what the manuscript already contains that's screenshot/clip-ready, before generating anything new. *"The book is already a marketing asset library... don't re-create them; export them."*
2. **Seam-legibility** — for material borrowed/adapted from outside the book and applied to its thesis: a mandatory chip, attribution, bridge label, and disclaimer frame, so a viewer can never mistake an applied line for something the author actually said.
3. **Honesty-gate checklist** — run on every derived claim before it ships: no lifespan claims, no unverified mechanism language, a standing disclaimer, authority framed as personal practice, never supervision.
4. **Caption/card production** — one voice note per set, one caption per card keyed to its exact filename, verbatim-embeddable by design.

Full detail per discipline: `reference/`.

## Setup

1. Load this folder into a Claude Project, or point a Claude Code session at it — `SKILL.md` lets Claude Code auto-discover and trigger it from a natural request (e.g. "repurpose this book" or "make launch cards from the manuscript"); it routes to `identity.md` → `rules.md`, then to the one `reference/` file the active situation needs.
2. Working from the raw files directly (no `SKILL.md` support): read `identity.md` → `rules.md` → `examples.md` in that order, then open only the `reference/` file for the discipline actually in play.
3. Have the finished or near-finished manuscript ready — ideally `book-ghostwriting-skill`'s Stage 5 rhythm-pass output, which flags the strongest repurposing candidates.

## First-run prompts

- *"The manuscript's done — build an asset inventory from it."*
- *"Make launch cards from chapter three."*
- *"This line is from a talk, not the book — bridge it to the book's thesis."*
- *"Run the honesty-gate check on this caption before it ships."*

## What this specialist does and doesn't do

See `identity.md` and `rules.md` for the full contract. In short: it never renders final visuals, never buys ad space, never architects the funnel around its content, never invents a claim to fill a content gap, and never ships applied/borrowed material without the seam-legibility chip — it owns the asset inventory, the seam-legibility framing, the honesty-gate pass, and the caption/card text, using a discipline that already shipped once, in full, on a real book.

## Where this fits

The book-production shelf, numbered as in the catalog. The skill in this repo is in bold.

1. [Book Ghostwriting](https://github.com/NFTYoginis/book-ghostwriting-skill)
2. [Publishing Preparation](https://github.com/NFTYoginis/publishing-preparation-skill)
3. [Title & Positioning](https://github.com/NFTYoginis/title-and-positioning-skill)
4. **Book-to-Content Repurposing** (this repo)
5. [Fact, Claim & Evidence Verification](https://github.com/NFTYoginis/fact-claim-verification-skill)
6. [Book Launch & Funnel Strategy](https://github.com/NFTYoginis/book-launch-funnel-strategy-skill)
7. [Book Format & Interior-Image Integrity](https://github.com/NFTYoginis/book-format-integrity-skill)

Previous: [Title & Positioning](https://github.com/NFTYoginis/title-and-positioning-skill) · Next: [Fact, Claim & Evidence Verification](https://github.com/NFTYoginis/fact-claim-verification-skill). All seven: [Book Production Skills](https://github.com/NFTYoginis/book-production-skills).

## License

MIT — see `LICENSE`.

---

Built by Gabe at The Quiet Ai. The Quiet Scribe Suite (early access) carries your context from one AI tool to the next: [thequietscribe.com](https://thequietscribe.com)
