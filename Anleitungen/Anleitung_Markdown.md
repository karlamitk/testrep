# Markdown benutzen
- Eine Markdown Datei erstellt man, indem man die Endung .md wählt
- gute Einleitung/Grundübersicht über Textformat: https://de.wikipedia.org/wiki/Markdown
- read this! https://help.github.com/articles/about-readmes/
-es gibt viele Templates, die man nutzen kann

## Eine Datei Verlinken
### Datei "irgendwo im Internet"
- Datei (Seite) öffnen und Adresszeile aud dem Browser einfach kopieren und einfügen
- z.B. [irgendein Link](https://de.wikipedia.org/wiki/Markdown)

    `[irgendein Link](https://de.wikipedia.org/wiki/Markdown)`

- geht auch mit Dateien in (fremden) github-repositories: [github link](https://github.com/patmu04/cubefactory/blob/master/case/README.md)

`    [github link](https://github.com/patmu04/cubefactory/blob/master/case/README.md)`


### Datei im selben repository ***relativ** verlinken:
- [Link zu Dokument im selben ordner](Anleitung_Github_Desktop.md)
- [Link zu Dokument in übergeordneten Ordner](../README.md)
- [Link zu Dokument in parallelem Ordner](../images/Desert.jpg)
```
    [Link zu Dokument im selben ordner](Anleitung_Github_Desktop.md)
    [Link zu Dokument in übergeordneten Ordner](../README.md)
    [Link zu Dokument in parallelem Ordner](../images/Desert.jpg)
```

### Bild verlinken
- Vorgehen genauso wie bei Dateien. Syntax unterscheidet sich durch ein `!`
- ![Anzeige von Bild aus parallelem Ordner](../images/Desert.jpg)

`    ![Anzeige von Bild aus parallelem Ordner](../images/Desert.jpg)`
