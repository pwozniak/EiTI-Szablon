# EiTI-Szablon
EiTI Szablon MGR INŻ

Autor: Piotr Woźniak

Postanowiłem udostępnić mój autorski szablon, zgodny ze wszystkimi normami PW. W folderze "titlepage" znajduje się grafika tytułowa do pracy magisterskiej i inżynierskiej.

UWAGA:

Ten szablon wykorzystuje kompilator XeLaTeX, aby używać pdfLaTeXa albo LuaTeXa, usuńcie fragment z definicją czcionek Ariel i Times New Roman. W XeLaTeXu nie działa BibTex (czyli trzeba pisać ręcznie bibliografię jak w tym szablonie).

PS Szablon jest sprawdzony w boju i polecany. Sam się obroniłem na nim. Nie było żadnych większych uwag. Jedyne odstępstwo od normy to czcionka: 12 pktów zamiast zalecanych 11. W drukarni będą chcieli wam wcisnąć pustą stronę między spisem treści a streszczeniami, ale nie róbcie tego, bo numeracja nie będzie spójna. Numeracja zaczyna się od strony z polskim streszczeniem.

PPS Protip: Wrzucanie rysunków

Korzystajcie z tego (zawsze działa):
https://pastebin.com/BfQ6TntC

Zamiast \textwidth można użyć również \textheight wraz z ułamkami, np. 0.3\textheight, oraz scale=0.5.

UWAGA:

Wymagany pakiet "float" dla parametru "H" (nie mylić z "h"!).
