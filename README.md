# sklep online - diagramy UML
1. Cel

Projekt, kóry zawiera się w tym repozytorium, dotyczy budowy systemu sklepu internetowego. Na poszczególnych diagramach przedstawione są poszczególne etapy pracy nad systemem, tak jak i warstwy systemu - logiczne i fizyczne (więcej o diagramach poniżej). Zaprojektowany tutaj system ma umożliwiać bezproblemowe zakupy przez internet (dla klientów), jak i administrowanie całym systemem (dla administratora sklepu).

2. Opis poszczególych diagramów

Diagram klas - istnieją trzy klasy implementujące interfejs "Osoba", reprezentujące osoby korzystające z systemu, które mają inne prawa do korzystania z systemu. Są to klasy "Klient", "Administrator" oraz "Gość". Produkt symbolizuje klasa "Produkt". To w niej są zapisane najważniejsze informacje o produkcie. Następnie mamy klasę "Koszyk", której instancje będą przechowywały informacje o zakupach zrobionych przez danego klienta. Ostatnią klasą jest "SystemPłatności" - jest to bramka płatności.
Diagram obiektów - przedstawia instancje klas z diagramu klas powyżej.
Diagram przypadków użycia - opisuje jakie czynności mogą zostać wykonane przez poszczególnych użytkowników lub poszczególne podsystemy systemu sklepu internetowego.
Diagram przebiegu - opisuje systuację, w której użytkownik zalogował się, a później postanowił zrobić zakupy i sfinzalizować operację poprzez płatność.
Diagram kooperacji - przedstaia strukturę obiektów systemu i komunikację między nimi. Niektóre metody tam przedstawione zawierają argumenty, którymi mogą być całe obiekty przedstawianego systemu.
Diagram stanu - określa stany, w których może znajdowac się obiekt "Klient", tak jak i akcje które może wykonać.
Diagram czynności - pokazuje/obrazuje schemat robienia zakupów przez klienta - szukania produktów oraz płatości za nie.
Diagram komponentów - pokazuje oraganizację i zalezności między poszczególnymi elementami oprogramowania oraz jakie informaje, funkcjonalności te elementy udostępniają.
Diagram wdrożenia - przedstawia powiązanie, tak jak i komunikację pomiędzy oprogramowaniem a sprzętem.
