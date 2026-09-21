# F1 — Prototype Fund (funding)

**To:** `info@prototypefund.de`
**Apply at:** <https://bewerben.prototypefund.de/>
**Window:** 1 October – 30 November 2026
**Tier:** E — funding. **This is the nearest hard deadline in the whole workspace.**

> Why this one first among funders: public-interest open-source software, built by an
> independent developer, with no business model required. Anspruch is close to a textbook
> fit. The email below is not the application — it is a short eligibility question sent
> *before* the window opens, so that the application itself is not the first contact.

## Blocker to clear before applying

**The repository has no licence.** `README.md` says "Not yet chosen." The Prototype Fund
funds open-source software; an unlicensed repository is legally not open source, and this
will sink an otherwise strong application. Pick a licence — AGPL-3.0 if you want
derivatives kept open, MIT if you want the widest adoption — and commit it first.

## What the application should lead with

Not the six languages, and not the accessibility work. Lead with **the adaptive
termination proof**: sixty-four questions reduced to twelve–twenty, with the reduction
shown to be sound rather than approximate, and tests that compute the score both ways and
assert one number. That is a genuine technical contribution, it is unusual, and it is what
a technically literate jury will respond to. The languages and the WCAG AAA work are the
evidence that the project takes its users seriously — they are the second paragraph, not
the first.

---

**Betreff:** Frage zur Förderfähigkeit — Open-Source-Werkzeug für Pflegeleistungen

Sehr geehrtes Prototype-Fund-Team,

ich beabsichtige, mich in der kommenden Runde (1. Oktober bis 30. November 2026) zu
bewerben, und habe vorab eine kurze Frage zur Förderfähigkeit.

Das Projekt heißt **Anspruch** und ist bereits als lauffähige erste Version veröffentlicht:

- Anwendung: <https://solution-for-germany.vercel.app>
- Quellcode: <https://github.com/9117KET/solution-for-germany>

**Das Problem:** Pflegeleistungen nach SGB XI werden nicht automatisch gezahlt, sondern
müssen einzeln beantragt werden. Bereits bewilligtes Geld wird regelmäßig nicht abgerufen.
Betroffen sind überproportional Haushalte, die die Anträge in einer Zweitsprache
bearbeiten, sowie sehr alte und erschöpfte Menschen.

**Die Lösung:** Eine Anwendung, die die Rechenlogik des Neuen Begutachtungsassessments
nachbildet, den voraussichtlichen Pflegegrad schätzt, den Anspruch gegen das tatsächlich
Bezogene stellt und die nächsten Schritte mit Rechtsgrundlage ausgibt. Sie läuft
vollständig im Browser; es gibt kein Konto, keinen Server und keine Analyse-Werkzeuge.
Getippte und angetippte Antworten verlassen das Gerät nicht; bei gesprochener Antwort
werten Chrome und Edge die Tonaufnahme auf Servern ihres Herstellers aus, was die
Datenschutzerklärung ausdrücklich nennt. Der Code steht unter der AGPL-3.0.

**Der technische Kern**, den ich weiterentwickeln möchte: Das Instrument umfasst
vierundsechzig Kriterien. Die Anwendung stellt typischerweise zwölf bis zwanzig Fragen —
und zwar nachweislich verlustfrei. Für jede unbeantwortete Frage wird das Ergebnis zweimal
gerechnet, einmal unter der günstigsten und einmal unter der ungünstigsten Annahme. Das
schließt den Pflegegrad in eine Schranke ein. Stimmen beide Schranken überein, können die
übrigen Fragen das Ergebnis beweisbar nicht mehr verändern, und die Befragung endet. Das
ist zulässig, weil die Bewertung in jedem Modul monoton ist. Wo die Schranken
auseinanderfallen, wird eine Spanne ausgegeben — nie der Mittelwert.

**Meine Fragen:**

1. Ist ein Projekt förderfähig, von dem bereits eine lauffähige Version veröffentlicht
   ist? Die geplante Arbeit betrifft die Absicherung und Erweiterung, nicht den
   Erstaufbau.
2. Ich bin Einzelentwickler mit Wohnsitz in Bremen. Gibt es Anforderungen an den
   Aufenthaltstitel, die ich vorab prüfen sollte?

Über einen kurzen Hinweis wäre ich dankbar, damit die Bewerbung nicht der erste Kontakt
ist.

Mit freundlichen Grüßen
Kinlo Ephriam Tangiri
Bremen · +49 176 27522943 · kinlotangiri@gmail.com
