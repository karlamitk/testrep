# github Desktop benutzen
## Projekt einrichten
- Github Desktop installieren.
- Persönl. Einstellungen (File > Options):
    - Zugangsdaten zu github (Accoun"ts)
    - Daten, mit denen alles unterschrieben wird (Git)
- Unser Projekt herunterladen:
    - (File > Clone Repository)
    - URL: patmu04/cubefactory
    - local path: Ordner, wo das Projekt liegen soll
- Projekt ist eingerichtet

## Workflow (Änderungen machen)
- Workflow zusammengefasst (Links beziehen sich nicht auf github desktop)
    - https://guides.github.com/activities/hello-world/
    - https://help.github.com/articles/github-flow/
    -  https://guides.github.com/introduction/flow/ 
-  Video, was ungefähr dem entspricht, was WIR machen, allerdings clone repository (siehe oben) anstatt add existing"
    - https://www.youtube.com/watch?v=ISkPyNkM2iY
- neuen Branch für die Änderungen anlegen (Branch > New Branch, Namen geben)
- darauf achten, dass oben bei "current branch" der neue Branchname steht
    - beliebig Änderungen an den Dokumenten /der Ordnerstruktur im Projektordner unter local path vornehmen
    - dabei tauchen in Git Desktop rote und blaue Zeilen mit den Änderungen auf. Links sind die changed files (Verschieben ist auch eine Änderung (des Dateinamens) auf)
    -wenn genug geändert, commit machen
    -dazu unten links Beschreibung der Änderungen (kurz, dort wo summary steht) eintippen und click auf commit to <mein branchname>
- so viele commits machen, wie gewünscht
- um ins remote repository (das, was man auf der Homepage sieht) zu pushen (hochladen/veröffentlichen):
    - oben, wo meist "fetch origin" steht auf den "Push to origin" Button klicken
    - erscheint online (allerdings nur, wenn man den branch von master auf den eigenen branchnamen ändert
    - schnellster Weg dorthin: (Repository > View on Github)
    - zusammenführen geht über pull request 
 
## Git allgemein verstehen
- sehr ausführlich: https://git-scm.com/book/en/v2
- kürzer https://homepages.thm.de/~hg11260/mat/git.pdf
    - v.a. die ersten 2 Seiten können helfen für ein Grundverständnis
    - Beispiel nutzt nur Kommandozeile und andere Plattform (kein github)