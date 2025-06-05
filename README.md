# HTML

Schritt für Schritt zum übertragen von lokalen Dateien zu GitHub:

1. Repository erstellen und einrichten:

    -In GitHub, gehe auf Home (Dashboard) und drücke "New"

    -Gebe ein gültigen Namen für das Repository an und mache ein Haken bei "READ.ME Datei einfügen". Klicke unten auf "Repository erstellen"

    -Im neu erstellen Repository, drücke "<> Code" an und unter SSH, kopiere den Link

    -Gebe im Terminal den Befehl und den gerade kopierten SSH KEY, hier in diesem Beispiel <git clone git@github.com:jennyrosyy/html-basics.git>

    -Gehe in den erstellen Ordner mit <cd html-basics> und gebe danach <git remote -v> ein. Nach diesem Befehl kommt ein Output: 
        origin	git@github.com:jennyrosyy/HTML.git (fetch)
        origin	git@github.com:jennyrosyy/HTML.git (push)

    -Erstelle neue Ordner oder Dateien und gebe danach <git status> ein.

    -Gebe (hier für dieses Beispiel) <git add html-boilerplate> ein. Danach gebe wieder <git status> ein.

    -Gebe <git commit -m "Hier dein Kommentar für Änderungen"> und danach <git status> nochmal ein.

    -Gebe <git log> ein (falls man stecken bleibt, drücke q für Quit).

    -Für alle Änderungen, die gemacht wurden, gebe <git add .> ein oder <git add 'Datei/Ordner'> ein für bestimmte. Danach wieder <git status>.

    -Gebe <git commit -m "Hier dein Kommentar zu Änderungen"> ein und danach <git status>. Ob alles einwandfrei in der Warteschlange ist, gebe <git log> ein.

    -Zum Schluss gebe <git push> oder <git push origin main> ein und zuletzt <git status> zum überprüfen. Falls alles richtig gemacht wurde, steht "Your branch is up to date with 'origin/main'. nothing to commit, working tree clean".

    -Lade GitHub neu und alle neuen Dateien/Ordner wurden hochgeladen.
