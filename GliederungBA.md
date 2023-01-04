# Einleitung
	Es wurden Mertiken erarbeitet, um zu bestimmen welche Platform sich wie gut für Android Kernel Fuzzing eignet. 
	Android wurde auf den jeweiligen Platformen aufgespielt und der Metrikwert erhoben. 
	Um zu evqluieren, ob die Metrik die Realität gut abbildet wurde Testweise Fuzzing auf den Platformen betrieben. 
	Hierzu wurden Beispielbugs entworfen und in den jeweiligen Kernel eingebaut. Diese Bugs mussten dann vom Fuzzer gefunden werden.
	Ob und wie schnell die Bugs gefunden wurden, war das Kriterium, nach welchen die Platformen eingeordnet wurden.
	Mit dieser zweiten Methode konnte die zuvor erarbeitete Metrik auf Güte überprüft werden.
# Motivation
	Es gibt sehr viele Android Geräte und Bugs im Kernel sind beonders schlimm. Fuzzing ist eine tolle Sache und 
	wenn man damit Bugs auf Android finden kann, dann sollte man das tun. Je besser man fuzzen kann desto mehr bugs kann man finden, 
	also macht es Sinn zu schauen welche Platfrom am besten geeignet ist.
# Ziel der Arbeit
	Ziel ist es einen Weg zu finden, mit dem man auch in Zukunft Platformen auf ihre Eignung für Android Kernel Fuzzing überprüfen kann.
# Grundlagen
	## ARM Architektur 
	Was macht ARM aus und warum wird es für Android verwendet?
	## Linux
	Was macht Linux aus und warum ist Android darauf aufgebaut?
	## Android
	Was unterscheidet Android von Linux, vor allem was den Kernel angeht?
	Was sind für Fuzzing wichtige Eigenschaften?
	## Device vs. VM
	Was ist der Unterschied, vor allem auf Fuzzing bezogen?
	## Programmanalyse 
	Welche Arten gibt es und wie eignen sie sich für Kernel analyse?
	## Dynamische Programmanalyse 
	Was ist das und wie muss man ein Programm zur analyse vorbereiten? 
	Wie verhält sich das, wenn man den Kernel untersucht?
	## Software Sicherheit
	Was kann einen Kernel unsicher machen und was hat das für Folgen? Beispiel?
	## Fuzzing
	Was ist Fuzzing? Wie funktioniert es und was ist besonders, 
	wenn man einenn Kernel fuzzen möchte? Welchen Fuzzer benutzen wir 
	und was macht diesen besonders?
	## Benchmarking 
	Welche Arten gibt es,welche eignet sich in diesem Fall und warum?
	## Qualitätsmetriken 
	Welche Arten gibt es? Was will man in diesem Fall messen 
	und welche Aussagekraft erwartet man?
	## Android Kernel Fuzzing
	Wie fügen sich die genannten Teile zu einem Ganzen zusammen 
	und was für Besonderheiten ergeben sich?
# Umsetzung
	## Die Platformen
	Welche Plattformen werden berücksichtigt und warum? 
	## Die Android Varianten
	Welche Varianten wurden genutzt und warum? 
	## Custom Android bauen
	Was wurde gebaut und warum? Wie lief der Prozess ab, was gab es für Schwierigkeiten und Lösungen?
	## Qualitätsmetriken erarbeiten
	Wie wurde vorgegangen und warum? Was soll die Metrik aussagen? Die Metrik wird beschrieben. 
	## Metrik auf Umgebungen anwenden
	Für alle Platformen mit allen Android Varianten wird einzeln das Metrik Rrgebnis beschrieben.
	## Ergebnis der Umgebungsvergleiches
	Wer ist der beste und was bedeutet das für Fuzzing?
# Evatuation
	## Kernel Challenges erstellen 
	Was sind diese Challenges? Was sollen sie aussagen? Wie erstellt man diese?
	## Testweise Fuzzing durchführen 
	Den ganzen Prozess beschreiben. Welcher Fuzzer wird benutzt 
	und wie benutzt man ihn in unserem Fall? Was wird gemessen und wie?
	## Metrikwerte mit Fuzzing-Realität vergleichen 
	Für jede Platform den Metrikwert mit dem Fuzzingtest vergleichen.
	## Interpretation und Fazit
	Ist die Metrik gut? Was wäre besser? was kann man tun?
#Related Work
	## Allgemeiner Forschungsstand
	Wird Fuzzing auf dem Android Kernel schon gemacht, wenn ja wie? 
	## Einzelne Projekte
	Beispiele
# Future Work
	Was wurde nicht gemacht und wie könnte das moch erreicht werden?