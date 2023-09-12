# **TASK 1** 

## Subtask 1 

9/10

## Subtask 3

Hej!
Zdecydowałam się podjąć to wyzwanie, ponieważ chciałam doświadczyć, jak wiedzę teoretyczną można zastosować w praktyce. Byłam też bardzo ciekawa, czy moje dotychczasowe umiejętności sprawdzą się w roli testera manualnego. Zawsze fascynowało mnie nowe oprogramowanie i uwielbiam odkrywać, jak ono działa. Wydaje mi się rownież, że branża IT rozwija się cały czas, co oznacza że trzeba się rozwijać razem z nią i na pewno będzie to ekscytujące. Mam nadzieję, że to wyzwanie pomoże mi dowiedzieć się nieco więcej o tej roli, pozwoli mi ocenić i rozwinąć moje umiejętności oraz poprowadzi mnie we właściwym kierunku w mojej nowej karierze.

## Subtask 4 Testy eksploracyjne

*Na czym polega ta aplikacja? Do czego służy?*

Jest to aplikacja przeznaczona do zarządzania i porządkowania informacji o piłkarzach. Oferuje różne funkcje, takie jak dodawanie nowych graczy, edytowanie profili graczy i symulowanie gier. Dodatkowo aplikacja udostępnia funkcję generowania raportów, dzięki którym użytkownicy mogą przeglądać szczegółowe dane zawodników oraz historię meczów. Użytkownicy mogą także dodawać komentarze lub opisy rozegranych meczów, usprawniając ogólną analizę i dokumentację każdego meczu.


*Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a? (Nie bój się wyrażać opinię!)*

Lista funkcjonalności:
- Dodawanie nowych graczy.
- Dodawanie meczy.
- Zarządzanie rozgrywkami meczów.
- Możliwość filtrowania danych.
- Generowanie raportów z opcją pobrania.
- Kontakt z zespołem deweloperskim.
- Wybór języka (polski lub angielski).
  

*Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?*

Interfejs aplikacji jest łatwy w obsłudze. Choć nie jest on zbyt intuicyjny pod względem poruszania się, to jednak spełnia większość swoich funkcji co stanowi kluczowy element pozytywnego doświadczenia użytkownika. Pod względem wizualnym nie jest to aplikacja zaawansowana. Niemniej jednak, priorytetem jest zapewnienie użytkownikom wygodnego korzystania z niej.


*Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu).*

Według mnie, nie wszystkie funkcjonalności aplikacji są intuicyjne, ale ogólnie aplikacja jest dość prosta w obsłudze. Większość elementów została zaprojektowana w sposób umożliwiający użytkownikom naturalne poruszanie się po niej bez większego wysiłku. Niemniej jednak, wprowadzenie kilku zmian mogłoby poprawić intuicyjność i interfejs aplikacji. Poniżej podaje kilka przykładów, które ulepszyłyby aplikacje:

- Niektórym przyciskom brakuje opisów, co należy dodać dla lepszego zrozumienia i dostępności dla użytkownika mam tutaj na myśli kiedy przechodzimy do zakładki mecze i odgrywamy grę, dla niektorych użytkowników mogą być niezrozumiałe
- Obecny proces dodawania graczy pozwala na przesłanie nieprawidłowych informacji bez stosowania żadnej logiki sprawdzania danych. Wdrożenie walidacji danych pomogłoby   zapewnić akceptowanie wyłącznie ważnych informacji. Aby pomóc w sprawdzaniu poprawności danych, dobrą opcią byłoby wdrożenie "menu rozwijane", które pomoże użytkownikom wybrać prawidłowe opcje i zmniejszyć prawdopodobieństwo błędów podczas wprowadzania danych.
- Korzystne byłoby ulepszenie strony głównej poprzez umożliwienie użytkownikom klikania górnych pól (liczba zawodników, mecze, raporty, akcje) i przekierowania do         odpowiedniej sekcji raportów w celu łatwiejszej nawigacji.
- Po prawej stronie pole „aktywność” przechodzimy do edytowania, według mnie należy wyłączyć automatyczną edycję danych po kliknięciu i zmianę na wyłacznie na podgląd, umożliwiając edycję dopiero po wybraniu odpowiedniej opcji.
- Brakuje w menu zakładki z "meczami", która pojawia się dopiero po dodaniu gracza

  
*Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. Tutaj masz na to miejsce, czas i przestrzeń! ;)*

- generowanie raportów- można ściągnąć tylko jedną stronę, powinna być możliwość ściągnięcia całej bazy danych (ułatwiłoby to przegląd całej bazy danych offline np w programie excel)
- podczas użytkowania aplikacji w języku angielskim znajdujemy słówka, które nie zostały przetłumaczone i vice versa
- podczas wypełniania informacji o graczu wyskakuje błąd, że nie udało się dodać gracza, jednak nie wiemy jaki błąd i jakie okienko trzeba wypełnić (zdarza się to podczas podania nieprawidłowego formatu email)
- możliwość dodania gracza z przyszłości, oznaczam to jako błąd
- Pole waga/wzrost pozwala na wprowadzenie wartości ujemnych, które należy ograniczyć.
- Opcja „telefon” pozwala na wprowadzanie liter, które powinny być ograniczone wyłącznie do cyfr.
- Aplikacja pozwala na wpisanie cyfr w polach imienia i nazwiska, które należy ograniczyć do liter.
- W opcjach dodawania linków do YouTube i Facebooka nie ma ograniczeń formatu - według mnie ograniczenie formatu do prawidłowych linków do stron internetowych i zapewnienie  możliwości przekierowania byłoby ulepszeniem
- Podczas kiedy przechodzimy do zakładki "mecze" opcje które są nieopisane (graj, pauza, cofnij, raport, usuń) niektóre z nich nie działają - opcja cofnij i usuń
- nie ma możliwości wglądu raportów meczy
- w opcji dodawania nowego meczu jest możliwość dodania numeru w polu "kolor koszulki", w polu "czas gry" możemy wpisać np -1, według mnie należy tutaj zastosować "menu rozwijane"




