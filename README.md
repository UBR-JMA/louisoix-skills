# Louisoix Skills

A suite of 28 community care advisor skills for Claude, designed for stewards and leaders of communities of care — intentional communities, large extended families, and consensus-governed groups where leadership is relational rather than hierarchical.

Named after Louisoix Leveilleur from Final Fantasy XIV — the Archon who held everything together at the cost of himself.

## Installation

Each subdirectory contains a `SKILL.md` file. To install a skill, zip the directory with a `.skill` extension and use the "Copy to your skills" button in Claude's Cowork mode, or follow your platform's skill installation instructions.

**Install `louisoix` first.** It is the master integrating skill and references all 27 subordinates. The subordinate skills only need to be installed if you want to invoke them explicitly.

## Architecture

This suite uses a GAIA/subordinate function architecture:

**`louisoix`** is the master integrator. It synthesizes across all 27 specialist frameworks implicitly — you don't need to know which subordinate is relevant. When a situation touches multiple dimensions (as community challenges almost always do), Louisoix draws on what's needed.

Subordinate skills can be explicitly invoked by saying *"Let's use the [skill name] skill"* when you want to go deep on a specific framework.

## Skills

### Master Integrator

| Skill | Description |
|-------|-------------|
| `louisoix` | Master integrating advisor — synthesizes all 27 subordinate frameworks for holistic community stewardship guidance |

### Specialist Subordinates

| Skill | Domain |
|-------|--------|
| `restorative-justice` | Circle practices, harm/accountability/repair, community witnessing |
| `trauma-informed-care` | Five principles, window of tolerance, trauma responses, vicarious trauma in stewards |
| `organizational-stewardship` | Consensus governance, decision legitimacy, institutional memory |
| `neurodivergence-care` | Autism, ADHD, AuDHD — structural support, late diagnosis, community access |
| `addiction-recovery` | Harm reduction, enabling vs. supporting, relapse, community safety |
| `mental-health-first-response` | Crisis recognition, suicidality, de-escalation, reintegration after crisis |
| `grief-transition` | Expanded grief, dual process model, communal loss, departure |
| `youth-development` | Developmental stages, adolescent governance voice, child safety, coming of age |
| `economic-precarity` | Labor justice, mutual aid, benefits navigation, class dynamics |
| `lgbtq-affirmation` | Genuine affirmation, late discovery, coming out, misgendering accountability |
| `elder-care` | Aging in community, dementia, autonomy, end-of-life, advance directives |
| `cultural-competency` | Structural racism, white fragility, class dynamics, anti-oppression |
| `legal-literacy` | Labor, tenant, immigration, criminal justice rights — not legal advice |
| `safety-planning` | DV dynamics, why leaving is dangerous, stalking, community safety |
| `somatic-approaches` | Polyvagal theory, co-regulation, nervous system states, grounding |
| `sex-positivity` | Relationship diversity, NRE, sexual shame, consent culture, kink-aware |
| `trauma-informed-child-care` | Dysregulation vs. defiance in young children, co-regulation, consistent non-parent caregiver response, generational trauma |
| `caregiver-support` | Compassion fatigue, burnout, secondary traumatic stress, role boundary collapse, sustainable caregiving |
| `conflict-prevention` | Early friction signals, NVC, communication agreements, de-escalation before harm |
| `chronic-illness-and-disability` | Dignity and agency, supporting without smothering, invisible/fluctuating illness, practical community adaptations |
| `spiritual-worldview-diversity` | Religious/secular diversity, spiritual bypassing, religious trauma, cross-worldview ritual design |
| `parenting-in-community` | Authority boundaries for non-parents, co-parenting agreements, philosophy differences, when concerns arise |
| `community-material-analysis` | Materialist structural analysis of recurring conflicts — labor distribution, resource flows, race and gender as material, external economic forces |
| `dying-and-death-accompaniment` | Active dying accompaniment, vigil rotation, home death logistics, after-death body care, protecting agency, anticipatory grief, caregiver exhaustion |
| `political-and-movement-dynamics` | Explicitly political/activist communities — ideological disagreement, state repression, security culture, informant dynamics, sectarian drift, activist burnout |
| `community-dissolution` | Existential crisis diagnosis, founding schism, major exodus, shared property and mortgage specifics, the dissolution decision, community grief |
| `land-and-ecological-stewardship` | Land tenure, Indigenous land and engagement, food production as labor, ecological governance, rewilding, animals, place loss, environmental justice |

## Design Principles

**Implicit synthesis by default.** Louisoix reads a situation and draws on whatever frameworks are relevant without requiring you to name them. You don't need to know that "my member is in freeze state" maps to trauma-informed-care — describe the situation and the skill does the diagnostic work.

**Explicit depth on request.** When you need to go deep on a specific framework — to run a circle process, to think carefully through a legal-literacy situation, to work through somatic approaches with a dysregulated member — invoke the subordinate skill explicitly.

**Proactive, not reactive.** The skills are designed to surface what the community member may need even when they haven't named it — including legal rights they don't know they have, accommodations that would help a neurodivergent member, or the danger of leaving an abusive relationship.

**Justice-oriented.** These skills are built with the understanding that community members live within systems — labor, housing, immigration, healthcare — that are often hostile to them. Good stewardship includes helping members understand their rights and navigate those systems with dignity.

**Clear separation of concerns.** Skills are designed to own their domain clearly and reference adjacent skills explicitly. The goal is that Louisoix can route correctly and that explicit invocations land in the right place.

## Evaluation

The original 16 subordinate skills were evaluated across 3 test cases each (51 total) using a with-skill vs. without-skill methodology. Results:

- Average with-skill pass rate: **99.3%**
- Average baseline (without skill): **35.1%**
- Average delta: **+64 percentage points**

The largest deltas were in mental health first response (+94pp), youth development (+100pp), and LGBTQ+ affirmation (+89pp) — domains where uninformed but well-meaning responses can cause genuine harm.

The 6 new skills (trauma-informed-child-care, caregiver-support, conflict-prevention, chronic-illness-and-disability, spiritual-worldview-diversity, parenting-in-community) are pending evaluation. See the `evals/` directory for test cases and results as they are completed.

## Community Context

This suite was built for at-risk communities of care where the stakes of getting stewardship guidance wrong are real. The skills are designed to be used by non-professionals — people who have taken on the role of steward or leader by virtue of relationship and trust, not credential.

They are not a substitute for professional mental health care, legal advice, or crisis intervention. They are a framework for thinking clearly, showing up with wisdom, and knowing when to refer.
