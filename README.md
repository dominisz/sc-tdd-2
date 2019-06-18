# Software Craftsmanship - Test Driven Development

## Źródło

Zadanie powstało na podstawie https://osherove.com/tdd-kata-1

## Zadanie

Wykorzystać podejście test driven development (https://www.samouczekprogramisty.pl/test-driven-development-na-przykladzie/) podczas implementowania metody, która dla podanego łańcucha dodaje znajdujące się w nim liczby całkowite (zakładamy, że w łańcuchu znajdują się poprawne liczby całkowite oddzielone przecinkami, np. `1,2,3,-4,50,234,1200`) i zwraca ich sumę. Metoda powinna być rozwijana z uwzględnieniem kolejnych wymagań:
* dla parametru `null` lub łańcucha pustego metoda zwraca 0,
* jeżeli łańcuch zawiera jedną liczbą, to metoda zwraca jej wartość,
* jeżeli w łańcuchu znajdują się dwie liczby oddzielone przecinkiem, to metoda zwraca ich sumę,
* jeżeli w łańcuchu znajduje się dowolnie wiele liczb oddzielonych przecinkami, to metoda zwraca ich sumę,
* jeżeli w łańcuchu znajdują się liczby ujemne, to metoda wyrzuca wyjątek,
* jeżeli w łańcuchu znajdują się liczby większe niż 1000, to są ignorowane.
