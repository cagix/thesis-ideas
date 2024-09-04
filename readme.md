# Ideen für Projekte, Hausarbeiten und Abschlussarbeiten

Herzlich willkommen, liebe Suchende!

Im Laufe des Informatik-Studiums an der HSBI am Campus Minden müssen immer wieder
Semesterprojekte, Hausarbeiten oder eben auch Abschlussarbeiten erstellt werden.

Hier einige Ideen und Anregungen:

1.  Der [Dungeon] ist unser Spiele-Projekt für die Module [Programmiermethoden] und
    [Programmieren2] und darüber hinaus. Die Basis ist ein Framework zur Erstellung eines
    2D-Rogue-like Dungeon-Crawlers, d.h. ein Spiel, in dem ein Spieler in einem Dungeon
    herumläuft und Aufgaben lösen muss und immer tiefer steigt ... und dabei ständig stirbt
    und wieder neu anfängt. Das nutze ich in "Programmiermethoden" und "Programmieren 2", wo
    die Studis schrittweise über das Semester ein eigenes Spiel in Java implementieren.

    Für ein Forschungsprojekt haben wir den Dungeon mit einer DSL erweitert. In dieser Sprache
    können Lehrende Aufgaben und Rätsel formulieren, die dann über einen "Interpreter" in ein
    fertiges Spiel übersetzt werden.

    In diesem Umfeld lassen sich etliche [**potentielle Themen**] finden. Tipp: Alle Tickets
    in der Liste, die mit "`[Thesis]`" anfangen, sind gute Kandidaten!

2.  Zusätzlich haben wir für die [Compilerbau-Veranstaltung im Bachelor] eine Art "LLVM in
    winzig" geschaffen: den [Mini-Python-Builder] (C-Builder plus Runtime). Die Studis können
    sich aus der AST-Traversierung heraus mit unserem C-Builder passenden C-Code erzeugen
    lassen, den sie zusammen mit einer Art Runtime und einem gcc oder clang zu einem
    ausführbaren Programm übersetzen können.

    Auch hier lassen sich [**viele Ideen**] finden.

3.  Darüber hinaus habe ich noch ein Projekt, das ich für das Tooling zum Erstellen von
    Lehrunterlagen nutze. Hier findest Du ein paar eher praktischere Ideen in diese Richtung:
    [**github.com/cagix/pandoc-lecture**].

Schau Dir gern mal die Sachen an, ob da was für Dich dabei ist und lass uns dazu ins Gespräch
kommen. Die Tickets sind dabei aber nicht unbedingt 1:1 für 5 oder 10 (oder gar für 12 oder
24) ECTS gedacht, d.h. hier muss man im Einzelfall schauen, ob das schon reicht oder wo man
Abstriche macht etc. ... Und vielleicht hast Du ja auch selbst noch Ideen, was Du immer schon
mal machen/lesen wolltest?

## LICENSE

![][1]

Unless otherwise noted, this work is licensed under CC BY-SA 4.0.

<!-- pandoc -s -f markdown -t markdown --columns=94 --reference-links=true readme.md -->

  [Dungeon]: https://github.com/Dungeon-CampusMinden/Dungeon
  [Programmiermethoden]: https://github.com/Programmiermethoden-CampusMinden/PM-Lecture
  [Programmieren2]: https://github.com/Programmiermethoden-CampusMinden/Prog2-Lecture
  [**potentielle Themen**]: https://github.com/Dungeon-CampusMinden/Dungeon/discussions/categories/ideas?discussions_q=is%3Aopen+category%3AIdeas+label%3Athesis
  [Compilerbau-Veranstaltung im Bachelor]: https://github.com/Compiler-CampusMinden/CB-Vorlesung-Bachelor
  [Mini-Python-Builder]: https://github.com/Compiler-CampusMinden/Mini-Python-Builder
  [**viele Ideen**]: https://github.com/Compiler-CampusMinden/Mini-Python-Builder/discussions/categories/ideas?discussions_q=is%3Aopen+category%3AIdeas+label%3Athesis
  [**github.com/cagix/pandoc-lecture**]: https://github.com/cagix/pandoc-lecture/discussions/categories/ideas?discussions_q=is%3Aopen+category%3AIdeas+label%3Athesis
  [1]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
