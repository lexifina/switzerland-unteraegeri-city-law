# Unterägeri (city): law history in git

The municipal law of the municipality of Unterägeri (Gemeinde Unterägeri, canton of Zug, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law). The law of the canton of Zug is in [lexifina/switzerland-zug-law](https://github.com/lexifina/switzerland-zug-law); federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, exactly as the municipality publishes it.

## What this repository holds

49 acts with 61 versions so far: the Gemeindeordnung (the municipality's charter) first, then the municipality's other enactments in force (ordinances, regulations, tariffs and decisions), in the order of the systematic collection, added in parts of about 50. Agreements, concessions, directives and repealed acts are not included.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `1-1-1/` | Gemeindeordnung (SRS 1.1-1) | 1 | one version (the oldest available), 1 February 2024 |
| `1-2-1/` | Reglement Ortseingangstafeln (SRS 1.2-1) | 1 | as enacted, 1 September 2010 |
| `1-2-2/` | Benutzungsordnung Gemeindearchiv für verwaltungsexterne Personen (SRS 1.2-2) | 1 | as enacted, 1 January 2017 |
| `1-7-1-anstellungsreglement/` | Reglement über das Arbeitsverhältnis des Gemeindepersonals (SRS 1.7-1) | 1 | as enacted, 1 January 2025 |
| `2-1-1/` | Verordnung über die Gebühren im Beurkundungswesen (SRS 2.1-1) | 1 | as enacted, 1 March 2019 |
| `4-1-1/` | Verordnung Tagesfamilien (SRS 4.1-1) | 2 | as enacted, then each consolidated version: 1 January 2023 to 1 August 2026 |
| `4-1-1-1/` | Tarifordnung Tagesfamilien (SRS 4.1-1.1) | 2 | as enacted, then each consolidated version: 1 January 2023 to 1 August 2026 |
| `4-1-2/` | Verordnung Kinderkrippe Wichtelhuus (SRS 4.1-2) | 2 | as enacted, then each consolidated version: 1 August 2019 to 1 August 2026 |
| `4-1-2-1/` | Tarifordnung Kinderkrippe Wichtelhuus (SRS 4.1-2.1) | 2 | as enacted, then each consolidated version: 1 August 2019 to 1 August 2026 |
| `4-1-2-2/` | Verordnung Betreuungsgutscheine Kindertagesstätten und Tagesfamilien (SRS 4.1-2.2) | 2 | as enacted, then each consolidated version: 1 January 2018 to 1 August 2026 |
| `4-1-3-betreuungsreglement-ber/` | Reglement über die familien- und schulergänzende Kinderbetreuung (SRS 4.1-3) | 2 | as enacted, then each consolidated version: 14 December 2015 to 1 August 2026 |
| `4-1-3-1-betreuungsverordnung-bev/` | Verordnung zum Reglement über die familien- und schulergänzende Kinderbetreuung (SRS 4.1-3.1) | 1 | as enacted, 1 August 2026 |
| `4-1-3-2/` | Tarifordnung schulergänzende Betreuung (SRS 4.1-3.2) | 1 | as enacted, 1 August 2026 |
| `4-1-3-3-seb-verordnung/` | Verordnung über die schulergänzende Betreuung von Kindern (SRS 4.1-3.3) | 1 | as enacted, 1 September 2026 |
| `4-2-1/` | Schul- und Disziplinarordnung (SRS 4.2-1) | 1 | as enacted, 1 April 2017 |
| `4-2-1-1/` | Absenzenordnung und Urlaubsregelung für Schülerinnen und Schüler aller Stufen (inkl. Kindergarten) (SRS 4.2-1.1) | 1 | as enacted, 1 November 2011 |
| `4-2-2/` | Reglement über den Schulzahnarztdienst (SRS 4.2-2) | 1 | as enacted, 1 August 2021 |
| `4-2-2-1/` | Verordnung zum Reglement über den Schulzahnarzt-Dienst (SRS 4.2-2.1) | 1 | as enacted, 1 January 2022 |
| `4-3-1/` | Reglement der Musikschule Unterägeri (SRS 4.3-1) | 1 | as enacted, 1 February 2013 |
| `4-3-1-1/` | Vollziehungsverordnung zum Musikschulreglement für Musikschülerinnen und Musikschüler (SRS 4.3-1.1) | 1 | as enacted, 1 August 2013 |
| `4-3-1-2/` | Richtlinien für Schulgeldermässigungen der Musikschule (SRS 4.3-1.2) | 1 | as enacted, 1 August 2018 |
| `4-5-1/` | Richtlinien Sportlerinnen- und Sportlerehrungen und Award-Verleihung (SRS 4.5-1) | 1 | one version (the oldest available), 8 April 2024 |
| `4-7-1/` | Benutzerverordnung Bibliothek Ägerital (SRS 4.7-1) | 1 | as enacted, 1 March 2021 |
| `4-7-2/` | Benutzerverordnug Ludothek Ägerital (SRS 4.7-2) | 1 | as enacted, 1 February 2024 |
| `5-5-1/` | Feuerwehrreglement (SRS 5.5-1) | 2 | as enacted, then each consolidated version: 1 January 1997 to 1 January 2025 |
| `5-5-1-1/` | Richtlinie zum Feuerwehrreglement (SRS 5.5-1.1) | 1 | as enacted, 1 January 2025 |
| `6-6-1/` | Benutzungs- und Gebührenreglement für Räume und Anlagen (SRS 6.6-1) | 1 | as enacted, 1 November 2022 |
| `6-6-2/` | Benützungsreglement des Kultur- und Begegnungshauses «Haus am See» (SRS 6.6-2) | 1 | as enacted, 12 October 2011 |
| `6-6-4/` | Benutzungsordnung für gemeindliche Sportanlagen (SRS 6.6-4) | 2 | as enacted, then each consolidated version: 10 March 2022 to 1 February 2026 |
| `6-6-5/` | Reglement Strandbad Lido Unterägeri (SRS 6.6-5) | 2 | as enacted, then each consolidated version: 1 May 2023 to 1 May 2026 |
| `6-6-6/` | Allgemeine Nutzungsrichtlinien für die AEGERIHALLE (SRS 6.6-6) | 1 | as enacted, 30 January 2024 |
| `6-6-7/` | Allgemeine Nutzungsrichtlinien für den KULTROOM15 (SRS 6.6-7) | 1 | as enacted, 1 January 2023 |
| `6-6-8/` | Reglement Fussballplatz Chruzelen mit Clubhaus (SRS 6.6-8) | 1 | as enacted, 1 September 2026 |
| `7-1-1/` | Bauordnung (SRS 7.1-1) | 2 | as enacted, then each consolidated version: 1 January 2009 to 3 April 2025 |
| `7-1-2/` | Kosten für die Prüfung von Jauchegruben (SRS 7.1-2) | 1 | as enacted, 18 March 2020 |
| `7-1-3/` | Baubewilligungsgebühren (SRS 7.1-3) | 1 | as enacted, 1 January 2019 |
| `7-1-4-pgw/` | Verordnung preisgünstiger Wohnungsbau (SRS 7.1-4) | 2 | as enacted, then each consolidated version: 12 June 2025 to 17 December 2025 |
| `7-1-5/` | Richtlinie über die Förderung der Entsiegelung von Flächen (SRS 7.1-5) | 1 | as enacted, 1 January 2026 |
| `7-4-3-2/` | Abwasserreglement (SRS 7.4.3-2) | 1 | as enacted, 1 January 2005 |
| `7-4-3-2-1/` | Verordnung zum Abwasserreglement (SRS 7.4.3-2.1) | 1 | as enacted, 1 January 2015 |
| `7-6-1/` | Strassenreglement (SRS 7.6-1) | 1 | as enacted, 20 February 2004 |
| `7-7-1/` | Parkplatzbewirtschaftungsreglement (SRS 7.7-1) | 2 | oldest version available, then each consolidated version: 1 July 2020 to 1 January 2027 |
| `8-2-1/` | Bestattungs- und Friedhofreglement (SRS 8.2-1) | 1 | as enacted, 1 January 2012 |
| `8-2-1-1/` | Gebührenordnung zum Bestattungs- und Friedhofreglement (SRS 8.2-1.1) | 1 | as enacted, 1 January 2012 |
| `8-3-1/` | Reglement über das Halten von Hunden und die Erhebung der Hundesteuer (SRS 8.3-1) | 1 | as enacted, 1 January 2024 |
| `8-3-1-1-hundereglement/` | Verordnung zum Reglement über das Halten von Hunden und die Erhebung der Hundesteuer (SRS 8.3-1.1) | 1 | as enacted, 1 February 2024 |
| `9-3-1/` | Verordnung über die Angelfischerei im Ägerisee (SRS 9.3-1) | 1 | one version (the oldest available), 1 February 2023 |
| `9-4-1/` | Verordnung über die Beherbergungsabgabe (SRS 9.4-1) | 1 | as enacted, 1 January 2018 |
| `9-5-1-alkoholsteuer/` | Gebührenordnung für den Kleinhandel mit gebrannten Wassern (SRS 9.5-1) | 1 | as enacted, 17 January 2019 |

## Source

The SRS (systematic collection) of the municipality, published by the municipality at <https://unteraegeri.tlex.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CRS). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the municipality's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (CRS), with an e-mail address that cannot exist (`<act key>@unteraegeri.tlex.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the municipality publishes as binding. The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
