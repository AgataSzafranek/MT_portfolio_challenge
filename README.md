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

## Subtask 3  SQL

*👉Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.*

SELECT * FROM actors ORDER BY surname ASC;

<img width="245" alt="image" src="https://github.com/AgataSzafranek/challenge_portfolio_agata/assets/142822653/6b6c1b7b-467a-4853-8ef5-de79d60db712">


*👉Wyświetl film, który powstał w 2019 roku.*

*👉Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.*

*👉Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$*

*👉Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.*

*👉Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.*

*👉Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.*

*👉Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.*

*👉Wyświetl dane klienta, który nie ma podanego adresu email.*

*👉Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.*














