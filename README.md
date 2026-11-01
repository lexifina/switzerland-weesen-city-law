# Weesen (city): law history in git

The municipal law of the municipality of Weesen (Gemeinde Weesen, canton of St. Gallen, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law). The law of the canton of St. Gallen is in [lexifina/switzerland-st-gallen-law](https://github.com/lexifina/switzerland-st-gallen-law); federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, exactly as the municipality publishes it.

## What this repository holds

65 acts with 66 versions so far: the Gemeindeordnung (the municipality's charter) first, then the municipality's other enactments in force (ordinances, regulations, tariffs and decisions), in the order of the systematic collection, added in parts of about 50. Agreements, concessions, directives and repealed acts are not included.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `1-1-1/` | Gemeindeordnung (SRS 1.1-1) | 1 | one version (the oldest available), 1 January 2019 |
| `1-2-1/` | Benutzungsordnung für das Gemeindearchiv Weesen (SRS 1.2-1) | 1 | as enacted, 17 August 2020 |
| `1-2-2/` | Zuständigkeits-Vereinbarung betreffend kommunaler Fachstelle für Datenschutz (SRS 1.2-2) | 1 | as enacted, 27 July 2010 |
| `1-2-3/` | Reglement für die Nutzung der elektronischen Ortseingangstafel (SRS 1.2-3) | 1 | as enacted, 3 February 2020 |
| `1-4-1/` | Reglement über die Elektronische Datenverarbeitung für die Ergebnisermittlung bei Wahlen (SRS 1.4-1) | 1 | as enacted, 1 July 1999 |
| `1-6-1/` | Geschäftsreglement Gemeinderat und Kommissionen (SRS 1.6-1) | 1 | as enacted, 1 January 2010 |
| `1-6-2/` | Reglement Kommission Vision Weesen – Riviera am Walensee (SRS 1.6-2) | 1 | as enacted, 14 June 2022 |
| `1-6-3/` | Visum- und Kompetenzregelung der Politischen Gemeinde Weesen (SRS 1.6-3) | 1 | as enacted, 1 January 2025 |
| `1-7-1/` | Personalreglement (SRS 1.7-1) | 1 | as enacted, 1 January 2020 |
| `2-1-1/` | Vereinbarung über die gemeinsame Führung des Grundbuchamtes Gaster (SRS 2.1-1) | 1 | as enacted, 1 January 2015 |
| `2-1-2/` | Reglement über die Delegation von Zuständigkeiten im Bereich des Zivilrechts (SRS 2.1-2) | 1 | as enacted, 1 March 2007 |
| `2-1-3/` | Vereinbarung über die regionale Führung eines Zivilstandskreises Gaster (SRS 2.1-3) | 1 | as enacted, 1 January 2006 |
| `4-2-1/` | Leistungsvereinbarung Schulsozialarbeit in der Primarschule Weesen (SRS 4.2-1) | 1 | as enacted, 1 August 2020 |
| `4-2-2/` | Leistungsvereinbarung Schulsozialarbeit in der Oberstufenschule Weesen-Amden (SRS 4.2-2) | 1 | as enacted, 1 August 2020 |
| `5-1-1/` | Reglement über die Gemeindepolizei (SRS 5.1-1) | 1 | as enacted, 17 June 1999 |
| `5-1-2/` | Vereinbarung betreffend Seerettungsdienst Walensee (SRS 5.1-2) | 1 | as enacted, 1 January 2017 |
| `5-1-2-1/` | Tarif für den Seerettungsdienst (SRS 5.1-2.1) | 1 | as enacted, 1 January 2009 |
| `5-3-1/` | Vereinbarung betreffend Bevölkerungsschutzorganisation Region Zürichsee-Linth (SRS 5.3-1) | 1 | as enacted, 1 July 2026 |
| `5-3-2/` | Vereinbarung über die Zivilschutzorganisation ZürichseeLinth (SRS 5.3-2) | 1 | as enacted, 1 April 2017 |
| `5-5-1/` | Feuerschutzreglement (SRS 5.5-1) | 1 | as enacted, 13 December 2021 |
| `5-5-1-1/` | Feuerwehrtarif (SRS 5.5-1.1) | 1 | one version (the oldest available), 1 January 2008 |
| `5-5-2/` | Vereinbarung über die Feuerwehr und Ölwehr in den Gebieten Fli-Amden und Betlis (SRS 5.5-2) | 1 | as enacted, 1 January 1997 |
| `5-5-3/` | Vereinbarung über die gemeinsame Nutzung der Autodrehleiter für die drei St. Galler Gemeinden Amden, Schänis und Weesen sowie die Gemeinden des Kantons Glarus (SRS 5.5-3) | 1 | as enacted, 3 July 2024 |
| `5-5-4/` | Vereinbarung über die Beschaffung eines Hilfeleistungsfahrzeuges für die Gemeinden Amden und Weesen (SRS 5.5-4) | 1 | as enacted, 10 June 2002 |
| `6-1-1/` | Reglement über die Reserve Werterhalt Finanzvermögen (SRS 6.1-1) | 1 | one version (the oldest available), 23 February 2021 |
| `6-6-1/` | Reglement über Organisation und Benützung der Mehrzweckturnhalle Weesen (SRS 6.6-1) | 1 | as enacted, 1 July 2003 |
| `6-6-1-1/` | Mehrzweckturnhalle Weesen, Gebührentarif (SRS 6.6-1.1) | 1 | as enacted, 1 January 2021 |
| `7-1-1-baur/` | Baureglement (SRS 7.1-1) | 1 | one version (the oldest available), 15 March 2013 |
| `7-1-2/` | Reglement über die Kostentragungspflicht der Nachführung der amtlichen Vermessung (SRS 7.1-2) | 1 | as enacted, 1 January 2001 |
| `7-3-1/` | Schutzverordnung (SRS 7.3-1) | 1 | one version (the oldest available), 16 January 2015 |
| `7-3-2/` | Verordnung zum Schutze der Pilze (SRS 7.3-2) | 1 | as enacted, 2 April 2001 |
| `7-3-3/` | Reglement über Luftreinhaltemassnahmen bei Feuerungen (SRS 7.3-3) | 1 | as enacted, 1 March 2022 |
| `7-3-3-1/` | Gebührentarif für die Kontrolle der Feuerungsanlagen der Gemeindefachstelle (SRS 7.3-3.1) | 1 | as enacted, 1 March 2022 |
| `7-3-4/` | Richtlinien über die Gewährung von Energie-Förderbeiträgen (SRS 7.3-4) | 1 | as enacted, 30 November 2021 |
| `7-3-5/` | Bachreglement (SRS 7.3-5) | 1 | as enacted, 1 May 2016 |
| `7-3-6/` | Reglement über Energie-Förderbeiträge (SRS 7.3-6) | 1 | as enacted, 1 August 2012 |
| `7-4-3-1/` | Wasserversorgungsreglement (SRS 7.4.3-1) | 1 | as enacted, 1 May 2016 |
| `7-4-3-1-1/` | Gebührentarif zum Wasserversorgungsreglement (SRS 7.4.3-1.1) | 1 | one version (the oldest available), 1 January 2023 |
| `7-4-3-2/` | Abwasserreglement (SRS 7.4.3-2) | 1 | as enacted, 1 October 2005 |
| `7-4-3-2-1/` | Abwasserreglement der Politischen Gemeinde Weesen Gebührentarif (SRS 7.4.3-2.1) | 1 | as enacted, 1 January 2025 |
| `7-4-3-3/` | Statuten Abwasserverband Glarnerland (SRS 7.4.3-3) | 1 | as enacted, 1 January 2022 |
| `7-4-4-1/` | Reglement über die Abfallentsorgung (SRS 7.4.4-1) | 1 | one version (the oldest available), 1 January 1995 |
| `7-4-4-1-1/` | Gebührentarif für die Abfallentsorgung (SRS 7.4.4-1.1) | 2 | oldest version available, then each consolidated version: 1 September 2017 to 1 October 2026 |
| `7-4-4-2/` | Vereinbarung über die gemeinsame Einführung und Bewirtschaftung der Kehrichtsackgebühr (SRS 7.4.4-2) | 1 | as enacted, 24 May 2006 |
| `7-7-1/` | Reglement über die Parkierung auf öffentlichem Grund (SRS 7.7-1) | 1 | as enacted, 26 April 1999 |
| `7-7-2/` | Schiffshafenverordnung (SRS 7.7-2) | 1 | one version (the oldest available), 1 January 2014 |
| `7-7-2-1/` | Gebührenordnung zur Schiffshafenverordnung (SRS 7.7-2.1) | 1 | as enacted, 1 January 2007 |
| `7-7-3/` | Weisungen für die Benützung von Grundstücken (SRS 7.7-3) | 1 | as enacted, 1 January 1991 |
| `8-2-1/` | Bestattungs- und Friedhofreglement (SRS 8.2-1) | 1 | as enacted, 7 July 2020 |
| `8-2-1-1/` | Gebührentarif zum Bestattungs- und Friedhofreglement (SRS 8.2-1.1) | 1 | as enacted, 7 July 2020 |
| `8-3-1/` | Reglement über die Hundehaltung (SRS 8.3-1) | 1 | one version (the oldest available), 1 January 2007 |
| `8-3-2/` | Vereinbarung über das Notschlachtlokal Schänis-Rufi (SRS 8.3-2) | 1 | as enacted, 1 January 2000 |
| `8-3-3/` | Vereinbarung über die Mitbenützung, Unterhalt und Betrieb der regionalen Tierkörper-Sammelstelle bei der Kläranlage Benken (SRS 8.3-3) | 1 | as enacted, 1 January 2000 |
| `8-7-1/` | Vereinbarung über die Bildung eines Zweckverbands «Soziale Dienste Linthgebiet» (SRS 8.7-1) | 1 | as enacted, 18 June 2008 |
| `8-7-2/` | Vereinbarung Zweckverband «Kindes- und Erwachsenenschutz Region Zürichsee-Linth» (SRS 8.7-2) | 1 | as enacted, 27 September 2019 |
| `8-7-3/` | Reglement über die Heimaufsicht (SRS 8.7-3) | 1 | as enacted, 1 January 2022 |
| `9-1-1/` | Reglement über den Entwicklungsfonds (SRS 9.1-1) | 1 | as enacted, 1 January 2008 |
| `9-4-1/` | Reglement über die Erhebung von Kurtaxen (SRS 9.4-1) | 1 | one version (the oldest available), 1 April 1996 |
| `9-4-1-1/` | Tarif zum Reglement über die Erhebung von Kurtaxen (SRS 9.4-1.1) | 1 | as enacted, 1 January 2026 |
| `9-5-1/` | Gastwirtschaftsreglement (SRS 9.5-1) | 1 | as enacted, 21 August 1996 |
| `9-5-1-1/` | Richtlinien zum Gastwirtschaftsreglement (SRS 9.5-1.1) | 1 | as enacted, 1 July 1996 |
| `9-5-1-2/` | Richtlinien zum Gastwirtschaftsgesetz (SRS 9.5-1.2) | 1 | as enacted, 1 July 1996 |
| `9-5-2/` | Reglement über den Ladenschluss in der Politischen Gemeinde Weesen (SRS 9.5-2) | 1 | as enacted, 10 August 1987 |
| `9-5-3/` | Reglement über das Marktwesen (SRS 9.5-3) | 1 | one version (the oldest available), 1 July 2013 |
| `9-5-3-1/` | Gebührentarif für das Marktwesen (SRS 9.5-3.1) | 1 | as enacted, 3 November 1994 |

## Source

The SRS (systematic collection) of the municipality, published by the municipality at <https://weesen.tlex.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CRS). Annexes the collection publishes only as separate PDF files are not included.

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

The author of a commit is the amending act, named by its entry in the chronological collection (CRS), with an e-mail address that cannot exist (`<act key>@weesen.tlex.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the municipality publishes as binding. The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
