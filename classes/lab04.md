## Techniczna dokumentacja projektu

### Krótkie wprowadzenie do znaczenia technicznej dokumentacji w projektach programistycznych

Dokumentacja techniczna jest kluczowym elementem każdego projektu programistycznego. Ułatwia zrozumienie, utrzymanie i rozwój oprogramowania, a także wspiera współpracę w zespołach programistycznych.

### Omówienie celu dokumentacji kodu

Głównymi celami dokumentacji kodu są:

- **Ułatwienie zrozumienia kodu:** Dobrze udokumentowany kod jest znacznie łatwiejszy do zrozumienia dla nowych członków zespołu oraz osób postronnych, co jest szczególnie ważne w przypadku długotrwałych projektów.

- **Wsparcie procesu utrzymania i rozwoju oprogramowania:** Aktualna dokumentacja ułatwia wprowadzanie zmian, aktualizacje oraz rozwiązywanie problemów związanych z kodem.

- **Ułatwienie współpracy w zespole:** Dokumentacja pomaga zespołom programistycznym efektywnie współpracować, zapewniając jednolite zrozumienie struktury i funkcji kodu.

### Dokumentowanie kodu

Dokumentowanie kodu jest nieodzownym elementem tworzenia oprogramowania. Nie tylko ułatwia zrozumienie kodu osobom, które z nim pracują, ale także stanowi kluczowe źródło informacji dla każdego, kto będzie potrzebował modyfikować lub analizować kod w przyszłości. Dobrze udokumentowany kod może znacznie przyspieszyć proces wdrażania nowych programistów do projektu oraz pomóc w zachowaniu spójności i jakości kodu w czasie.

#### Metody dokumentowania kodu

1. **Komentarze w kodzie:** Jednym z podstawowych sposobów dokumentowania jest używanie komentarzy. Dobre komentarze wyjaśniają "dlaczego" coś zostało zrobione, a nie tylko "co" zostało zrobione. Ważne jest, aby komentarze były zwięzłe i na temat, aby nie zaśmiecały kodu.

2. **Nazewnictwo funkcji i zmiennych:** Jasne i zrozumiałe nazewnictwo jest samym w sobie formą dokumentacji. Nazwy funkcji i zmiennych powinny odzwierciedlać ich przeznaczenie i sposób użycia. Dobrym zwyczajem jest stosowanie konwencji nazewnictwa, która jest spójna w całym projekcie.

3. **Struktura kodu:** Czytelna struktura kodu pomaga w jego zrozumieniu. Użycie odpowiednich wcięć, separacja bloków kodu i logiczne grupowanie funkcji mogą znacznie ułatwić nawigację po kodzie.

#### Przegląd narzędzi

Programiści mają do dyspozycji wiele narzędzi, które automatyzują proces tworzenia dokumentacji z komentarzy umieszczonych w kodzie. Oto kilka popularnych narzędzi, każde z nich dedykowane dla różnych języków programowania:

1. **phpDocumentor:**
   - **Język:** PHP
   - **Opis:** phpDocumentor to narzędzie do generowania dokumentacji dla PHP, które analizuje komentarze w stylu PHPDoc, generując z nich dokumentację. Umożliwia tworzenie szczegółowych opisów klas, metod i zmiennych.

2. **Doxygen:**
   - **Język:** C++, C, Java, Objective-C, Python, i inne
   - **Opis:** Doxygen jest narzędziem do tworzenia dokumentacji dla kodu napisanego w wielu językach. Pozwala na generowanie dokumentacji z adnotacji w kodzie, wspierając różne formaty wyjściowe.

3. **pydoc:**
   - **Język:** Python
   - **Opis:** pydoc to narzędzie w Pythonie do generowania dokumentacji z komentarzy w kodzie. Może tworzyć dokumentację w formie tekstowej lub HTML.

### Zadanie do wykonania:

Należy:

- Pobrać ze swojego repozytorium jeden z programów (od laboratorium piątego i wzwyż) zaimplementowanych na zajęciach z Projektowania i programowania obiektowego I: **Projektowania i programowania obiektowego I**.
- Udokumentować zgodnie z zasadami języka kod wybranego programu; 
- Za pomocą phpDocumentora, Doxygenu, pydoca lub dowolnego innego generatora dokumentacji wytworzyć dokumentację wybranego programu;
- Gotową dokumentację dołączyć do repozytorium Git; zalecane jest uporządkowanie zadań w odpowiadającym im katalogach