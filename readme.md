# Ideen für Projekte, Hausarbeiten und Abschlussarbeiten

Herzlich willkommen, liebe Suchende!

Du bist auf der Suche nach einem Thema für Deine Bachelor- oder Masterarbeit oder Dein
Forschungsprojekt? In den Bereichen **Programmiersprachen und Compilerbau**,
**Softwarequalität** sowie **Künstliche Intelligenz** betreue ich Arbeiten, die sich mit
innovativen und praxisrelevanten Fragestellungen auseinander setzen. Ich betreue dabei sowohl
Arbeiten an der HSBI als auch "mitgebrachte" Themen, beispielsweise in einem Firmenkontext.

Hast Du bereits Ideen, gibt es Dinge, die Du immer schon mal machen/lesen wolltest? Lass uns
gern darüber austauschen, um diese Ideen gemeinsam zu einem passenden Thema zu entwickeln.

## Programmiersprachen und Compilerbau

Im Bereich **Programmiersprachen und Compilerbau** könntest Du die Auswirkungen bestimmter
Designentscheidungen von Programmiersprachen auf einen Compiler (und die Runtime) untersuchen.
Eine andere spannende Idee ist die Entwicklung eines Prototyps für einen neuen Compiler, der
neue oder hybride Programmierparadigmen unterstützt oder bestehende Techniken verbessert. Die
Entwicklung eigener Sprachen/DSL oder die Untersuchung der Integration von Programmiersprachen
in moderne Software-Entwicklungsumgebungen bieten ebenfalls Potential für interessante
Projekte.

## Softwarequalität

Innerhalb des Themenfeldes **Softwarequalität** gibt es zahlreiche Ansätze, die Du vertiefen
kannst. Eine Möglichkeit wäre beispielsweise die Analyse von Software-Testing-Methoden und
deren Einfluss auf die Softwarequalität. Du könntest auch ein Projekt entwickeln, das die
Automatisierung von Tests mithilfe von KI-Techniken fördert. Die Evaluierung und Verbesserung
bestehender Code-Review-Tools (beispielsweise über KI-Methoden) bietet interessante
Ansatzpunkte. Die Erstellung und Umsetzung eines umfassenden Testkonzepts für ein
Softwareprojekt könnte ebenfalls eine interessante Arbeit sein.

## Künstliche Intelligenz

Im Bereich **Künstliche Intelligenz**, insbesondere im Gebiet der **Natural Language
Processing (*NLP*)** und der Anwendung von **Large Language Models (*LLM*)**, stehen Dir
vielfältige Möglichkeiten offen. Hier könntest Du beispielsweise untersuchen, wie
Retrieval-Augmented Generation (*RAG*) eingesetzt werden kann, um die Qualität der von LLM
generierten Texte zu verbessern. Ein weiteres Projektthema könnte die Entwicklung von
Anwendungen sein, die sich auf die Erkennung und Verarbeitung von Emotionen oder
Sarkasmus/Ironie in Texten fokussieren. Zudem ist die Erforschung von Bias in Modellen der
natürlichen Sprachverarbeitung ein brisantes und relevantes Forschungsfeld.

## Ideen aus Projekten

Hier findest Du hier zusätzlich noch einige Ideen und Anregungen aus verschiedenen Projekten:

1.  Der [Dungeon] ist unser Spiele-Projekt für die Module [Programmiermethoden] und
    [Programmieren2] sowie darüber hinaus. Das Projekt ist ein Framework zur Erstellung eines
    2D-Rogue-like Dungeon-Crawlers. In diesem Spiel navigiert der Spieler einen "Helden" durch
    einen Dungeon, löst Aufgaben und steigt dabei immer weiter ab -- mit der Schwierigkeit,
    dass der Held ständig stirbt und das Spiel wieder neu anfängt. In den Modulen
    "Programmiermethoden" und "Programmieren 2" setzen die Studierenden damit schrittweise im
    Verlauf des Semesters ihr eigenes Spiel in Java um.

    Für ein Forschungsprojekt haben wir den Dungeon um eine Domain-Specific Language (*DSL*)
    erweitert. Mit dieser Sprache können Lehrende spezifische Übungsaufgaben und Rätsel
    formulieren, die dann mit einem von uns implementierten Interpreter/Compiler in ein
    fertiges Spiel für Studierende übersetzt werden.

    In diesem Kontext ergeben sich zahlreiche [**potentielle Themen**], die sowohl für
    Bachelor- als auch Masterarbeiten oder Forschungsprojekte interessant sein könnten.

2.  Für die [Compilerbau-Veranstaltung im Bachelor] haben wir eine Art "Mini-LLVM" entwickelt:
    den [Mini-Python-Builder]. Die Studierenden schreiben einen eigenen Parser für einen
    Python-Dialekt und können aus der AST-Traversierung heraus mit dem Mini-Python-Builder
    passenden C-Code generieren, welcher dann zusammen mit einer von uns selbst definierten
    Runtime und einem normalen C-Compiler wie gcc oder clang in ein ausführbares Programm
    übersetzt werden kann.

    Auch in diesem Bereich gibt es [**viele spannende Ideen**] für Bachelor- als auch
    Masterarbeiten oder Forschungsprojekte, die Du erkunden kannst.

3.  Für das Tooling zur Erstellung von Lehrunterlagen pflege ich das Projekt
    [**github.com/cagix/pandoc-lecture**]. Hier findest du einige praktische Ideen für
    potentielle Projekte.

Schau dir gerne die Projekte an, ob etwas für Dich dabei ist. Lass uns darüber ins Gespräch
kommen! Die Themen sind dabei nicht unbedingt 1:1 für 5 oder 10 (oder sogar für 12 oder 24)
ECTS-Punkte gedacht. Das bedeutet, dass wir im Einzelfall prüfen müssen, ob das Thema
ausreicht oder wo eventuell Anpassungen notwendig sind.

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
  [**viele spannende Ideen**]: https://github.com/Compiler-CampusMinden/Mini-Python-Builder/discussions/categories/ideas?discussions_q=is%3Aopen+category%3AIdeas+label%3Athesis
  [**github.com/cagix/pandoc-lecture**]: https://github.com/cagix/pandoc-lecture/discussions/categories/ideas?discussions_q=is%3Aopen+category%3AIdeas+label%3Athesis
  [1]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
