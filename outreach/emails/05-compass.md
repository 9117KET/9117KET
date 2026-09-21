# 05 — compass private pflegeberatung GmbH

**To:** `info@compass-pflegeberatung.de`
**Attn:** Dr. Sibylle Angele, Geschäftsführung — verify first
**Tier:** C — payer-side advice service
**Ask:** a conversation about where a tool like this could sit
**Send:** week 4

> Why this one: compass delivers statutory care advice for the privately insured across
> the whole country, from one organisation with one management. Unlike a Pflegekasse they
> have no incentive to suppress claims — advice *is* their product. If any institutional
> body adopts this, it is likeliest to be them.

---

**Betreff:** Werkzeug zur Vorbereitung auf die Begutachtung — Anfrage nach einem Gespräch

Sehr geehrte Frau Dr. Angele,

ich wende mich an Sie, weil compass Pflegeberatung bundesweit und aus einer Hand
erbringt — und weil ich ein Werkzeug gebaut habe, das eine Beratung vorbereiten, aber
nicht ersetzen soll.

Ich bin Softwareentwickler in Bremen. Das Werkzeug schätzt den voraussichtlichen
Pflegegrad, vergleicht den daraus folgenden Anspruch mit dem, was ein Haushalt bereits
bezieht, und benennt die nächsten Schritte mit der jeweiligen Rechtsgrundlage:

**<https://solution-for-germany.vercel.app>**

Vier Eigenschaften, die aus Sicht einer Beratungsorganisation relevant sein dürften:

**Es ist auf die Beratung hin gebaut, nicht von ihr weg.** Das Ergebnis-PDF enthält neben
der Einschätzung auch **die gegebenen Antworten**. Die Begutachtung stellt dieselben
Fragen; eine Familie, die ihre Antworten mitbringt, muss sich im Termin nicht daran
erinnern, wie oft die Nächte schlecht waren. Der Nutzen liegt in der Vorbereitung, nicht
im Ersetzen des Gesprächs.

**Es entsteht kein datenschutzrechtlicher Vorgang.** Die Anwendung läuft vollständig im
Browser. Kein Konto, kein Server, keine Analyse-Werkzeuge. Die Angaben verlassen das Gerät
nicht und sind für mich zu keinem Zeitpunkt einsehbar. Ein unterbrochener Durchlauf bleibt
lokal erhalten und kann beim nächsten Besuch fortgesetzt oder gelöscht werden.

**Die Verkürzung ist belegt, nicht geschätzt.** Zwölf bis zwanzig Fragen statt
vierundsechzig. Es werden eine obere und eine untere Schranke des Ergebnisses
mitgerechnet; abgebrochen wird erst, wenn die offenen Fragen den Pflegegrad nachweislich
nicht mehr verändern können. Wo die Schranken auseinanderfallen, wird eine Spanne
ausgewiesen und die offenen Fragen werden erneut angeboten. Der Bericht nennt immer, wie
viele der vierundsechzig Fragen gestellt wurden und warum die übrigen entfallen sind.

**Die Darstellung ist bewusst konservativ.** Jeder Betrag trägt seine Rechtsgrundlage und
das Datum der letzten Prüfung. Einmalige Zuschüsse gehen nicht in die Monatssumme ein.
Pflegegeld und Pflegesachleistung werden nach § 38 SGB XI als Alternativen behandelt und
nicht addiert. Ein zu hoher Betrag wäre schädlicher als gar keiner: Die Familie erfährt es
bei der Pflegekasse und glaubt danach nichts mehr, was das Werkzeug gesagt hat.

**Mein Anliegen:** Hätten Sie oder jemand aus Ihrem Haus Interesse an einem Gespräch
darüber, ob und wo ein solches Werkzeug in einem Beratungsablauf sinnvoll sitzen könnte —
etwa als Vorbereitung vor dem Erstgespräch? Ich bin offen dafür, dass die Antwort „nirgends"
lautet; auch diese Begründung wäre für mich wertvoll.

Das Werkzeug ist kostenfrei, der Quellcode offen:
<https://github.com/9117KET/solution-for-germany>

Mit freundlichen Grüßen
Kinlo Ephriam Tangiri
Bremen · +49 176 27522943 · kinlotangiri911@gmail.com
