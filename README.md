# **TASK 1️⃣** 

## Subtask 1 

9/10

## Subtask 3 👋

Hej! Zdecydowałam się podjąć to wyzwanie, ponieważ chciałam doświadczyć, jak wiedzę teoretyczną można zastosować w praktyce. Byłam też bardzo ciekawa, czy moje dotychczasowe umiejętności sprawdzą się w roli testera manualnego. Zawsze fascynowało mnie nowe oprogramowanie i uwielbiam odkrywać, jak ono działa. Wydaje mi się również, że branża IT rozwija się cały czas, co oznacza że trzeba się rozwijać razem z nią i na pewno będzie to ekscytujące. Mam nadzieję, że to wyzwanie pomoże mi dowiedzieć się nieco więcej o tej roli, pozwoli mi ocenić i rozwinąć moje umiejętności oraz poprowadzi mnie we właściwym kierunku w mojej nowej karierze.

## Subtask 4 Testy eksploracyjne

*Na czym polega ta aplikacja? Do czego służy*❓

Jest to aplikacja przeznaczona do zarządzania i porządkowania informacji o piłkarzach. Oferuje różne funkcje, takie jak dodawanie nowych graczy, edytowanie profili graczy i symulowanie gier. Dodatkowo aplikacja udostępnia funkcję generowania raportów, dzięki którym użytkownicy mogą przeglądać szczegółowe dane zawodników. Użytkownicy mogą także dodawać komentarze lub opisy rozegranych meczów, usprawniając ogólną analizę i dokumentację każdego meczu.


*Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmieniła❓ 

Lista funkcjonalności:
- Logowanie/Wylogowanie
- Dodawanie nowych graczy.
- Dodawanie meczy.
- Zarządzanie rozgrywkami meczów.
- Możliwość filtrowania danych.
- Generowanie raportów z opcją pobrania.
- Kontakt z zespołem deweloperskim.
- Wybór języka (polski lub angielski).
  

*Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie*❓

Interfejs aplikacji jest łatwy w obsłudze. Choć nie jest on zbyt intuicyjny pod względem poruszania się, to jednak spełnia większość swoich funkcji co stanowi kluczowy element pozytywnego doświadczenia użytkownika. Pod względem wizualnym nie jest to aplikacja zaawansowana. 


*Czy aplikacja jest intuicyjna❓ 

Według mnie, nie wszystkie funkcjonalności aplikacji są intuicyjne, ale ogólnie aplikacja jest dość prosta w obsłudze. Większość elementów została zaprojektowana w sposób umożliwiający użytkownikom naturalne poruszanie się po niej bez większego wysiłku. Niemniej jednak, wprowadzenie kilku zmian mogłoby poprawić intuicyjność aplikacji. Poniżej podaje kilka przykładów, które polepszyłyby użytkowanie:

- Obecny proces dodawania graczy pozwala na przesłanie nieprawidłowych informacji bez stosowania żadnej logiki sprawdzania danych. Wdrożenie walidacji danych pomogłoby zapewnić akceptowanie wyłącznie ważnych informacji. Aby pomóc w sprawdzaniu poprawności danych, dobrą opcją byłoby wdrożenie "menu rozwijane", które pomoże użytkownikom wybrać prawidłowe opcje i zmniejszyć prawdopodobieństwo błędów podczas wprowadzania danych.
- Korzystne byłoby ulepszenie strony głównej poprzez umożliwienie użytkownikom klikania górnych pól (liczba zawodników, mecze, raporty, akcje) i przekierowania do odpowiedniej sekcji raportów w celu łatwiejszej nawigacji.
- Po prawej stronie pole „aktywność” przechodzimy do edytowania, według mnie należy wyłączyć automatyczną edycję danych po kliknięciu i zmianę wyłącznie na podgląd, umożliwiając edycję dopiero po wybraniu odpowiedniej opcji.
- Brakuje w menu zakładki z "meczami", która pojawia się dopiero po dodaniu gracza.
- Niektórym przyciskom brakuje opisów, co należy dodać dla lepszego zrozumienia i dostępności dla użytkownika mam tutaj na myśli kiedy przechodzimy do zakładki mecze i odgrywamy grę, dla niektórych użytkowników przyciski mogą być niezrozumiałe.


*Czy zauważasz jakieś błędy❓ Albo coś wydaje Ci się błędem❓ 

- Generowanie raportów- można ściągnąć tylko jedną stronę, powinna być możliwość ściągnięcia całej bazy danych (ułatwiłoby to przegląd całej bazy danych offline np w programie excel)
- Podczas użytkowania aplikacji w języku angielskim znajdujemy słówka, które nie zostały przetłumaczone i vice versa
- Podczas wypełniania informacji o graczu wyskakuje błąd, że nie udało się dodać gracza, jednak nie wiemy jaki błąd i jakie okienko trzeba wypełnić (zdarza się to podczas podania nieprawidłowego formatu email)
- Możliwość dodania gracza z przyszłości, oznaczam to jako błąd
- Pole waga/wzrost pozwala na wprowadzenie wartości ujemnych, które należy ograniczyć.
- Opcja „telefon” pozwala na wprowadzanie liter, które powinny być ograniczone wyłącznie do cyfr.
- Aplikacja pozwala na wpisanie cyfr w polach imienia i nazwiska, które należy ograniczyć do liter.
- W opcjach dodawania linków do YouTube i Facebooka nie ma ograniczeń formatu - według mnie ograniczenie formatu do prawidłowych linków do stron internetowych i zapewnienie możliwości przekierowania byłoby ulepszeniem
- Podczas kiedy przechodzimy do zakładki "mecze" opcje które są nieopisane (graj, pauza, cofnij, raport, usuń) niektóre z nich nie działają - opcja cofnij i usuń
- Pole "kolor koszulki" tutaj można dodać numery - menu rozwijane byłoby dobrą opcją.
- Podczas podawania numeru zawodnika można wpisać ujemną liczbę i system akceptuje dane.


# **TASK 2️⃣**

## Subtask 1 

*Pisanie przypadków testowych na podstawie User Story.* 👇

https://docs.google.com/spreadsheets/d/17HuADjw36U1ICTBMWDfxVv165mc_FXMnMt0lwNPjtcM/edit#gid=0

## Subtask 2 

*Pisanie przypadków testowych na podstawie “własnych doświadczeń”.* 👇

https://docs.google.com/spreadsheets/d/17HuADjw36U1ICTBMWDfxVv165mc_FXMnMt0lwNPjtcM/edit#gid=627617835

## Subtask 3

*Po co piszemy test case'y*❓ 

Przypadki testowe piszemy, aby udokumentować w przejrzysty sposób różne możliwości obsłużenia modułów w ramach danej aplikacji. Dobre pokrycie przypadkami testowymi oprogramowania daje nam pewność podczas testów, że nie pominęliśmy żadnej ważnej funkcjonalności.

## Subtask 4 

*Pisanie przypadków testowych na podstawie “własnych doświadczeń.* 👇

https://docs.google.com/spreadsheets/d/17HuADjw36U1ICTBMWDfxVv165mc_FXMnMt0lwNPjtcM/edit#gid=803657594


# **TASK 3️⃣**

## Subtask 1 and 2 

*Testowanie według planów testów i raportowanie błędów 👇*

https://docs.google.com/spreadsheets/d/1V-j4m7qnDQPoXOQUMJPWNt5E0gfwhbChv986K_DqNqI/edit#gid=1598039072

## Subtask 3 

*Raport z wykonanych testów 👇*

https://docs.google.com/spreadsheets/d/1MX4lhIQYoEQBU28HplEeVPpBvlNkJuf0ayz3C1pYLn0/edit#gid=0

# **TASK 4️⃣** 

## Subtask 1 and 2 

*Testowanie eksploracyjne i raportowanie błędów 👇*

https://docs.google.com/spreadsheets/d/17oFdvnihQzpErrf5bHvCi4vVh-WnUsM1zBG2FBJ7AnQ/edit#gid=0

## Subtask 3 

*Aplikacja*

*Do czego służy ta aplikacja❓ Jaki jest cel tej aplikacji❓*

Jest to wszechstronna platforma, która umożliwia zarówno kupno, jak i sprzedaż szerokiej gamy towarów. Od ubrań po samochody i przedmioty kolekcjonerskie – ta aplikacja oferuje użytkownikom zróżnicowany rynek. Jedną z jego wyróżniających się funkcji jest możliwość wyszukiwania i kupowania samochodów, a także wynajmowania i kupowania nieruchomości. Oprócz tego są tutaj publikowane oferty pracy.  Dodatkowo aplikacja zapewnia wyjątkową możliwość adopcji zwierząt, promując poczucie współczucia i troski. Co więcej, użytkownicy mogą nawet znaleźć produkty dostępne za darmo, co stanowi dodatkową warstwę wygody i przystępności cenowej. Dzięki szerokiemu zasięgowi na terenie całej Polski aplikacja ta stanowi naprawdę kompleksowe rozwiązanie dla osób chcących przeprowadzać różnorodne transakcje.

*Kto ma być użytkownikiem końcowym aplikacji❓*

Docelową grupą odbiorców tej aplikacji są przede wszystkim osoby aktywnie zaangażowane w proces zakupu lub sprzedaży towarów. Niezależnie od tego, czy chcą dokonać zakupu, czy też sprzedać własne przedmioty, ta aplikacja zaspokaja potrzeby zarówno kupujących, jak i sprzedających. Dzięki przyjaznemu dla użytkownika interfejsowi i wszechstronnym funkcjom zapewnia bezproblemową obsługę tym, którzy planują przeprowadzać transakcje.

*Czy według Ciebie aplikacja jest user friendly❓*

Według mnie aplikacja ma bardzo przyjazny interfejs, dzięki czemu nawigacja i korzystanie z niej jest niezwykle łatwe. Od chwili uruchomienia aplikacji powita Cię atrakcyjny wizualnie interfejs, który jest zarówno estetyczny, jak i funkcjonalny. Układ i organizacja funkcji zostały starannie zaprojektowane, co pozwala użytkownikom na łatwe przeglądanie aplikacji i interakcję z nią. Będąc nowicjuszem na platformie, nawigacja i maksymalne wykorzystanie jej funkcji jest niezwykle łatwe. 

*Jak byś usprawniła aplikację❓ Co byś w niej poprawiła❓ Czy masz jakiś pomysł na dodatkową funkcjonalność❓* 

Według mnie, fajną opcją byłoby dodanie możliwości wyboru języka angielskiego.

*Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej❓* 

- Platforma: Aplikacje internetowe są uruchamiane w przeglądarce internetowej i są dostępne na różnych platformach, takich jak Windows, macOS, Linux itp. Natomiast aplikacje natywne są specjalnie zaprojektowane i napisane dla konkretnej platformy, takiej jak Android, iOS, Windows itp.

- Instalacja i aktualizacje: Aplikacje natywne muszą być zainstalowane na urządzeniu użytkownika i mogą być aktualizowane poprzez sklepy aplikacji. Aplikacje internetowe nie wymagają instalacji i mogą być dostępne bezpośrednio poprzez przeglądarkę internetową, a aktualizacje są automatycznie wprowadzane przez dewelopera.


# **TASK 5️⃣**

## Subtask 1 Krótki kurs podstaw SQL (Structured Query Language (SQL) is a standardized programming language that is used to manage relational databases and perform various operations on the data in them.)

Operatory/Zapytania
- SELECT, USE, CREATE, ORDER BY, GO, GROUP BY, BETWEEN, IN, WHERE, AND, ON, FROM, LIKE, =, >, <, AS, IS NOT    

Funkcje skalarne:
- GETDATE, UPPER, LOWER, DATEDIFF

Funkcje agregujące:
- COUNT, SUM, MIN, MAX

## Subtask 3  SQL- Kilka zadań na rozgrzewkę

*👉Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.*

SELECT * 
FROM actors 
ORDER BY surname ASC;
<img width="245" alt="image" src="https://github.com/AgataSzafranek/challenge_portfolio_agata/assets/142822653/6b6c1b7b-467a-4853-8ef5-de79d60db712">

*👉Wyświetl film, który powstał w 2019 roku.*

SELECT * 
FROM movies 
WHERE year_of_production = "2019";
<img width="323" alt="image" src="https://github.com/AgataSzafranek/challenge_portfolio_agata/assets/142822653/e9c1284e-cb8b-4361-bb01-e1fa3bfc5bb1">

*👉Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.*

SELECT * 
FROM movies 
WHERE year_of_production BETWEEN 1900 AND 1999;
<img width="440" alt="image" src="https://github.com/AgataSzafranek/challenge_portfolio_agata/assets/142822653/edd3dd80-8056-4e7b-9ef6-592c2c53bf14">

*👉Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$*

SELECT title, price 
FROM movies 
WHERE price < "7";
<img width="293" alt="image" src="https://github.com/AgataSzafranek/challenge_portfolio_agata/assets/142822653/a8d1093e-b7a7-4ea9-97bb-0ff4d4c1ebe4">

*👉Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.*

SELECT * 
FROM actors 
WHERE actor_id >= 4 AND actor_id <= 7;
<img width="239" alt="image" src="https://github.com/AgataSzafranek/challenge_portfolio_agata/assets/142822653/745223d9-ebc5-40b3-bc31-688aec19e8a0">

*👉Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.*

SELECT * 
FROM customers 
WHERE customer_id IN ('2', '4', '6');
<img width="348" alt="image" src="https://github.com/AgataSzafranek/challenge_portfolio_agata/assets/142822653/d66370f9-e9c5-456b-b5d1-a3534c66a1d1">

*👉Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.*

SELECT * 
FROM customers 
WHERE customer_id IN ('1', '3', '5');
<img width="337" alt="image" src="https://github.com/AgataSzafranek/challenge_portfolio_agata/assets/142822653/0a456e77-0a72-4869-a7f3-261fae83ea2b">

*👉Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.*

SELECT * 
FROM actors 
WHERE name LIKE "An%"
<img width="222" alt="image" src="https://github.com/AgataSzafranek/challenge_portfolio_agata/assets/142822653/a145a6b3-19c5-40d1-a5be-11fdf52f5d3e">

*👉Wyświetl dane klienta, który nie ma podanego adresu email.*

SELECT * 
FROM customers 
WHERE email IS NULL
<img width="287" alt="image" src="https://github.com/AgataSzafranek/challenge_portfolio_agata/assets/142822653/9f6c2d8b-a1f0-464e-b46d-f96bb090c41f">

*👉Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.*

SELECT * 
FROM movies 
WHERE price > 9 AND movie_id BETWEEN 2 AND 8
<img width="357" alt="image" src="https://github.com/AgataSzafranek/challenge_portfolio_agata/assets/142822653/dd5d4ecc-49d1-424d-a756-c9a94d555722">

# **TASK 6️⃣**

## Subtask 1  SQL- Kilka zadań na rozgrzewkę (kontynuacja)

*👉Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd 🙈*

UPDATE customers
SET surname = 'Miler'
WHERE customer_id = 3
![image](https://github.com/AgataSzafranek/challenge_portfolio_agata/assets/142822653/8d799632-d04c-4a39-910d-06ed51df8e9d)

*👉Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.*

SELECT customers.name, customers.email
FROM customers
INNER JOIN sale ON customers.customer_id = sale.customer_id
WHERE sale.movie_id = 4
![image](https://github.com/AgataSzafranek/challenge_portfolio_agata/assets/142822653/c7cf6041-ed9e-411f-8aa9-9fe51f73f3e3)

*👉Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com*

UPDATE customers
SET email = 'pati@mail.com'
WHERE customer_id = 4
![image](https://github.com/AgataSzafranek/challenge_portfolio_agata/assets/142822653/45f6af55-1ecc-4b8f-a28d-856c1334fde9)

*👉Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).*

SELECT customers.name, customers.surname, movies.title
FROM customers
INNER JOIN sale ON customers.customer_id = sale.customer_id
INNER JOIN movies ON movies.movie_id = sale.movie_id;
![image](https://github.com/AgataSzafranek/challenge_portfolio_agata/assets/142822653/4d3667fb-087a-4921-8dfc-88bcdbcf44a1)

*👉W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag*

ALTER TABLE customers
ADD pseudonym char(3);
UPDATE customers SET pseudonym = CONCAT(LEFT(customers.name, 2), RIGHT(customers.surname, 1))
![image](https://github.com/AgataSzafranek/challenge_portfolio_agata/assets/142822653/a4c864c4-9431-4cfe-8c87-cd1b9d92f47f)

*👉Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.*

SELECT DISTINCT movies.title
FROM movies
INNER JOIN sale ON sale.movie_id=movies.movie_id
![image](https://github.com/AgataSzafranek/challenge_portfolio_agata/assets/142822653/d8ba3064-3b5c-44e5-8196-bb2df7a60bdb)

*👉Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)*

SELECT name FROM customers
UNION
SELECT name FROM actors
ORDER BY name ASC
![image](https://github.com/AgataSzafranek/challenge_portfolio_agata/assets/142822653/21fdf4fe-a490-43bc-898f-456a06e3bac9)

*👉Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).*

UPDATE movies
SET price = price + 2.5
WHERE movies.year_of_production>2000
![image](https://github.com/AgataSzafranek/challenge_portfolio_agata/assets/142822653/529abbf7-5860-4807-aa0e-2d6a6acf0b39)

*👉Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał*

SELECT actors.name, actors.surname, movies.title
FROM actors
INNER JOIN cast ON cast.actor_id = actors.actor_id
INNER JOIN movies ON movies.movie_id = cast.movie_id
WHERE actors.actor_id = 4
![image](https://github.com/AgataSzafranek/challenge_portfolio_agata/assets/142822653/288ca305-a651-4e94-8ff3-d788bc9dd917)

*👉A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa*

INSERT INTO customers (customer_id, name, surname, email, pseudonym)
VALUES (7, 'Honia', 'Stuczka-Kucharska', 'honia@mail.com', 'Hoa')
![image](https://github.com/AgataSzafranek/challenge_portfolio_agata/assets/142822653/03ea5c3e-c768-46a2-9a7d-9bf22f0880e5)

## Subtask 2 TEST

http://getistqb.com/

<img width="480" alt="image" src="https://github.com/AgataSzafranek/challenge_portfolio_agata/assets/142822653/7cbad5c4-6f1d-402f-b84e-60523fa4f9e5">














