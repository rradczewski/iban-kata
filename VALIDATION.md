### Validierungslevel

1. Entspricht der allgemeinen Form einer IBAN? 
	1. Maximal 34 Zeichen
	2. Stellen 1-2 sind Buchstaben
	3. Stellen 3-4 sind Ziffern
	4. Ab Stelle 5 sind Ziffern

2. Stimmt die Prüfsumme?
	a. Stellen 1-2 durch ihre Stelle im Alphabet + 9 ersetzen
	b. Stellen 1-6 nach ganz Rechts verschieben
	c. Als Zahl interpretieren und MOD 97 ausführen
	d. Ergebnis gegen 1 prüfen

3. Fokus auf Deutschland: Validiere deutsche IBAN
	1. Länge 22
