**<h1 style= "color:red">Dokumentation Gruppenarbeit</h1>**


## Phase 1
Analysieren Sie die Vorgaben mit Augenmerk auf mögliche Beteiligte/Systeme (Personen/Objekte)<br>
des Geschäftsprozesses der ITSystemHausDD GmbH.<br>
• Arbeiten Sie verschiedenen Zielplattformen für die Softwareentwicklung heraus und notieren Sie<br>
deren Vor-/Nachteile bzw. Besonderheiten.<br>
• Ermitteln Sie Tätigkeiten und Beziehungen der beteiligten Objekte und Personen und stellen Sie diese<br>
grafisch dar. → Stichworte: Anwendungsfalldiagramm (siehe Präsentation) /UML/ Software Umletino<br>

<a href="https://github.com/GingerJinx/LF8-Garbage/tree/main/Phase1/" target="_blank">Aufgabe Phase 1</a>


## Phase 2
Mit Github beschäftigen<br>
- repository erstellen<br>
- Git Einstellungen:<br>
git config --global user.name "callmewhatuwant"<br>
git config --global user.email "cryptoisgood@outlook.de"<br>
proxy: git config --global http.proxy http://kjs-03.lan.dd-schulen.de:3128<br>
git config --global https.proxy http://kjs-03.lan.dd-schulen.de:3128<br>
upload files <br>
git add README.md <br>
git commit -m "first commit"<br>
git branch -M main<br>
git push https://github.com/GingerJinx/LF8-Garbage.git<br>

<a href="https://github.com/GingerJinx/LF8-Garbage/tree/main/Phase2/" target="_blank">Aufgabe Phase 2</a>

## Phase 3
Darstellung der zeitlichen Reihenfolge der Tätigkeiten<br>
• Basis sind die gefundenen Beteiligten und die Tätigkeiten aus Phase 1.<br>
• Stellen Sie die Reihenfolge der Tätigkeiten in einem sequentiellen Ablauf (sequentiell = nacheinander<br>
folgend) dar. → Stichworte: Sequenzdiagramm (siehe Präsentation)/UML/Software Umletino<br>

<a href="https://github.com/GingerJinx/LF8-Garbage/tree/main/Phase3/" target="_blank">Aufgabe Phase 3</a>

## Phase 4
Erstellung eines Projekt-Wikis<br>
• Eine einfache Möglichkeit ist die Nutzung von mkdocs für diese Aufgabe. Mit der genutzten<br>
Auszeichnungssprache und dem bereitgestellten Dienst können Sie einfach statische HTML-Seiten<br>
erzeugen, die über einen Web-Serverdienst (z.B. nginx) abrufbar sind.<br>
• Erstellen Sie ein Wiki, welches alle bisher erstellten Dokumente und Informationen im Projekt<br>
beschreibt und als Verweise beinhaltet.<br>
• Sichern Sie das Wiki ebenfalls im git-Repository.<br>


<a href="https://fabi321.github.io/mkdocs-showcase/" target="_blank">Anleitung 4</a> <br>
pip --proxy http://kjs-03.lan.dd-schulen.de:3128  install mkdocs mkdocs-material<br>
<br>
mit cmd:<br>
C:\Users\i21georgini\Documents\lf8\mkdocs\mkdocs vorlage> c:\users\i21georgini\appdata\roaming\python\python310\scripts\mkdocs serve






<a href="https://github.com/GingerJinx/LF8-Garbage/tree/main/Phase4/" target="_blank">Aufgabe Phase 4</a>

## Phase 5

Untersuchen Sie die Datenformate bzw. Datenquellen im Detail.

**1.	Welche Daten werden dargestellt?**<br>
Grundrisse und Gebäudepläne

**2.	Wie werden Daten werden dargestellt?**<br>
Gängige Dateiformate: .png, .jpg, .pdf, .ifc, .rvt, .ndw, .nwd, .pln

**3.	Wie können diese importiert und sinnvoll weiterverarbeitet werden?**<br>
Abfrage des Dateityps -> .png, .jpg, .pdf, .ifc bei Bedarf Wahl der Software

**4.	Welche Metainformationen sind zur Datenquelle vorhanden**<br>
Datum, Dateityp, Absender

**5.	Wer darf innerhalb der ITSystemHausDD GmbH mit diesen Dateien hantieren?**<br>
Alle Projektmitglieder (Bearbeiter:innen, Außendienst)

**6.	Entscheiden Sie sich für ein Dateiformat für das Angebot.**<br>
-	.ifc -> wenn Weiterbearbeitung gewünscht 
-	.pdf -> für Endverbraucher bzw. ohne Bearbeitung 

<a href="https://github.com/GingerJinx/LF8-Garbage/tree/main/mkdocs/mkdocs%20vorlage" target="_blank">Aufgabe Phase 5</a>
<br>
<br>
---
<br>
<a href="https://www.markdownguide.org/basic-syntax/" target="_blank">...Syntax im Internet 5</a>
<br>
<br>

---

[Impressum](legal/imprint.md).
​

​
