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

Four of these are now done — see
[solution-for-germany#4](https://github.com/9117KET/solution-for-germany/pull/4).

- [x] **Verify the "29 in 100" figure.** Done, and it survived: of 185,494 reports
      re-examined after an objection in 2022, roughly every third was changed
      (Medizinischer Dienst Bund, Nov 2023). The *wording* did not survive — the app
      said those reports "waren falsch", in all six languages, and the MD published
      that release specifically to rebut the "wrong" reading. Corrected to "changed",
      and the figure now has an entry in `sources.ts`, which it had been missing.
- [x] **Decide the licence.** AGPL-3.0. Prototype Fund is now unblocked.
- [x] **Add an Impressum and a privacy note.** `/impressum` and `/datenschutz`, linked
      from a footer on every screen. **One thing left for you:** the postal address is
      a marked placeholder, left out so no home address enters public git history.
- [x] **Qualify the privacy claim.** Speech recognition uses the Web Speech API, and
      Chrome and Edge upload the audio to the vendor. "Nothing leaves the device" was
      therefore true of tapped and typed answers only. Every draft in `emails/` now
      states this itself rather than waiting to be caught on it — in this sector,
      volunteering the limitation is worth more than the claim it qualifies.
- [ ] **Have a German native speaker read the German drafts.** Still open, and now the
      single largest risk left in this workspace.
- [x] **Fill in the Impressum address.** Set to 28757 Bremen. **Still short of § 5
      DDG**, which wants a *ladungsfähige Anschrift* — an address at which you can
      actually be served. Postcode and city alone does not meet that, and nor would a
      Postfach. A Pflegekasse's or a Verband's legal side is exactly the reader who
      checks this. Closing it means adding the street, or switching to a c/o or a
      commercial Impressum service address.
- [ ] **Redeploy**, then click both footer links on the live site before the first
      email goes out.
- [ ] **Set up a project email address.** Sending from a personal Gmail is survivable
      but weaker. Anything at a project domain lifts the reply rate.

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
