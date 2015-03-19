# Git auf Deutsch

Die tägliche Kommunikation in deutschen Entwicklungsteams, die `git` 
(übersetzt: `Schwachkopf`) anwenden, ist oft das feinste Denglish. 
_"Kannst du bitte pullen"_ oder _"Hast du gepusht"_ sind nur zwei
der oft seltsam klingenden Konstruktionen.

Git auf deutsch schafft Abhilfe!

## Forschläge

Es folgen zwei Tabellen mit Vorschlägen für den täglichen Gebrauch.

| Verb        | Aktueller Gebrauch | Vorschlag             |
|-------------|--------------------|-----------------------|
| pull        | pullen             | ziehen                |
| push        | pushen             | drücken               |
| fetch       | fetchen            | holen                 |
| branch      | branchen           | abzweigen             |
| commit      | commiten           | übergeben             |
| rebase      | rebasen            | umschreiben           |
| merge       | mergen             | vereinigen            |
| stash       | stashen            | verstecken            |
| tag         | tagen              | markieren             |
| cherry-pick | cherry-picken      | rosinen herauspicken  |

| Substantiv   | Aktueller Gebrauch | Vorschlag                      |
|--------------|--------------------|--------------------------------|
| git          | git                | Schwachkopf                    |
| github       | github             | Umschlagplatz für Schwachköpfe |
| repository   | repo               | Lagerstätte                    |
| branch       | branch             | Zweig                          |
| commit       | commit             | Übergabe                       |
| pull request | pull request       | Ziehbegehren                   |
| stash        | stash              | Versteck                       |
| tag          | tag                | Markierung                     |

## Beispiele

    - Kannst du den Zweig, den ich gerade umgeschrieben hab, ziehen und zum Umschlagplatz [für Schwachköpfe] drücken?

    - Ich hab gerade abgezweigt und die Änderungen aus meinem Versteck übergeben.

    - Mach ein Ziehbegehren, wenn du mit der Vereinigung fertig bist!

    - Am besten wir picken uns die Rosinen aus dem Meisterzweig heraus.

## Git auf Deutsch anwenden

Wer den nächsten Schritt machen will, hier eine Anleitung, die Git auf Deutsch
in Deine Konsole bringt. Da Git keine Umlaute zulässt, müssen wir in den 
Befehlen leider darauf verzichten. Nimm folgende Änderungen in Deiner `~/.gitconfig` 
vor:

    git config --global alias.zieh pull
    git config --global alias.druck push
    git config --global alias.zweig branch
    git config --global alias.verzweigen branch
    git config --global alias.ubergeben commit
    git config --global alias.umschreiben rebase
    git config --global alias.vereinigen merge
    git config --global alias.verstecken stash
    git config --global alias.markieren tag

    alias schwachkopf=git
