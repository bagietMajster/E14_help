# E14_help
https://egzamin-informatyk.pl/arkusze-praktyczne-inf03-ee09-e14-programowanie-bazy-danych/
https://arkusze.pl/egzamin-zawodowy-kwalifikacja-e-14/

#JS

## document.getElementById vs querySelector
Teoretycznie do wybierania elementów z HTML jest lepsze querySelector ale nie ma go w tabelce dołączonej do egzaminu.
```
var element = document.querySelector("#id");
```
## interpolacja stringów
W plikach nie używałem interpolacji, bo nie pamiętam czy w technikum było to poruszane czy nie ale używa się jej bardzo prosto:
```
var result = `tutaj jest normalny string i jak chcemy do niego coś dodać to robimy ${zmienna} i dalej sobie możemy pisać`;
```
Należy zwrócić uwagę że to nie jest ' ani " tylko tylda(~) bez shifta. aka backtick.

## const vs let
Warto znać różnice i stosować const, nie tylko dla optymalizacji, ale stałe potrafią wyeliminować błędy które przy zmiennej (let) trzeba dodatkowo obsłużyć.
Egzamin nie jest skomplikowany i można go oblecieć na samym let ale trzeba być czujnym.

## z czego się uczyć?
https://javascript.info/
https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics
https://exploringjs.com/
Lub dowolne źródło w internecie tłumaczące PODSTAWY, nie uczymy się wszystkiego. Podstawy wystarczą do zdania egzaminu i trochę obycia z kodem i przerobienie samodzielnie wszystkich arkuszy.

## Bonus
Jak ktoś chce pracować jako programista i klepać frontend to polecam ten link:
https://gist.github.com/Piotr-Aueternum/97213fa28a27cd7c3a45242a526d7f51
Odpowiednio przerobiony wraz z projektami do portfolio (3-4 większe projekty) może dać pracę.
