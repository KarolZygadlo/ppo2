## Estymowanie i specyfikowanie projektów

### Estymowanie projektów programistycznych

Estymowanie projektów programistycznych to proces przewidywania ilości pracy, czasu i zasobów potrzebnych do zrealizowania projektu. Jest to kluczowy element planowania i zarządzania projektem, który umożliwia ocenę zakresu prac i ich kosztów. 
#### Praktyczne aspekty estymacji

Podczas estymacji projektów programistycznych należy brać pod uwagę różne praktyczne aspekty, takie jak:

- **Ryzyko**: Wszelkie potencjalne zagrożenia, które mogą wpłynąć na harmonogram projektu, powinny być uwzględnione podczas estymacji.
- **Niepewność**: Estymacja zawsze wiąże się z pewnym stopniem niepewności, dlatego ważne jest, aby uwzględniać ten fakt i pozostawiać pewien margines błędu przy określaniu czasu i zasobów potrzebnych do realizacji projektu.

### Planning Poker - jedna z wielu metod wykorzystywanych podczas planowania

#### Jak działa Planning Poker

Planning Poker, znany również jako Scrum Poker, jest popularną techniką szacowania wykorzystywaną w metodykach zwinnych (agile), takich jak Scrum, do oceny skomplikowania zadań lub czasu potrzebnego na ich realizację. Jest to interaktywna i demokratyczna metoda, która pozwala zespołowi osiągnąć konsensus w kwestii zakresu prac związanych z różnymi funkcjami projektu.

#### Proces Planning Poker

1. **Prezentacja zadania:** Scrum Master lub lider projektu przedstawia i wyjaśnia zadanie, które ma być oszacowane. W tym czasie członkowie zespołu mogą zadawać pytania dotyczące szczegółów zadania, aby lepiej je zrozumieć.
2. **Dyskusja:** Członkowie zespołu dyskutują o zadaniu, dzieląc się swoimi opiniami i doświadczeniami. Ważne jest, aby każdy członek miał możliwość wyrażenia swoich przemyśleń, co pomaga w lepszym zrozumieniu problemu.
3. **Szacowanie:** Każdy członek zespołu wybiera kartę z zestawu Planning Poker, która reprezentuje jego szacunek dotyczący złożoności zadania. Karty mają na ogół numery odpowiadające serii Fibonacciego (1, 2, 3, 5, 8, 13, 21, itd.), co ma na celu odzwierciedlenie niepewności i nieliniowego charakteru wzrostu trudności zadań.
4. **Odsłonięcie kart:** Wszyscy członkowie zespołu jednocześnie odsłaniają swoje karty. Ta technika zapobiega wpływaniu na siebie nawzajem przed podjęciem decyzji.
5. **Dyskusja i ponowne szacowanie:** Jeżeli szacunki różnią się znacznie, członkowie zespołu, którzy wybrali najwyższe i najniższe wartości, wyjaśniają swoje wybory. Następnie zespół może przeprowadzić kolejną rundę dyskusji i ponownie szacować, aby zbliżyć się do wspólnego konsensusu.
6. **Zatwierdzenie szacunku:** Proces powtarza się, aż do momentu, kiedy zespół osiągnie konsensus w zakresie szacunków lub zdecyduje się przyjąć wartość kompromisową.

#### Korzyści z wykorzystania tej metody

- **Zwiększenie zaangażowania zespołu:** Każdy członek ma możliwość wyrażenia swojej opinii, co wzmacnia poczucie współodpowiedzialności.
- **Lepsze zrozumienie projektu:** Dyskusje pomagają ujawnić różne aspekty i potencjalne problemy zadania.
- **Optymalizacja szacunków:** Używanie serii Fibonacciego pomaga w oszacowaniu złożoności zadania, a nie bezpośrednio czasu potrzebnego na jego wykonanie, co jest bardziej adekwatne w zmiennych warunkach projektów.

Planning Poker jest cennym narzędziem, które pozwala na efektywne i dokładne szacowanie pracy, co jest kluczowe dla sukcesu projektów prowadzonych w metodyce zwinnej. Dla tych, którzy szukają odpowiedniego narzędzia do przeprowadzania sesji Planning Poker, polecam skorzystać z dostępnej online platformy na [PlanningPokerOnline.com](https://planningpokeronline.com/).

## Specyfikowanie projektów programistycznych

Specyfikowanie projektów programistycznych odgrywa kluczową rolę w rozwoju oprogramowania, stanowiąc fundament dla efektywnej realizacji i zarządzania projektem. Jest to proces, który precyzuje, co ma być zbudowane, jakie funkcje będzie posiadało oprogramowanie oraz jakie są oczekiwania wobec jego działania i jakości. Odpowiednio przygotowana specyfikacja pomaga zminimalizować ryzyko nieporozumień pomiędzy zespołem developerskim a klientem, a także zapewnia, że wszystkie strony zgadzają się co do zakresu i celów projektu.

### Znaczenie specyfikacji projektu

Specyfikacja projektu jest nie tylko dokumentem technicznym, ale również kontraktowym punktem odniesienia, który gwarantuje, że realizowane prace są zgodne z oczekiwaniami klienta oraz standardami branżowymi. Dokument ten jest szczególnie istotny w przypadku dużych projektów, gdzie złożoność i liczba zaangażowanych osób wymaga precyzyjnego określenia zadań i celów. Specyfikacja zapewnia także bazę do oceny postępów i jakości wykonania, umożliwiając systematyczną weryfikację osiągniętych rezultatów względem założonych wymagań.

### Elementy składowe specyfikacji

Specyfikacja projektu powinna zawierać różne elementy, które razem tworzą pełny obraz wymagań i oczekiwań:

#### Wymagania funkcjonalne

To opis funkcji, które ma realizować system lub aplikacja. Wymagania funkcjonalne definiują działania, które użytkownik końcowy będzie mógł wykonać za pomocą oprogramowania, np. rejestracja, logowanie, przetwarzanie danych, generowanie raportów. Są one kluczowe dla zrozumienia, jak aplikacja ma działać z perspektywy użytkownika.

#### Wymagania niefunkcjonalne

Dotyczą jakości i standardów, które muszą być spełnione przez system, takich jak wydajność, bezpieczeństwo, skalowalność, czy kompatybilność. Wymagania te są równie ważne, ponieważ określają, jak oprogramowanie powinno się zachowywać w różnych warunkach i środowiskach, co ma bezpośredni wpływ na doświadczenia użytkowników i niezawodność systemu.

#### Inne elementy

Dodatkowo, specyfikacja może zawierać diagramy, takie jak diagramy przypadków użycia, diagramy przepływu danych czy diagramy klas, które wizualizują i precyzują architekturę systemu. Mogą również być uwzględnione scenariusze testowe, kryteria akceptacji, a także przewidywane ograniczenia technologiczne i operacyjne.

### Proces tworzenia specyfikacji

Proces tworzenia specyfikacji projektu wymaga współpracy między wszystkimi zaangażowanymi stronami:

1. **Zbieranie wymagań:** Rozmowy z klientem oraz innymi interesariuszami w celu zrozumienia ich potrzeb i oczekiwań. W tej fazie często korzysta się z technik takich jak wywiady, ankiety, warsztaty czy sesje burzy mózgów.
2. **Analiza wymagań:** Weryfikacja zebranych danych i ich klasyfikacja. W tym etapie analizuje się możliwości techniczne realizacji oraz ocenia potencjalne ryzyka.
3. **Dokumentowanie wymagań:** Przygotowanie formalnego dokumentu specyfikacji, który jest jasny, zrozumiały i wolny od sprzeczności. Ważne jest, aby specyfikacja była czytelna nie tylko dla programistów, ale także dla osób nieposiadających technicznego wykształcenia.
4. **Weryfikacja i akceptacja specyfikacji:** Specyfikacja powinna być zatwierdzona przez wszystkie strony przed rozpoczęciem właściwych prac programistycznych. Ten etap zapewnia, że wszelkie nieścisłoNależy:ści lub błędy są poprawione, a dokument odzwierciedla rzeczywiste potrzeby i oczekiwania.

### Zadanie do wykonania:

Proszę o wykonanie następujących czynności:

1. **Estymacja czasu i nakładu pracy**: Ustalenie przewidywanego czasu oraz nakładu pracy potrzebnego do zrealizowania projektu w ramach kursu "Projektowanie i programowanie systemów internetowych I".
3. **Specyfikacja projektu**: Opracowanie dokładnej specyfikacji projektu, która powinna obejmować szczegółowy opis wymagań funkcjonalnych oraz niefunkcjonalnych.
4. **Zarządzanie dokumentacją**: Umieszczenie gotowych dokumentów w odpowiednio zorganizowanych katalogach w repozytorium Git. Zaleca się utrzymanie porządku i przejrzystości struktury folderów.