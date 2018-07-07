# Basketball_BBL

Damit sich Mannschaften und ihre Spieler im professionellen Sportbereich weiterentwickeln und verbessern können, werden Analysen durchgeführt. Diese Analysen, basierend auf Scouting und Statistiken vergangener Spiele, helfen enorm bei der Vorbereitung auf den Gegner und können die Effizienz des Spieles steigern. In dieser Arbeit liegt der Fokus bei der deutschen Basketball Bundesliga (BBL). Die easycredit BBL stellt etliche Informationen zur Verfügung, welche zur Analyse der Mannschaften verwendet werden kann. Diese Statistiken sind alle auf die Leistung der Spieler und Teams bezogen. Hier stellt sich die Frage, ob äußere Faktoren, wie z.B. die Zuschaueranzahl, Hallenkapazitäten und -auslastung, Wochentage und Uhrzeiten sowie Jahreszeiten einen Einfluss auf die Leistung und somit auch auf die Spielergebnisse haben. Mithilfe von künstlicher Intelligenz (KI) und durch die Ansammlung großer Datenmengen sollen Analysen im Sportbereich auf das nächste Level gebracht werden. Dadurch besteht die Möglichkeit, neue Aspekte und Einflussfaktoren zu identifizieren, die sich auf die Gewinnwahrscheinlichkeit auswirken können. Durch die Aufzeichnung aller Daten und der Anwendung von KI, können Muster identifiziert werden, die den Trainer helfen können, seine Spieler zu managen, Strategien zu planen und Vorhersagen für Spiele zu treffen. Wer sich ein wenig mit Sport beschäftigt, der hat schon einmal etwas über den sogenannten „Heimvorteil“ gehört. Das Ziel dieser Arbeit ist es, mittels künstlichen neuronalen Netzen (ANN), mögliche Einflussfaktoren mit Auswirkung auf die Gewinnwahrscheinlichkeit zu eruieren. 

In diesem Repository befinden sich mehrere Versuche, die Wahrscheinlichkeit und Einflussfaktoren herauszufinden:

- SimpleANN_Basketball 1 und 2 waren die ersten Versuche ein Netz zu erstellen

- Das Ziel des Simple ANN war es, herauszufinden wie hoch die Gewinnwahrscheinlichkeit ist, wenn der Input nur aus dem Heim und Gast Team sowie aus dem Ergebnis über Sieg oder Niederlage besteht.

- In dem ANNcomparison werden 50 Netze mit zufälliger Neuronenanzahl trainiert, um das die beste Anzahl herauszufinden.

- ANN_moreFeatures beinhaltet zusätzlich zu den Daten aus dem SimpleANN die Zuschaueranzahl und die Hallenkapazität.

- Das Final_ANN beinhalten zusätzlich zu den Daten aus dem ANN_moreFeatures den Wochentag, die Uhrzeit und die Kalenderwoche.

- In dem kfold_ANN wird die Bewertungsmethode k-Fold Crossvalditation für die Netze verwendet.

