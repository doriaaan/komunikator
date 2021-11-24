# Projekt Bezpieczny Komunikator
Naszym projektem jest stworzenie bezpiecznego komunikatora, którego naszymi potencjalnymi użytkownikami zostaną żonierze wojska polskiego pracującego w MON. Celem bezpiecznego komunikatora jest wymiana treści między użytkownikami i ochrona tych wiadomości przed przechwyceniem przez obce służby. Nasz komunitor posiadać będzie szyfrowania end-to-end oraz peer-to-peer co pozwoli zagwarantować użytkowniom bezpieczną wymianę wiadomości. Nasz aplikacja nosi nazwę SafeMon. Aby zapewnić sprawne stworzenie aplikacji i zarządzanie nią potrzebujemy zatrudnić wielu wyspecjalizowanych pracowników, którzy będą odpowiedzialni za swoją część aby aplikacja powstała pomyślnie. Użytkowanie aplikacji może odbywać się przy pomocy aplikacji webowej bądż mobilnej z podziałem na android oraz ios
## Najważniejsze produkty projektu.

**1. Serwer**

Serwery bezpiecznego komunikatora dzielą się na serwer fizyczny, serwer aplikacji oraz serwer dla baz danych.
Zadaniem serwerów jest przetwarzanie oraz przechoywanie niezbędnych elementów. Serwery posiadają zaawansowane funkcje zarządzające równomiernym obciążeniem pomiędzy użytkowników oraz pozwalają na efektywniejsze zarządzanie danymi. Celem serwerów jest przechowywnie danych i zasobów oraz sprawne zarządzanie tymi zasobami. Potrzebujemy oddzielnych serwerów aby nie były mocno obciążone i funkcjonowały prawidłowo. Za sprawne zarządzanie serwerami będzie odpowiadał administrator serwerów.

**2. Baza danych**

Baza danych potrzebna jest nam do zbierania i organizowania informacji. Aby organizowanie informacji przebiegało sprawnie stworzyliśmy bazę danych zarejestrowanych użytkowników do aplikacji, bazę danych dla wiadomości, bazę danych dla plików multimedialnych, bazę danych dla systemów nadzorujących oraz dodatkowo chmurę oraz kopię zapasową w przypadku podejrzeni awarii baz. Bazy pozwalają nam przechowywnie informacji a przez wzgląd na ich podział również na sprawne zarządzanie danymi. Za bazy danych odpowiedzialny jest administrator baz danych. 

**3. Aplikacja**

Nasz bezpieczny komunikator będzie użytkowany poprzez aplikację mobilną jak i webową. Aplikacja ma za zadanie umożliwić użytkownikowi sprawne oraz bezpieczne komunikowanie się z innym użytkownikiem. Aplikacja mobilna będzie użytkowana na urządzeniach przenośnych tj. telefony. Natomiast przy użyciu komputera będzie można korzystać z aplikacji webowej jednak nie będzie ona oferowałaa tylu funkcji co aplikacja mobilna. Za aplikację odpowiedzialny będzie dział IT, a użytkować będą zarejestrowani użytkownicy. Aplikacja webowa będzie umożliwiała wysyłanie wiadomości między użytkownikami, wysyłanie multimediów oraz tworzenie grup użytkownikó. Aplikacja mobilna umożliwi użytkownikom również wysyłanie wiadomości, wysyłanie multimediów oraz tworzenie grup oraz dodatkowo nagrywanie wiadomości głosowych oraz możiwość rozmów przez transmisję video.


**4. System nadzorujący**

Ważnym produktem dla nas są również systemy nadzorujące. Wymieniliśmy trzy systemy, które każde z nich odpowiedzialne są za inną czynność. Wymienić możemy system monitoringu wydajności aplikacji, system nadzorujący zasięg aplikacji oraz system nadzorujący włamania do systemu. Ich głównym celem jest monitorowanie i kontrolowanie pracy indywidualnych elementów co ułatwi nam weryfikowanie zdobytych informacji oraz będą alarmować nas w przypadku wystąpienia określonych nieprawidłowości czy próbach włamania do systemu przez osoby nieupoważnione do tego.


**5. Proces weryfikacji**

Proces weryfikacji użytkowników będzie odbywał się po wcześniejszym sprawdzeniu ich oraz jedyną rzeczą przy rejetracji będzie podanie numeru telefonu użytkownika. Następnie na podstawie numeru służby opowiedzialne za weryfikację sprawdzą potencjalnego użytkownika. Następnie na numer telefonu zostanie wysłany specjalny kod pin bądź kod QR, którym użytkownik loguje się do aplikacji. Jednak w celu zwiększenia bezpieczeństwa przed kradzieżą konta, będzie wymagane co jakiś czas ponowne wprowadzenie kodu pin bądź QR. 

**6. Moduły aplikacji oraz zabezpieczające**

Modułysą ważnym produktem naszego projektu, gdyż to dzięki nim użytkownicy będą mogli się ze sobą wymieniać wiadomościami  oraz moduły zabezpieczające odpowiadają za bezpieczeństwo tych zasobów. Moduły aplikacji składają się z modułu zapewniającego transmisję głosu, modułu zapewniającego transmisję video, modułu zapewniającego wysyłanie oraz odbieranie wiadomości, modułu zapewniającego tworzenie grup, modułu zapewniającego przesyłanie plików, multimediów. Moduł zapezbieczający składa się szyfrowania end-to-end, szyfrowania peer-to-peer, rejestracji wyłącznie na podstawie numeru telefonu, rejestracji wyłącznie zweryfikowanych użytkowników, powiadomienia, gdy użytkownik loguje się z nowego urządzenia lub w przypadku zmiany urządzenia, opcji automatycznego usuwania rozów oraz histori po określonym czasie przez użytkownika, ustawienie zapewniające znikające wiadomości oraz zarządzanie nimi oraz tworzenie kopii zapasowej i przywracanie wiadomości.

