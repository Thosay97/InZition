# InCyZn — BRIEF.md

Source: client-supplied Design & Development Brief
(`InCyZn_Website_Design_&_Development_Brief.md`), treated as the interview
transcript per the skill's own allowance. Not self-authored; the founder's
words are quoted directly below rather than paraphrased.

---

## 1. The eight interview answers

**1. Vibe, in three to five words, plus references.**
"Digital surgical environment. Dark, precise, minimal, sophisticated, slightly
mysterious." Referenced against: "black surgical table + technical instrument
+ editorial design + systems thinking + premium strategy consultancy." No
existing sites named — deliberately, since naming sites is how a page ends up
looking like one.

**2. The scroll journey, section by section, in their words.**
Eleven acts, given verbatim as ACT 01 through ACT 11 in the source brief:
The Stall → The Question → The System → The Blockage → The Incision →
What We Actually Do → What We Don't Do → The Method → Who We Work With →
The Future → The Close. "Do not build a standard Hero → About → Services →
Testimonials → Team → Contact landing page. Instead, create a continuous
narrative."

**3. The energy curve.**
Quiet and controlled almost throughout, one sharp engineered release. "Motion
should be slow, controlled, precise, intentional, mechanical where
appropriate... The website should feel expensive because it knows when NOT to
move." The loudest the page ever gets is one wordless cut at Act 05.

**4. Feeling stage-by-stage, and the one moment.**
Given directly as "Feeling Curve" in the source brief (Act 1 Intrigue → Act 2
Tension → Act 3 Recognition → Act 4 Clarity → Act 5 Release → Act 6 Confidence
→ Act 7 Trust → Act 8 Action). The one moment: "one precise line/cut passes
through the blockage. The system separates... No explosion. No particle
effects. No cheesy success animation. Just: one precise movement." This is
the peak — see §3.

**5. One thing no site they've seen does.**
"The Incision": a persistent line/network system that is present the whole
page, tangles into a blockage, and is cut apart at the engineered peak — "the
website itself performs an incision," driven by ScrollCraft's scroll-progress
mechanism rather than generic parallax.

**6. Distance from premium-minimal.**
Premium-minimal, but pushed toward restraint rather than luxury: "the
website should feel expensive because it knows when NOT to move." No warmth,
no texture-as-decoration, monochrome discipline.

**7. One unbroken world, or distinct scenes?**
Distinct scenes read as one continuous journey — explicitly not a worldflight
("do not build a standard... landing page" is about section grammar, not
about wanting a single fixed 3D place). Eleven named acts each carry their
own real semantic content (headline, body copy, sometimes a reveal list),
which a worldflight's fixed-canvas-plus-waypoint-captions structure cannot
hold. This is a page of chaptered movements bound by one recurring motif
(the line), not one camera flight through one scene. See §4 for the grammar
reasoning in full.

**8. Assets on hand.**
The real logo (mark + wordmark, extracted losslessly from the client's own
files — see `assets/incyzn-logo-lockup.png` and `incyzn-mark.png`). No
photography, no footage, no product shots. The brief is explicit that this is
correct, not a gap to fill: "Prefer generated abstract visual systems over
stock photography... Do not use literal scalpels... the incision metaphor
should remain intelligent and abstract." No `KIE_AI_API_KEY` is configured in
this environment either, which only confirms the route the brief already
specifies: everything but the logo is built as line, node and typographic
system, in SVG and CSS, authored directly in the page.

---

## 2. The feeling curve

One line per act. Emotion first, cause second — the source brief's own
"Feeling Curve" section supplies the emotions; the causes are this build's.

```
01  Intrigue     Near-black stage, the mark alone, then the tagline arriving
                 slowly. A single thin line drawn by a persistent SVG rail
                 tries to travel and stutters against nothing yet named.
02  Tension       Large editorial question, heavy negative space, the line
                 still catching, now visibly irregular.
03  Recognition   Supporting copy naming the real causes of a stall, arriving
                 one at a time in a held pin — the reader recognises their
                 own situation in the list.
04  Complexity    "Before we look for someone, we look at the system." A
                 tangled node network draws itself from nothing, edges
                 arriving faster than the eye can track.
05  Clarity       The network resolves: most connections dim, one cluster
                 stays lit and identifiably snarled. "Find the constraint."
06  (held)        Diagnostic menu (Hire / Restructure / Reassign / Redefine /
                 Remove / Intervene) arriving as options, not answers —
                 confidence that the diagnosis is real rather than a hire
                 foregone.
07  Release       THE PEAK. Full-bleed, near-silent stage. The tangled
                 cluster fills the screen. One straight line sweeps through
                 it. The knot separates into two clean paths. Held, generous
                 span, nothing else happening.
08  Confidence    "Precision before placement." The four service lines
                 revealed one at a time against the now-clean line motif,
                 not as feature cards.
09  Trust         "We don't believe more is always better." A struck-through
                 cadence of refusals, plain and fast, ending on the one
                 sentence that is the real differentiator.
10  Recognition   The six-step method, drawn as the line itself advancing
                 through labelled stages — the reader watches the same line
                 from Act 01 now moving freely.
11  Intimacy      Founder-voiced situations ("We're growing faster than our
                 structure can handle") — quiet, first-person, no logos, no
                 testimonial styling.
12  Confidence    A brief, deliberately undersold note on the future network —
                 one sentence, no marketplace framing, kept small on purpose
                 so it cannot compete with the peak.
13  Resolve       The close. The line, now moving smoothly, arrives at rest.
                 "Something is stuck. Let's find out why." Two CTAs. The
                 mark and both brand lines, held.
```

No two adjacent acts share a feeling word. Act 05→06 is the one place two
quiet beats sit next to each other by design — 06 is a continuation of 05's
clarity into concrete named options, not a repeat, and it is kept short (a
flow reveal, not its own pinned act) specifically so it reads as coda rather
than as filler.

---

## 3. The peak

> The screen goes almost silent, the tangled knot fills the frame, and one
> straight line just — cuts through it. No fireworks. It just comes apart
> into two clean lines, and you realise that's the whole pitch.

Lives in **Act 07 (source Act 05, "The Incision")**. It gets the largest
`data-sc-span` on the page, the act before it (source Act 04, "The
Blockage") is quieter and slower by comparison, and the act ends on a held,
two-line statement ("ONE PRECISE INTERVENTION.") rather than fading before
the next act arrives.

---

## 4. Grammar: filmic one-shot, and why the other seven lost

**Chosen: Filmic one-shot.**
"The entire website should feel like one continuous diagnostic journey" is
the brief's own words, and filmic one-shot is defined as exactly that: "a
single linear argument with one emotional arc... the visitor should feel
carried rather than navigating." The brief's nav spec — a small wordmark plus
a handful of near-invisible links, no visible sequence, no chapter numbers —
matches this grammar's nav treatment almost exactly, and its close (pinned,
held, one CTA) matches the brief's Act 11 requirement precisely.

This grammar is the one four prior builds all reached for by default, so it
carries a burden of proof here — met on the brief's own terms rather than by
default:

- **Chaptered editorial** — rejected. Its nav is a visible folio with a
  chapter number and title; the brief explicitly forbids visible sequence
  ("do NOT... add 01/06 section counters") and asks for navigation "nearly
  invisible until needed." Its hero also bans media above the fold, but the
  brief's Act 01 hero *is* the signature line motif starting to move.
- **Live surface** — rejected outright. There is no software product to
  operate; the "system" here is a diagnostic metaphor, not a UI.
- **Continuous world (worldflight)** — rejected. It bans every section
  boundary and pinned act on the page and requires one fixed canvas the
  whole way down, with copy arriving only as waypoint captions. Eleven acts
  each carrying real paragraphs, a reveal list, and a named method step
  cannot live inside that shape without being reduced to captions, which
  would gut exactly the "continuous diagnostic journey... progressively
  becomes clearer" reading the brief asks for. It is also the grammar the
  skill itself flags as the most fragile to build, and this brief does not
  ask for travel through a physical place.
- **Typographic poster** — rejected. The line/network *is* the site's
  central visual argument; a type-only page would have nowhere to put it, and
  the brief is explicit that the visual experience should communicate the
  philosophy before the copy does.
- **Gallery / catalog** — rejected. Nothing here is a browsable range; there
  are no variants, no case studies, no objects to walk past.
- **Split stage** — rejected. Act 04's diagnostic menu (Hire / Restructure /
  Reassign...) is a list of options, not a two-sided comparison held in
  tension the whole page.
- **Rhythmic cutlist** — rejected, directly contradicted by the brief: "avoid
  bounce, excessive spring animations... constant movement, overlapping
  animation everywhere." A cutlist is built from exactly the hard, fast cuts
  this brief asks to avoid.

**Grammar bans respected:** filmic one-shot bans nothing structural, so
`pin`, `flow` + `in`, `reveal`, `kinetic`, `drift` and pointer devices are all
available. No `scrub` is used anywhere — there is no footage or generated
photography on this page by design (see §1.8), so the hero's "camera move"
is the signature line-and-network system rendered live in SVG/CSS and driven
off scroll, not a pre-rendered clip. This satisfies the grammar's hero
requirement (a full-bleed device the reader's hand visibly drives) without
requiring video.

**World:** Technical drawing (worlds.md §8), inverted for a near-black
ground — fine consistent line weight, no fills, no gradients, no 3D shading,
orthographic restraint, monochrome ink. The one non-photographic world the
skill treats as premium rather than cheap, and it is the literal medium of
this brand's own metaphor (the incision drawn as a precise technical line).

---

## 5. The signature move: "The Incision"

A single persistent SVG rail, fixed in a layer behind the content, present
from the first pixel of Act 01 to the last pixel of Act 13. It is one
continuous path element whose geometry and `stroke-dashoffset` are driven off
total document scroll progress (a page-level `--sc-doc-p`, not a single act's
`--sc-p`):

1. **Acts 01–02:** the path is a straight horizontal line, drawn in from the
   left as the reader scrolls. Small procedural jitter is added to its
   control points as Act 02 progresses, so the "stutter" is visible motion,
   not implied by copy alone.
2. **Acts 03–05:** the same path's data is swapped for a tangled multi-node
   network (`sc-network`, a hand-built SVG graph of ~14 nodes / ~22 edges).
   Edges draw in (`stroke-dashoffset`) as Act 03 advances. At Act 05 most
   edges fade to low opacity except one cluster, which stays lit and visibly
   snarled.
3. **Act 07 (the peak):** the lit cluster fills the frame. A second path — a
   single straight "incision" line — sweeps across it on a `clip-path` wipe
   keyed to the act's own `--sc-p`. The instant it completes, the tangled
   cluster's path data morphs (via a precomputed intermediate path, not a
   library) into two clean diverging lines.
4. **Acts 08–13:** the rail is back to being one line, now animated with a
   gentle, confident, non-jittering flow, carried through the method act
   (where it becomes the visual spine the six method steps attach to) and
   resolving to a short, still, horizontal segment at the close.

This is not a parameter change on a kit device: it is one bespoke element
with its own state machine, reading page-level scroll progress rather than
any single act's, and it is the only thing on the page that persists across
every act. The tell-someone sentence in §3 is this move.

---

## 6. Colour, type, tokens

Six roles, one accent, per the brief's own tokens (kept faithfully, not
"blindly copied" per its own caveat — verified against render contrast in
§8 below):

```
--sc-canvas      #050505   primary ground
--sc-canvas-deep #080808   deepest drift stop
--sc-surface     #101010   elevated surface / cards-that-aren't-cards
--sc-surface-2   #151515   second surface step
--sc-border      #242424   hairlines
--sc-ink         #F2F2F0   primary text
--sc-ink-soft    #A3A3A0   secondary text
--sc-ink-mute    #6F6F6C   muted / label text
--sc-accent      #BFC3C6   cold surgical silver
--sc-accent-2    #D8DADC   restrained accent highlight (line glints only)
--sc-accent-ink  #0A0A0A   text set on the accent
```

One accent, locked for the whole page — no exception clause needed, this page
never hard-cuts to a light ground.

Type: **DM Serif Display** (headlines — a real weight, not the thin Cormorant
end of the brief's list, closer to the reference comps' actual letterforms)
paired with **IBM Plex Sans** (body/UI — chosen over Inter specifically
because taste.md discourages Inter as a non-decision and Plex's technical
character fits "surgical/precision" rather than reading neutral). Both named
in the brief's own font lists. Display capped near 6rem outside the hero and
the peak's "ONE PRECISE INTERVENTION." moment; no gradient text, no
decorative letter-spacing beyond the wordmark (which is baked into the
supplied logo file, untouched).

---

## 7. Fingerprint gate

`scrollcraft/FINGERPRINTS.md` is empty — first build in this workspace, so
the gate has nothing to clear. Recorded here for the append after ship:
grammar filmic one-shot; nav fixed minimal bar (mark + "Approach" /
"Intervention" / "About" / one CTA); hero is a live SVG line device, not
`scrub`; act shape is 10 `data-sc-act` sections (5 `pin`, 2 `pan`, 3 `flow`)
across a measured **23.4vh** total (21045px document height at a 900px
viewport) — well above the 8–14vh generic band, deliberately: the client
brief specifies eleven named narrative beats with real paragraphs, a
diagnostic option rail, a four-item service list, a six-item refusal list
and a six-step method, and compressing that further would cut content the
brief asks for by name rather than trim genuine filler. Documented here
rather than silently overrun. Close is a pinned hold with two CTAs and the
line at rest, not a spotlight-plus-magnet close (magnet is used on the
primary CTA only, no spotlight anywhere on the page — the brief's
"controlled lighting", not a pointer-follow glow); signature move is the
persistent cross-act incision rail described in §5.

---

## 8. Authored silence

Act 01 opens on a near-empty stage on purpose — logo, nothing else, for a
beat, before the tagline arrives. Act 06 is intentionally light (a short flow
reveal, not a pinned act) so Act 07's peak has quiet in front of it. Neither
is dead scroll; both are named here so the verification pass can tell the
difference.
