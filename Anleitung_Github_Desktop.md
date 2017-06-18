# github Desktop benutzen
## Projekt einrichten
- Github Desktop installieren.
- Persönl. Einstellungen (File > Options):
    - Zugangsdaten zu github (Accounts)
    - Daten, mit denen alles unterschrieben wird (Git)
- Unser Projekt herunterladen:
    - (File > Clone Repository)
    - URL: patmu04/cubefactory
    - local path: Ordner, wo das Projekt liegen soll
- Projekt ist eingerichtet

## Workflow (Änderungen machen)
- neuen Branch für die Änderungen anlegen (Branch > New Branch, Namen geben)
- darauf achten, dass oben bei "current branch" der neue Branchname steht
    - beliebig Änderungen an den Dokumenten /der Ordnerstruktur im Projektordner unter local path vornehmen
    - dabei tauchen in Git Desktop rote und blaue Zeilen mit den änerungen auf. Links sind die changed files (verschieben ist auch eine       Änderung (des Dateinamens) auf)
    -wenn genug geändert, commit machen
    -dazu unten links Beschreibung der Änderungen (kurz, dort wo summary steht) eintippen und click auf commit to <mein branchname>
- so viele commits machen, wie gewünscht
- um ins remote repository (das, was man auf der Homepage sieht) zu pushen (hochladen/veröffentlichen):
    - oben, wo meist "fetch origin" steht auf den "Push to origin" Button klicken
    - erscheint online (allerdings nur, wenn man den branch von master auf den eigenen branchnamen ändert
    - zusammenführen geht über pull request 
