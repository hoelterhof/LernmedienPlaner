# Lernmedien-Planer

*This is a tool for teachers to design digital learning environments that are made up of several components resp. medias, like wikis, videos, presentations and instructions etc. It is also a wiki for organising and implementing this design process as well as a database of possible authoring tools and platforms that can be used for this purpose. It is an open educational resource (OER) for teaching and learning in higher education teacher training with a focus on teachers in healthcare and nursing. Currently this tool is available in German language only.*

Der Lernmedien-Planer ist ein Tool für Lehrende zum Entwerfen von digitalen Lernumgebungen, die aus mehreren Komponenten bzw. Medien zusammengesetzt sind, wie etwa Wikis, Videos, Präsentationen, Lernaufgaben etc. Er ist außerdem ein Wiki zum Organisieren und Realisieren dieses Gestaltungsprozesses sowie ein Datenbank mit möglichen Autorenwerkzeugen und Plattformen, die hierfür eingesetzt werden können. Das Tool stellt als solches eine offene Bildungsressource (OER) für das Lehren und Lernen in der hochschulischen Lehrendenbildung dar mit einem Fokus auf das Lehren im Gesundheitswesen und in der Pflege.

------------------------------------------------------------------------

Dieses Tool ist entstanden im Rahmen der Schwerpunktprofessur „Gestaltung digitaler Bildungsumgebungen im Gesundheitswesen" an der [Katholischen Hochschule NRW](https://www.katho-nrw.de) von [Tobias Hölterhof](https://hoe.lt/erhof).

Installation und Nutzung
========================

Der Lernmedien-Planer ist in JavaScript programmiert, läuft in allen gängigen und aktuellen Webbrowsern und wird als **eine HTML-Datei** ausgeliefert, in der alle Ressourcen eingebettet sind. Für die Nutzung ist daher keine Installation erforderlich. Außerdem kann das Tool offline ausgeführt werden, es ist kein Server erforderlich.

Eine aktuelle Version des Lernmedien-Planers als HTML-Datei ist im Ordner `output/` in diesem Repository. Diese Version kann ohne weitere Voraussetzungen im Webbrowser genutzt werden, indem die HTML-Datei geöffnet wird. Im Tool ist eine Anleitung verfügbar, die die weitere Verwendung erklärt.

Das Tools basiert auf [TiddlyWiki](https://github.com/Jermolene/TiddlyWiki5) von [Jeremy Ruston](https://github.com/Jermolene).

Build
=====

Der Lernmedien-Planer kann aus den hier im Repository eingestellten Source-Codes erzeugt werden. Dafür ist [node.js](https://nodejs.org) sowie das node.js-Package [tiddlywiki](https://www.npmjs.com/package/tiddlywiki) erforderlich. Sind diese Voraussetzungen installiert, kann das Tool aus diesem Stammverzeichnis dieses Repositorium mit dem folgenden Befehl erstellt werden:

``` {.shell}
tiddlywiki ./ --build index
```

Nach der Ausführung dieses Befehls ist der Lernmedien-Planer als `index.html` im Ordner `output/` zu finden.

Lizenz
======

Diese Software wird unter der Creative-Common-Lizenz [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.de) vertrieben. Eine Kopie dieser Lizenzvereinbarung ist in der Datei [LICENSE](LICENSE.md) zu finden.
