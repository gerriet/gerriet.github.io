---
permalink: /projects/image_inspection
title: "Bildinspektion zur optischen Qualitätskontrolle"
layout: single
#header: 
#    image: /assets/images/
---

In vielen Bereichen ist es wichtig, Produkte vor und nach einer gewissen Verarbeitung zu vergleichen und festzustellen, ob nur die gewünschten Veränderungen vorgenommen wurden. 

In der Softwareentwicklung setzt man dazu häufig Programme zum Textvergleich im Rahmen der Versionsverwaltung ein, die nur die Zeilen zum Beispiel im Programmcode hervorheben, die tatsächlich verändert wurden. Für Druckprodukte, die eventuell sogar in pharmazeutischem Umfeld eingesetzt werden (man denke an Packungsbeilagen von Medikamenten) ist dies ungleich komplexer. 

Ich habe ein solches Produkt (MediaCheck Workflow) bei der Firma [tec4check](https://www.tec4check.de/) mit aufgebaut. 

Es zeichnetesich durch die Strukturierung als Client-Server-Anwendung, die geschwindigkeitsoptimierte Bildverarbeitung mit OpenMP und SSE, sowie die effiziente Bedienung und gute Integration in bestehende Arbeitsabläufe aus und ist heute weltweit im Einsatz. 

Prüfungen in hoher Auflösung von Bogen in A0-Größe und darüber hinaus bedeuten, dass das System einerseits Bilder in Gigabytegröße verarbeitet und darin dann Abweichungen bis hinab zu i-Punkten in 4-Punkt-Schrift findet. Es fliessen Daten aus unterschiedlichen Abteilungen zusammen (PDF-Verarbeitung in der Druckvorstufe, druckbegleitende Prüfung, abschliessende Prüfung beim Warenausgang) und bei vielen Kunden fallen monatlich Tausende von Prüfungen an. Letzteres bedeutet auch, dass sich durch besonders effiziente Handhabung des System viel Arbeitszeit beim Kunden einsparen liess. Dazu trägt auf der anderen Seite besonders die intelligente Bildverarbeitung bei, die nur die wirklich relevanten Abweichungen auswählt.