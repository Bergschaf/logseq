# Die Siedler
#circle_packing #Bwinf
- # Aufgabenstellung
	- ## Regeln
	  Mindestabstand zwischen zwei Ortschaften: 10km
	  Wenn Abstand zwischen zwei Ortschaften > 20km, dann kann die Krankheit nicht übertragen werden
	  Gesundheitszentrum: alle Ortschaften im Umkreis von 85 km sind immun gegen Krankheiten und übertragung
	- ## Gegeben
	  Gebiet in Form eines Polygons
	- ## Ziel
	  Ein Gesundheitszentrum und möglichst viele Ortschaften so positionieren, dass die Weitergabe von Krankheiten nicht möglich ist
-
- # Visualisierung
	- ## Einfachste Methode
	  #python #PIL #ImageDraw
	  Polygon mit ImageDraw auf Bild zeichnen
	-
-
- # Lösungsansatz
  -> Aufteilung in zwei Unterprobleme
  <ins>-> Die Ortschaften dürfen bis genau an den Rand des Gebietes liegen</ins>
  <ins>-> Die Ortschaften dürfen innen und außen genau am Rand des Gesundheitszentrums liegen</ins>
	- # Möglichst viele Ortschaften im Einflussgebiet des Gesundheitszentrums
	- # Möglichst viele Ortschaften + Gesundheitszentrum im Gebiet
-
- # Mögliche Erweiterungen
	- ## Mehrere Gesundheitszentren
	- ## Änderungen des Gebiets
	  Flüsse, über die keine Krankheit übertragen werden kann
	  wind, der krankheiten in eine bestimmte Richtung besser überträgt