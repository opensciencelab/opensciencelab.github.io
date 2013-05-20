---
published: true
layout: default
title: Doku So Far
filename: "_posts/2013-05-05-doku-so-far.md"

---

# Was haben wir?

* Github organizational account [opensciencelab](https://github.com/opensciencelab/) angelegt.
* Das Repository [opensciencelab.github.io](https://github.com/opensciencelab/opensciencelab.github.io) wird unter [http://opensciencelab.github.io](http://opensciencelab.github.io/) ausgegeben 
* Gihub-Benutzer, die [mit dem Rechte-Level "Push"](https://help.github.com/articles/what-are-the-different-access-permissions) hinzugefügt werden, können in dieses Repository neue Postings hineinschreiben, Pull Requests mergen etc.
* Mit etwas Javascript in der [index.html](https://github.com/opensciencelab/opensciencelab.github.io/blob/master/index.html) Liste der Committer neben den Posts generiert
* ... mit einem Link zur Blame-Ansicht des Postings bei Github
* Disqus in die default.html eingebunden
* "Bearbeiten"-Button unter den Posts eingebunden, wie bei [Brunosan](http://brunosan.eu/2012/07/01/jekyll-pull-requests/)
* Persönlicher Access Token eingebaut, um die Github API 5000 mal / Stunde benutzen zu können (sonst wäre das begrenzt auf 60 / Stunde)
* [History-Seite](http://opensciencelab.github.io/history/) mit den letzten Commits zu allen Posts

# Was ist als nächstes zu tun?

* Die History-Liste der letzten Commits zu allen Posts (s.o.) in der Navigationsspalte des Blogs anzeigen o.ä. integrieren
* Layout aufhübschen etc.

# Was später/irgendwann mal tun?

* Eigener Domänenname?
* Piwik einbinden
* Verwendung einer Meta-Information "licence", um Icon/Link der jeweiligen CC-Lizenz unter den Postings anzuzeigen
* Verwendung einer Meta-Information "category", um wie in einem Blog Unterzeichnisse für Kategorien in der URL verwenden zu können
* Blogartige Startseite mit Vorschau der ersten 500 Zeichen jedes Postings
* Commits in die Kommentar-History von Disqus einbinden 
* Github-externer Server mit kleinem Ruby-Skript für granularere Rollen-/Rechteverteilung. Beispielhaftes Problem mit der jetzigen Lösung ("organizational account" bei Github): Um Pull Requests für die eigenen Postings bearbeiten zu können ist man Mitglied des organizational accounts, aber man kann dann keine Pull Requests zu den Postings anderer Autoren machen - sondern man committet seine Änderungen dann direkt. 
* Alternativer Einstieg in die Textsammlung: Mehr "Inhaltsverzeichnis" als "Blog"
* Alternative Ausgabe der Textsammlung, z.B. als ePub oder PDF
* Layout: "Geschweifte Klammer" für Commits zu mehreren Postings gleichzeitig. Idee: Tabellenspalte 1 zählt die Commits auf, Tabellenspalte 2 die (ggf. mehreren) davon betroffenen Postings. Eine (beliebig lange) geschweifte Klammer dazwischen als Verbindung. Könnte man mit [box drawing characters](https://en.wikipedia.org/wiki/Box-drawing_character) (Unicode) malen.

# Related / mögliche auf dies hier aufbauende Projekte

* DOI für jedes Posting, vielleicht beim erstmaligen Veröffentlichen, und danach...?
* dLZA-Lösung für sowas

# Wie erklärt man Dritten, was das hier ist?

* [Nettes Blogposting zum Thema](http://kinlane.com/2013/01/02/creating-two-levels-of-open-engagement-with-github-pages-and-disqus/)
* Könnte man so formulieren: *How To Open Science? (powered by TIB Open Science Lab)* (Arbeitstitel) unterstützt unterschiedlich "tiefe" Formen der Interaktion:
  * Posting kommentieren (Kommentarfunktion benutzen)
  * Überarbeitung eines Posting vorschlagen. (Unter dem Posting auf "Bearbeiten" klicken)
  * Eigenes Posting vorschlagen. (Vorgehensweise: Markdown-Datei schreiben und unter [https://github.com/opensciencelab/opensciencelab.github.io/tree/master/_posts](https://github.com/opensciencelab/opensciencelab.github.io/tree/master/_posts) einfügen.)
  * Die [gesamte Plattform](https://github.com/opensciencelab/opensciencelab.github.io/fork) kopieren, wenn gewünscht einschließlich aller Inhalte.
* ...und verschiedene Formen der Rezeption: Lesen/abonnieren als Blog, Download als ePub etc.
* Maintainer/Fork/Pull Request = "Dritter Modus" des kollaborativen Schreibens, da Überarbeitungen nicht von jedermann, aber auch nicht nur aus geschlossenem Team.
