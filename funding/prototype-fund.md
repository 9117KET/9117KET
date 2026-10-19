# Prototype Fund — research brief

For Jahrgang 03. Compiled 22 September 2026, from the fund's own pages, the DLR
Projektträger, the OKF annual reports, and a direct reply from the PTF team.

**Marked throughout:** ✅ verified from more than one source · ⚠️ single source or
inferred · ❓ could not establish. The fund's own site is unreachable from this
machine, so anything marked ❓ needs one look at <https://www.prototypefund.de>.

---

## 1. What it is, and who actually runs it

| | |
| --- | --- |
| Programme | Prototype Fund (the BMFTR funding measure is called *Software-Sprint*) |
| Funder | **BMFTR** — Bundesministerium für Forschung, Technologie und Raumfahrt (the renamed BMBF) ✅ |
| Run by | **Open Knowledge Foundation Deutschland** — the team you already spoke to ✅ |
| Administered by | **DLR Projektträger** — the formal grant paperwork ✅ |
| Running since | 2016 ✅ |
| Self-description | The first low-threshold funding programme in Germany for independent developers building free and open-source software "from society, for society" ✅ |

Two organisations, two jobs. OKF judges whether your idea belongs; DLR handles the
Zuwendungsrecht once it does. Patricia is OKF. You will not meet DLR unless you get
through the jury.

## 2. The scope, which is narrower than it used to be

Since 2025 there are **two focus areas and no others**. Civic Tech and Data Literacy
were dropped. ✅

### Datensicherheit

> Software that helps protect sensitive data from loss, unauthorised access or
> manipulation — for example implementing encryption in existing projects, or
> **tools for checking data integrity**.

Their own examples: easier or more secure access to VPN encryption, **a tool for
software testing**, or another application that implements **security by design**. ✅

### Software-Infrastruktur

> Software packages or standardised implementations of protocols that are necessary
> to write and operate applications. Developers use them to save work, and they form
> the foundation of everything we use daily.

And the line that decides most applications:

> **"Such software projects are generally not aimed at end-users, but at
> programmers."** ✅

Their named examples: **Reproducible Builds** and **microG**. ✅

### Why they narrowed it — this is the part worth reading twice

Their blog gives the reasoning: civic-tech and data-literacy projects built important
things, but those solutions **"often don't require technically complicated
approaches"** and can be assembled from proven open-source libraries. Meanwhile the
funding landscape for civic tech has matured since 2016, with other funders better
suited to it. ✅

Read plainly: they now want **technically demanding, developer-facing work**. That is
the bar. An application that is socially worthy but technically ordinary is exactly
what they have decided to stop funding — and it is why Anspruch, as an end-user
application, does not fit however good it is.

## 3. Money

| | Individual | Team (up to 4) |
| --- | --- | --- |
| Main stage, 6 months | **€47,500** ✅ | €95,000 ✅ |
| Second stage, +4 months | €31,667 ⚠️ | €63,000 ⚠️ |
| Ten-month figure quoted elsewhere | €79,167 ⚠️ | €158,333 ⚠️ |

Sources disagree slightly on how the ten-month and second-stage numbers combine. The
individual six-month figure of €47,500 is consistent everywhere. The second stage is
**optional and not automatic** — it is applied for, and extends the work by four
months. ⚠️

## 4. Timeline for Jahrgang 03 — read this before planning anything

| When | What |
| --- | --- |
| **1 Oct – 30 Nov 2026** | Applications open ✅ |
| Dec 2026 – Jan 2027 | PTF team and Projektträger screen submissions; formally deficient applications are excluded; a shortlist is drawn ✅ |
| **Early Feb 2027** | Jury session. **25–30 projects** chosen and proposed to the BMFTR ✅ |
| Spring 2027 | Selected teams attend an *Antragssprechstunde* / workshop and file the formal Förderantrag with DLR's help ✅ |
| **June – November 2027** | The funding period ✅ |
| Dec 2027 – March 2028 | Optional second stage ⚠️ |

**The money arrives in June 2027.** Nine months from now. This is not runway for the
present; it is a 2027 decision being made in 2026. Plan the rest of your year as
though this does not exist, because for nine months it does not.

## 5. Who may apply

**Eligible:** individual developers, or individual members of a team. ✅

**Not eligible:** companies, Vereine, universities, non-university research
institutions, other institutions and organisations. ✅ A GmbH or an e.V. cannot hold
this grant. You apply as a person.

**Requirements, confirmed directly by the PTF team on 22 September 2026:**
residence in Germany and a German Steuer-ID. **No requirement regarding the
Aufenthaltstitel.** ✅ That question is settled — do not spend more time on it.

## 6. Licence obligations, which are stricter than "open source"

- Everything built with the funding must be published under an open-source licence. ✅
- **Dual licensing is not permitted. Open Core is not permitted.** ✅ There is no
  "community edition plus a paid tier" route here. The whole thing is open, or it is
  not funded.

Anspruch is already AGPL-3.0, which satisfies this. Any new project must be too.

## 7. Language — better news than expected

- The fund's information and support are available in **German and English**. ✅
- **The forms must be submitted in German.** ✅
- **Exception: the Vorhabenbeschreibung — the project description, the part that
  carries the actual argument — may be submitted in English** where the applicant is
  not sufficiently proficient in German. ✅

So the substance can be written in English and argued at full strength, while the
administrative fields are German. That removes the biggest worry. Do not write a
weaker German Vorhabenbeschreibung out of pride; the exception exists for exactly
this case.

## 8. What the jury weighs

Five stated criteria: ✅

1. **Relevance to the funding priorities** ← the one that killed Anspruch
2. **Degree of innovation**
3. **Technical feasibility**
4. **Societal benefit**
5. **Potential reach**

Note the ordering and note what is *not* first. Societal benefit is fourth. A project
that is socially valuable but off-scope fails at criterion one before anyone reaches
criterion four.

## 9. What the application actually asks

- An **online form** at <https://bewerben.prototypefund.de>, with questions about the
  idea, the planned scope, and the desired duration (six or ten months). ✅
- The first step asks **only a few questions about the idea**. ✅ The heavy paperwork
  comes after selection, not before — this is a genuinely low-threshold application.
- A **Vorhabenbeschreibung** is attached, following a supplied *Mustergliederung*,
  sketching the milestones to be delivered in the funding period. ✅

Patricia's own instruction, from her reply: a project with an existing codebase may
apply, but you must **clearly delimit what is newly developed in the funding period**
— it must not be "reines Weitermachen am existierenden Projekt". ✅

## 10. Reference projects

Named by the fund as examples of what Software-Infrastruktur means: ✅

- **Reproducible Builds** — lets source code be built repeatedly by different parties
  to confirm the binary really is the source. Security through verifiability.
- **microG** — a free reimplementation of Google Play Services, so Android apps can
  run without them.
- **Grandine** — an Ethereum consensus client.

Ecosystem work they have funded: osm2pgsql generalisation of OpenStreetMap data,
StreetComplete, parking-data processing. ⚠️

Older civic-tech-era projects, useful only as a contrast with what they now fund:
pretix, CitRad, Bahn-Vorhersage, Mat-o-Wahl. ⚠️

❓ **Gap:** the named projects of Jahrgang 01 and 02 — the first two cohorts under the
new two-area scope — could not be retrieved. These are the most relevant precedents
there are, because they show how the jury actually interprets the new scope. Spend
twenty minutes at <https://www.prototypefund.de/en/projects> filtered to those
cohorts before writing anything.

❓ **Gap:** applications received per cohort, and therefore the acceptance rate. Only
the funded count is public: 25–30 in Jahrgang 01, 28 in Jahrgang 02. ✅

## 11. What this means for the two candidate ideas

### A — Rules-as-code library for statutory entitlements

Fits **Software-Infrastruktur** on paper: it is a library, used by other developers.
The genuinely novel part is not the statute encoding but the **general algorithm** —
given any monotonic scoring instrument, provably compute the shortest sufficient
question sequence, with bounds that bracket every completion.

**Risk:** a jury reads "Sozialrecht library" and sees an end-user problem wearing a
library's clothes. Criterion 1 again. If this is the pitch, it must lead with the
algorithm and treat Pflege as the first of several instances, not the subject.

### B — A verifier for local-first privacy claims

Prove, in CI and at runtime, that an application handling sensitive data transmits
nothing — static detection of network sinks, a build that fails when a new one
appears, runtime enforcement, an attestable manifest.

**This hits both focus areas at once:**

| Their words | B |
| --- | --- |
| "tools for checking data integrity" | yes |
| "a tool for software testing" | yes — their own example |
| "security by design" | yes |
| "tools that support the development of other software" | yes |
| "not aimed at end-users, but at programmers" | yes — the decisive line |
| "technically complicated approaches" | yes — this is the bit civic tech lacked |

And there is a true origin story: Anspruch claimed answers never left the device while
Chrome's speech recognition was uploading the audio. That was found by accident, in a
project built carefully by someone who cared about exactly this property. Nobody
shipping health, benefits or immigration data has a tool that would have caught it.

**Recommendation: B.** A is the fallback if Patricia's answer points that way.

## 12. Before applying

- [ ] Read the Jahrgang 01 and 02 project lists — the only real evidence of how this
      jury reads the new scope.
- [ ] Wait for Patricia's answer to the follow-up sent 22 September.
- [ ] Have something running. Criterion 3 is technical feasibility, and a solo
      applicant with a working prototype answers it in a way prose cannot.
- [ ] Write the Vorhabenbeschreibung in English. The exception exists; use it.
- [ ] Do not describe a business model. Dual licensing and Open Core are disqualifying.

## Sources

- Focus areas and rationale: <https://www.prototypefund.de/en/blog/why-we-focus-on-data-security-and-software-infrastructure>
- Datensicherheit: <https://www.prototypefund.de/datensicherheit>
- Software-Infrastruktur: <https://www.prototypefund.de/blog/softwareinfrastruktur>
- How to apply: <https://www.prototypefund.de/en/application> · Jury: <https://www.prototypefund.de/en/application/jury>
- Application wiki: <https://wiki.prototypefund.de/index.php?title=Antragstellung>
- Projects: <https://www.prototypefund.de/en/projects> · Classes: <https://www.prototypefund.de/en/classes>
- Application platform: <https://bewerben.prototypefund.de/>
- DLR Projektträger: <https://projekttraeger.dlr.de/de/news/foerdermassnahme-software-sprint-prototype-fund-zeigt-wirkung>
- OKF annual reports: <https://2024.okfn.de/projekte/prototypefund/>
- Reply from the PTF team (Patricia), 22 September 2026 — eligibility, scope, and the
  rule on existing projects.
