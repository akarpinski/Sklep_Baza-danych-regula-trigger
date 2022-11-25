<img src="PG_WFTiMS.jpg" alt="Politechnika Gdańska" width="300" height="auto"> 

#### Projekt bazy danych: <b> SKLEP INTERNETOWY </b>
---
Mój własny projekt tworzony w trakcie studiów Data Science/Big Data  na Politechnice Gdańskiej.

#### Dwie wersje w oddzielnych plikach
* dla Oracle w PL/SQL
* dla PostgreSQL w PL/pgSQL

##### Scenariusz projektu
1. Sklep internetowy ze sprzętem komputerowym.
```
* Na stronie internetowej sklepu podany jest m.in. wykaz towarów, ceny, dane sklepu, kontakt.
* W bazie danych sklepu są zbierane dane aktualnych klientów i tych, którzy składali zamówienia w przeszłości.
* Zamówienia drogą internetową z podaniem swoich danych osobowych i jednej z 3 form dostawy.
```

2. Dodatkowo (na końcu reguła, funkcje, trigger)
```
* Reguła zapisująca stare ceny przed ich zmianą (dla obniżki).
* Wyzwalacz o działaniu takim jak poprzednia reguła, ale z innym parametrem oraz ich przykład użycia (dla podwyżki).
```

3. Dwie wersje bazy danych (Oracle, PostgreSQL)
```
* Reguła, funkcje, trigger pisane były dla wersji bazy PostgreSQL w PL/pgSQL.
* Nie działają tu w wersji bazy Oracle w PL/SQL.
```

4. Relacyjny model bazy danych (zmienne, typy danych, klucze tabel, relacje)
```
* Przedstawiony tutaj w formie graficznej lub obrazu w oddzielnym pliku.
```

5. Raport bazy danych.
