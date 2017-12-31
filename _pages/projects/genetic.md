---
permalink: /projects/ai_genetic/
title: "Künstliche Intelligenz - Genetische Programmierung"
layout: single
header: 
    image: /assets/images/GP_crossover.png
---
Die Informatik will oft den einen geraden Weg zur korrekten Lösung finden. In vielen Fällen ist dies jedoch kaum machbar. Dann bieten sich Verfahren an, die mit geeigneten Heuristiken versuchen, eine sehr gute Lösung mit begrenztem Aufwand zu finden. 

Eine Gruppe solcher Verfahren sind Genetische Algorithmen (verwandt sind Evolutionäre Algorithmen und Evolutionsstrategien). Den Verfahren ist gemeinsam, dass für ein gegebenes Problem eine Gruppe von möglichen Lösungen generiert und hinsichtlich ihrer Qualität bewertet wird. Diese "Population" von Kandidaten wird dann durch sogenannte genetische Operatoren transformiert, d.h. durch Mutation werden kleine zufällige Änderungen vorgenommen und per Crossover wird aus zwei oder mehr Kandidaten eine neuer "gemischter" Kandidat erzeugt. Aus der so veränderten Population werden anhand der Qualitätsbewertung wieder die besten Lösungen ausgewählt und dieser Prozess für mehrere "Generationen" wiederholt. 

Das Besondere an der Genetischen Programmierung, die in den 90er Jahren von [John Koza]() vorgestellt wurde, ist, dass die Kandidaten Computerprogramme sind. Diese werden für eine Aufgabenstellung (in meiner Arbeit zum Beispiel eine Krankheitsdiagnose) zuerst zufällig erstellt, dann auf eine Reihe bekannter Testfälle (die Trainingsdaten) angewandt und anschließend hinsichtlich der Korrektheit ihrer Diagnose bewertet. Für die nächste Generation werden die besseren Programme ausgewählt, mutiert und miteinander kombiniert. Die Qualität der Diagnose (die sogenannte Fitness) nimmt im Laufe der Generationen zu und man erhält ein Programm, das auch auf bisher unbekannten Daten brauchbare Diagnosen erstellt. 