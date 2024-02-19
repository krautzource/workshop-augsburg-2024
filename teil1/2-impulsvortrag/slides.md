# Barrierefreies Web und LaTeX - Freund oder Feind?

Peter Krautzberger, [krautzource](https://krautzource.com)

<small>Links/rechts scrollen, um die Slides durchzusehen.</small>

## Die Web Plattform

[_Separation of concerns_](https://en.wikipedia.org/wiki/Separation_of_concerns) (Trennung der Belange) des Web.

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) für Struktur/Semantik
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) für Präsentation/Layout
- [SVG](https://developer.mozilla.org/en-US/docs/Web/SVG) - Vektorgraphik
- Erweiterbarkeit und Interaktivität (z.B. JavaScript, Canvas, WebGL)

## Aber was ist das Web, wirklich?

Wir wissen es noch nicht. Zum Vergleich, 100 Jahre nach Gutenbergs Druckerpresse:

- Schlechtes Layout im Vergleich Kodizes
- Keine neuen inhaltlichen Formate (z.B. Roman)
- Illegale Kopien
- Einfache Pamphlete
- die Unruhen und Kriege auslösen

Inspiration: [Dao of Web Design (2000)](https://alistapart.com/article/dao/), [Responsive Web Design (2010)](https://alistapart.com/article/responsive-web-design/), [The Web's Grain (2015)](https://frankchimero.com/blog/2015/the-webs-grain/), [F-Shaped Pattern of Reading on the Web (2017)](https://www.nngroup.com/articles/f-shaped-pattern-reading-web-content/)

## Grundsätzlich barrierefrei

_Das Web ist grundsätzlich barrierefrei. Wenn Barrieren entstehen, haben wir sie selbst verschuldet._

Barrieren enstehen z.B. in den folgenden Bereichen:

👁 **Visuell**: Blindheit, niedrige oder eingeschränkte Sehleistung, eingeschränkte Sicht\
👂 **Auditiv**: Taubheit, Schwerhörigkeit, Lärm\
🖐 **Motorik**: keine Maus, langsame Reaktion, eingeschränkte Feinmotorik\
🧠 **Kognition**: Dyslexie, Dyskalkulie, Ablenkung, Gedächtnisschwierigkeiten

Inspiration: [HTML: A good basis for accessibility (MDN)](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML), [(Talk) Selfish Accessibility, Adrian Roselli](http://adrianroselli.com/2017/03/selfish-accessibility-slides-from-wordcamp-london-2017.html), [(Talk) Accessibility is usability (video)](https://www.confabevents.com/videos/accessibility-is-usability)

## Universelles Design

Ein wichtiger Überbegriff ist das [Universal Design](https://de.wikipedia.org/wiki/Universal_Design).

> “Universal design is design that’s usable by all people, to the greatest extent possible, without the need for adaptation or specialized design.”–[Ron Mace](https://en.wikipedia.org/wiki/Ronald_Mace)

<a href="https://commons.wikimedia.org/wiki/File:Curb_cut_for_wheelchair_ramp_(DSC_3616).jpg#/media/File:Curb_cut_for_wheelchair_ramp_(DSC_3616).jpg"><img src="https://upload.wikimedia.org/wikipedia/commons/b/bf/Curb_cut_for_wheelchair_ramp_%28DSC_3616%29.jpg" alt="Curb cut for wheelchair ramp (DSC 3616).jpg" height="2000" width="3000" style="height:20vw;width:30vw; display:block; margin-inline:auto" ></a>
<small><a href="//commons.wikimedia.org/wiki/User:Nick-philly" class="mw-redirect" title="User:Nick-philly">Nick-philly</a> , [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0 "Creative Commons Attribution-Share Alike 4.0")
</small>

## Barrierfrei definieren

**Barrierefreiheit ist ein auf Menschen ausgerichteter Prozess**.

Rechtlich: [European Accessibility Act](https://en.wikipedia.org/wiki/European_Accessibility_Act) / [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/03.02.01_60/en_301549v030201p.pdf) / [BITV](https://de.wikipedia.org/wiki/Barrierefreie-Informationstechnik-Verordnung).

Im Wesentlichen: [Web Content Accessibility Guidelines (WCAG) 2.2](https://www.w3.org/TR/WCAG22/)

- ~80 Success Criteria (Erfolgskriterien) eingeteilt in A, AA, AAA
- A&AA rechtlich gefordert, AAA optional/ideal
- Betreffen größtenteils Interaktion, weniger "statische" Inhalte
- Begleitend: [Understanding WCAG](https://www.w3.org/WAI/WCAG22/Understanding/), [WCAG Quick Reference](https://www.w3.org/WAI/WCAG22/quickref/)
- Einstieg: [W3C Accessibility Principles](https://www.w3.org/WAI/fundamentals/accessibility-principles/) [WebAIM WCAG Checklist](https://webaim.org/standards/wcag/checklist)

Mehr: [EAA Umsetzung in Deutschland](https://www.bitvtest.de/bitv_test/das_testverfahren_im_detail/vertiefend/european_accessibility_act.html), [WCAG 2.1 auf Deutsch](https://outline-rocks.github.io/wcag/translations/WCAG21-de/), [WebAIM Artikel (Englisch)](https://webaim.org/articles/)

## WCAGs POUR Prinzipien

WCAG Grundpfeiler: Alle Inhalte müssen

- Perceivable - Wahrnehmbar
- Operable - Bedienbar
- Understandable - Verständlich
- Robust

sein für **alle** Nutzer.

## Barrierefreiheit entwickeln

**Barrierefreiheit ist ein auf Menschen ausgerichteter Prozess**.

- Jeder Schritt ist wertvoll - vor allem der erste.
- Barrierefrei ist kein Endpunkt
- Reifegradmodelle können helfen, die Entwicklung zu bewerten und zu verbessern.

Mehr: [Fortschritt in der digitalen Barrierefreiheit messen](https://www.netz-barrierefrei.de/wordpress/fortschritt-in-der-digitalen-barrierefreiheit-messen-maturity-model-oder-reifegradmodell/), [W3C Accessibility Maturity Model](https://www.w3.org/TR/maturity-model/), [The Digital Accessibility Maturity Lifecycle](https://www.tpgi.com/the-accessibility-maturity-lifecycle/)

## LaTeX

> Und was hat das ganze mit LaTeX zu tun?

## Reicht ein PDF?

**Nein.**

- PDF ist grundsätzlich nicht barrierefrei
- PDF-UA ist deutlich schlechter nutzbar als Webinhalte ([webaim survey, 2019](https://webaim.org/projects/screenreadersurvey8/#pdf))
- PDF-UA ist schwer herstellbar, prüfbar, korrigierbar
  - insbesondere nicht für komplexe akademische Inhalte
- LaTeX Projekt zu PDF-UA kommt nicht vom Fleck

Mehr: [Wie barrierefrei sind PDFs?](https://www.netz-barrierefrei.de/wordpress/barrierefreies-publizieren/barrierefreie-pdfs/wie-barrierefrei-sind-pdfs/), [LaTeX Project News](https://www.latex-project.org/news/)

## TeXs Herz is Print

Printtraditionen bergen versteckte Problem. Eine Auswahl:

- rein visuelles Medium
- fixe Dimensionen
- komplexes Textdesign (Schriften, Größen, Orientierung)
- semantischer White Space
- Formelsatz
- Bildelemente

## TeXs Schwächen

- all of the above
- Makroprogrammiersprache
  - [Chomsky Typ 1](https://de.wikipedia.org/wiki/Chomsky-Hierarchie#Die_Hierarchie)
  - Kind seiner Zeit (z.B. Layout, Fonts, Optimierungen)
- Kulturelle Probleme (z.B. Lernverhalten, Pakete)

## TeXs Stärken

- LaTeX
  - standardisiertes Makropaket
  - Fokus: Trennung von Inhalt & Präsentation
- Programmiersprache
  - Stabilität
  - text basiert
- Kultur
  - Lingua Franca in Mathematik, Physik, Informatik etc
  - Teils im Schulbereich
  - Tradition des [Literate Programming](https://de.wikipedia.org/wiki/Literate_Programming)

## Aus LaTeX Quellen zum Web

Etliche Programme können LaTeX zu Webinhalten konvertieren. \
Eine Auswahl:

- [pandoc](https://pandoc.org/) \*
- [tex4ht / make4ht](https://tug.org/tex4ht/) \*
- [plastex](http://plastex.github.io/plastex/)
- [latexml](https://math.nist.gov/~BMiller/LaTeXML/)
- [AMS texml](https://github.com/AmerMathSoc/texml)

## Eine Frage der Balance

Separation of concerns.

- Wie nah an TeX (d.h. Print) bleiben?
  - zu weit weg vom Web: Printlayout, Barrieren
- Wie nah ans Web kommen?
  - zu weit weg von TeX: Einschränkungen bei Macros, Paketen etc.

**Werkzeuge retten uns nicht, sie können es aber schlimmer machen.**

Beispiel: [Algorithm layout](https://www.peterkrautzberger.org/0217/)

<img src="https://www.peterkrautzberger.org/assets/2020/euclid.png" alt="Euclid's Algorithmus als Textsatz mit dem algorithmicx Paket" style="margin-inline:auto">

## Eine Frage der Balance 2

Benutzbarkeit gegenüber Mächtigkeit.

Up-conversion als Chance und Risiko.

Nische in der Nische.

**Wir sind der Qualität der Tools ausgeliefert.**

## Stärken: Best Practices sind zentral

LaTeX hat gute Best Practices. \
Eine Auswahl:

- Gliederung
- Listen, Abbildungen, Tabellen, Zitate, Quellcode
- Theorem-Umgebungen (Definitionen, Theoreme, Lemmata etc)
- Querverweise (Gliederung, Formeln, Theorem, Bibliographien, Fußnoten)
- Indizes, Glossare
- erzeugte Graphiken (Diagramme etc)
- Metadaten

**Menschen lernen LaTeX einmal und nur einmal.**

## Stärken

Use the Source!

- TeX ist lesbar, weiterverwendbar
- erzeugte Graphiken (tikz, pstricks)
- externer Code (matplotlib, Sage, R, Julia)
- Formelsatz (`\frac`, `\begin{matrix}`)
  - Vor allem in Deutschland

Keep the Source!

## Problemgebiet: Formelsatz

Formelsatz ist grundsätzlich problematisch.

> an elaborate, two-dimensional form of abbreviated notation for compressed, highly complex, context dependent, abstract thought.


Gute LaTeX-Quellen sind das beste Format für barrierefreie Darstellung von Formelsatz im Web. 

[MathJax](https://www.mathjax.org/) hilft.

## Problemgebiete: Visuelle Kommunikation

- Graphiken
  - Textalternativen
  - Visuelles Design (out of scope)
- Farben
- Sensorische Kommunikation
- Bad Practices

Mehr dazu morgen!

## Nach der Pause...

- Kurze Einführung in pandoc und tex4ht
- Beispieldokumente Konvertieren
  - Konversionsprobleme lösen
- Offene Arbeit
