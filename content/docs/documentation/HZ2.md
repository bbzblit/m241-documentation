# Design Thinking (HZ2)

## Problemstellung
In den letzten Jahren ist Phishing zu einem immer größer werdenden Problem geworden. Durch den rasanten Zuwachs an Internetnutzern gibt es auch immer mehr potenzielle Ziele für Betrüger.

Eine weitere sehr beunruhigende Entwicklung ist die ständige Verbesserung der Phishing-Methoden. Die Techniken der Angreifer werden immer ausgefeilter und sind teilweise selbst für Experten schwer zu erkennen. Ein einziger Fehlklick reicht aus, um einen PC zu infizieren.

## Problemlösung
Um eine Lösung für mein Problem zu finden, habe ich die Design-Thinking-Methode angewandt. Dabei habe ich mehrere Phasen durchlaufen und bin Schritt für Schritt zu einer möglichen Lösung gekommen.

### Verstehen
Zuerst habe ich analysiert, was das eigentliche Problem ist. Dabei bin ich zu dem Schluss gekommen, dass das Hauptrisiko von Domains ausgeht, die täuschend echt wie die originale Webseite aussehen. Zudem verwenden manche offizielle Webseiten Präfixe oder Suffixe, was es noch schwieriger macht, eine offizielle Webseite von Betrugsseiten zu unterscheiden.

### Ideenfindung
Anschließend habe ich Ideen zur Lösung des Problems entwickelt. Meine Hauptlösung besteht darin, einen eigenen DNS-Server zu hosten, der automatisch gefährliche Webseiten erkennen und blockieren kann. Ein möglicher Aufbau könnte so aussehen:

![Scenario 1: Across columns](/image/dns.png)

Dabei werden vergangene DNS-Anfragen anonymisiert gespeichert und anschließend verwendet, um gefälschte Webseiten zu erkennen.

### Iteration und Prototyping
In der Iterationsphase wird überprüft, ob das Produkt brauchbar ist. Da ich keinen Prototyp entwickeln konnte, habe ich lediglich beschrieben, wie ich Usertests durchführen würde, falls ich einen Prototypen hätte.
