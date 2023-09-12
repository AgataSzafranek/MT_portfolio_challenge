# **TASK 1** 

## Subtask 1 

9/10

## Subtask 3

Hej!
Zdecydowałam się podjąć to wyzwanie, ponieważ chciałam doświadczyć, jak wiedzę teoretyczną można zastosować w praktyce. Byłam też bardzo ciekawa, czy moje dotychczasowe umiejętności sprawdzą się w roli testera manualnego. Zawsze fascynowało mnie nowe oprogramowanie i uwielbiam odkrywać, jak ono działa. Wydaje mi się rownież, że branża IT rozwija się cały czas, co oznacza że trzeba się rozwijać razem z nią i na pewno nie będzie to ekscytujące. Mam nadzieję, że to wyzwanie pomoże mi dowiedzieć się nieco więcej o tej roli, pozwoli mi ocenić i rozwinąć moje umiejętności oraz poprowadzi mnie we właściwym kierunku w mojej nowej karierze.

## Subtask 4 Testy eksploracyjne

*Na czym polega ta aplikacja? Do czego służy?*

Jest to aplikacja przeznaczona do zarządzania i porządkowania informacji o piłkarzach. Oferuje różne funkcje, takie jak dodawanie nowych graczy, edytowanie profili graczy i symulowanie gier. Dodatkowo aplikacja udostępnia funkcję generowania raportów, dzięki którym użytkownicy mogą przeglądać szczegółowe dane zawodników oraz historię meczów. Użytkownicy mogą także dodawać komentarze lub opisy rozegranych meczów, usprawniając ogólną analizę i dokumentację każdego meczu.

*Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a? (Nie bój się wyrażać opinię!)*

Funkcjonalności:
- dodawanie nowych graczy 
- dodawanie meczy
- rozgrywki meczu
- filtrowanie danych
- generowanie raportow z możliwością ściągnięcia raportu
- kontakt z deweloperami
- wybór języka (polski lub angielski)

Według mnie nie wszystkie funkcjonalności w aplikacji są intuicyjne, ale aplikacja jest w miare prosta w użyciu. Większość elementów jest zbudowana w taki sposób, że użytkownik jest w stanie nawigować w sposób naturalny i bez wysiłku. 

*Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?*

Aplikacja nie jest skomplikowana i dosyć prosta w użyciu. wedlug mnie ma podstawowe uzytkownosci

*Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu).*

Nawigowanie po stronie przez użytkownika jest naturalne i nie sprawia większego wysiłku, poniżej wymieniam kilka przykładów, które według mnie poprawiłyby intuicyjność aplikacji:

- Niektórym przyciskom brakuje opisów, co należy dodać dla lepszego zrozumienia i dostępności dla użytkownika.
- Obecny proces dodawania graczy pozwala na przesłanie nieprawidłowych informacji bez stosowania żadnej logiki sprawdzania danych. Wdrożenie walidacji danych pomogłoby zapewnić akceptowanie wyłącznie ważnych informacji. Aby pomóc w sprawdzaniu poprawności danych, dobrą opcią byłoby wdrożenie menu rozwijanych, które pomogą użytkownikom wybrać prawidłowe opcje i zmniejszyć prawdopodobieństwo błędów podczas wprowadzania danych.
- Korzystne byłoby ulepszenie strony głównej poprzez umożliwienie użytkownikom klikania górnych pól (liczba zawodników, mecze, raporty, akcje) i przekierowania do odpowiedniej sekcji raportów w celu łatwiejszej nawigacji.
- Po prawej stronie pole „aktywność” powinno wyłączać automatyczną edycję danych po kliknięciu, umożliwiając edycję dopiero po wybraniu odpowiedniej opcji.
  

*Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. Tutaj masz na to miejsce, czas i przestrzeń! ;)*

- generowanie raportów- można ściągnąć tylko jedną stronę, powinna być możliwość ściągnięcia całej bazy danych (ułatwiłoby to przegląd całej bazy danych)
- podczas użytkowania aplikacji w języku angielskim znajdujemy słówka, które nie zostały przetłumaczone i vice versa
- podczas wypełniania informacji o graczu wyskakuje błąd, że nie udało się dodać gracza, jednak nie wiemy jaki błąd i jakie okienko trzeba wypełnić
- możliwość dodania gracza, który się jeszcze nie urodzi- sugeruję ograniczenie do dat przyszłych
- Pole waga/wzrost pozwala na wprowadzenie wartości ujemnych, które należy ograniczyć.
- W formularzu dodawania gracza istnieje możliwość dodania języka- sugeruje dołączenie listy rozwijanej języków, aby zapewnić prawidłowe wpisy.
- Opcja „telefon” pozwala na wprowadzanie liter, które powinny być ograniczone wyłącznie do cyfr.
- W opcjach dodawania linków do YouTube i Facebooka nie ma ograniczeń formatu - według mnie ograniczenie formatu do prawidłowych linków do stron internetowych i zapewnienie możliwości przekierowania byłoby ulepszeniem
- Aplikacja pozwala na wpisanie cyfr wyłącznie w polach imienia i nazwiska, które należy ograniczyć do liter.




