# Erweitere Latex-Vorlage

Dies ist eine erweiterte LaTeX Vorlage und basiert auf der Vorlage der [Hochschule Furtwangen](https://www.hs-furtwangen.de/) und wurde im Rahmen meiner Bachelor Thesis um weitere Funktionen erweitert. 


## Funktionen:

+ Quellcodeverzeichnis
+ Veränderte Verzeichnis-Struktur
+ Dateistruktur beginnend mit Zahlen zur Sortierung des Quellcodes
+ Abgeänderte Nummerierung im Inhaltsverzeichnis
+ Gitignore für LaTeX und TMP-Ordner
+ Vorbereitung zum Einsatz in [Texlipse](http://texlipse.sourceforge.net/), [TeXStudio](https://www.texstudio.org/)
+ Kompatibel zu: [Overleaf](https://www.overleaf.com/)
+ Angepasste Code-Darstellung
+ HFU Konform für Bachelor/Master-Thesis und Projekt-Dokus

## Verzeichnisstruktur 

```
├─README.MD  
├─.gitignore  
├─*document_BUILD.pdf* (generierte LaTeX Pdf von Texlipse)  
└─── src  
   ├── main.tex (Hauptdatei)  
   ├── preamble.tex (Konfiguration)  
   ├── bibtex.bib (Quellen)  
   └── content (Beinhaltet die Kapitel)  
      ├── 0_introduction.tex  
      ├── 1_basics.tex  
      ├── 2-7_custom_chapter.tex  
      ├── 8_prospect.tex  
      ├── 9_conclusion.tex  
      ├── code  
      |   └── example.java  
      ├── pictures  
      |   └── hfu.jp  
      └─── framework  
         ├── abbreviations.tex (Abkürzungen)  
         ├── abstract.tex (Abstract)  
         └── title.tex (Deckblatt)  
```

## LaTeX Pakete:

### Linux 

texlive-Repository hinzufügen:

```sudo add-apt-repository -y ppa:texlive-backports/ppa```

Benötigte Pakete (können mit apt-get installiert werden):

+ texlive
+ latexmk
+ texlive-lang-german
+ texlive-latex-extra
+ texlive-fonts-extra
+ texlive-bibtex-extra

### Windows:

[Miktex](http://miktex.org/download)
Fehlende LaTeX pakete werden bei bedarf installiert.

### OSX: 
[Mactex](http://tug.org/mactex/)


Über Ergänzungen in Form eines Pull-Requests freue ich mich.
