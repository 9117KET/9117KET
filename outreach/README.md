# Anspruch — Outreach Workspace

Partnership and funding outreach for **Anspruch**
(<https://solution-for-germany.vercel.app> · <https://github.com/9117KET/solution-for-germany>).

Owner: Kinlo Ephriam Tangiri · Bremen

---

## What is being offered, in one paragraph

Anspruch estimates the *Pflegegrad* a *Begutachtung* would likely arrive at, compares
the resulting entitlement against what a household already receives, and lists what to
do about the difference, in order, with the statutory basis for each step. It asks
twelve to twenty questions instead of the instrument's sixty-four, and the reduction is
provable rather than approximate. It runs entirely in the browser: no account, no
server, no analytics, and answers never leave the device. It ends in a PDF the family
can carry to the Pflegekasse.

## The three things that open doors

Lead with these, in this order. They are what make an institution take a cold email
from an unaffiliated developer seriously.

1. **No data leaves the device.** No server, no account, no analytics, no processor
   agreement, no *Auftragsverarbeitungsvertrag* to negotiate. For a Pflegestützpunkt or
   a Wohlfahrtsverband this removes the single biggest obstacle to trying something new.
   Say this early and say it plainly.
2. **Every figure is traceable.** Each euro amount and threshold carries its statute
   and the date a human last checked it (`lib/rules/sources.ts`). Conservative by
   construction: one-off grants never enter the monthly headline, Pflegegeld and
   Pflegesachleistung are counted once rather than summed. A figure that cannot be
   traced is not shown.
3. **It does not oversell itself.** It says it is an estimate, not an assessment, and
   it points at free statutory advice under § 7a SGB XI. Partial intakes produce a
   *range*, never a confident wrong number. This is the sentence that separates it from
   the lead-generation tools these organisations get pitched every month.

## The ask, per tier

Do not ask for a partnership in the abstract. Ask for one specific, small,
cheap-to-say-yes-to thing:

| Tier | Who | The ask |
| --- | --- | --- |
| A | Bremen advice points, Wohlfahrtsverbände | 30 minutes with one adviser, then 5–10 families |
| B | National advocacy & quality bodies | A read of the method, and a named critic |
| C | Payers, ministries, MD | A conversation about where it could sit |
| D | Migrant & language organisations | Native-speaker review of the four unreviewed languages |
| E | Funders | Eligibility check first, application second |

## Sequencing — do not send everything at once

**Week 1 — Bremen, local, warm.** Pflegestützpunkt Land Bremen, Der Paritätische Bremen,
AWO Bremen, Diakonie Bremen. These are reachable, local, and a yes here produces the
pilot evidence every later email needs.

**Week 2 — the language gap.** Migrant organisations and DeMigranz. The four unreviewed
languages are the project's most honest weakness; asking for help with it is a better
opening than asking for a pilot, and it produces a real collaborator.

**Week 3 — national advocacy.** wir pflegen, BIVA, BAGSO, Deutsche Alzheimer
Gesellschaft, ZQP, Deutsche Stiftung Patientenschutz. Now you can write "a pilot is
running in Bremen with N families", which changes the email entirely.

**Week 4+ — payers and funders.** AOK Bremen, compass, the Senatorin's Referat 31,
GKV-Spitzenverband. Starthaus Bremen can be booked at any point — it is free and costs
nothing but an hour.

## Before you send anything

- [ ] **Verify the "29 in 100" figure.** The README states that roughly 29 in 100
      re-checked assessment reports are corrected. Find and pin the primary source (MD
      Bund / MDS *Pflegebegutachtung* statistics) before putting it in an email to an
      institution that will know the number better than you do. If it cannot be pinned,
      drop it — the rest of the case stands without it.
- [ ] **Have a German native speaker read the German drafts.** These are written to be
      correct and formal, but a cold email to a *Geschäftsführung* is the wrong place to
      discover a stiff phrasing.
- [ ] **Decide the licence.** The repo says "Not yet chosen." Every funder in Tier E and
      several partners in Tier A/B will ask. Prototype Fund *requires* an OSI licence.
      Pick one (AGPL-3.0 or MIT) before sending funder emails.
- [ ] **Add an Impressum and a privacy note to the deployed site.** A German
      organisation will look for both before replying. Their absence reads as unserious;
      for a publicly reachable site aimed at German users it is also a legal
      expectation. This is the highest-value hour of work before outreach starts.
- [ ] **Set up a project email address.** Sending from a personal Gmail is survivable but
      weaker. Anything at a project domain lifts the reply rate.

## Files

| File | What it holds |
| --- | --- |
| `CONTACTS.md` | The directory: organisations, addresses, why each one, what to ask |
| `TRACKER.md` | Send/reply log — fill in as you go |
| `emails/` | Ready-to-send drafts, one per archetype |

## A note on how these drafts are written

Short. German institutions do not read long cold emails, and length reads as a sales
pitch. Every draft states the problem in two sentences, the solution in three, the
honest limitation in one, and the ask in one. The link goes near the top, not buried at
the bottom — the deployed app is the strongest argument in the email and it should be
clickable within the first screen.

The German drafts use *Sie* throughout and avoid English loanwords where a German term
exists. Where a draft addresses a named person, the name is marked `[...]` if it was
not verified — **check it on the organisation's own site before sending.** Getting a
name wrong in a first contact is worse than using the general address.
