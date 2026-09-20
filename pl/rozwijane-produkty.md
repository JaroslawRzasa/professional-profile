# Rozwijane Produkty

Przegląd najważniejszych produktów, narzędzi i funkcjonalności, które zaprojektowałem i rozwijałem w trakcie mojej kariery. Wszystkie poniższe projekty realizowałem jako członek zespołu, jednak mój udział był znaczący — w większości z nich wręcz wiodący.

## Puzzle Club

### Oprogramowanie do rozwiązywania łamigłówek
Oprogramowanie do rozwiązywania łamigłówek matematycznych i logicznych — implementacja algorytmów rozwiązujących w Pythonie, C# i C++.


## Rockwell Automation

### Binaryzacja stosu protokołu NetLinx
Refaktoryzacja firmware'u dla rodziny urządzeń ControlLogix, implementująca protokół NetLinx Unified Common Industrial Protocol i wydzielająca rdzenną bibliotekę komunikacyjną w pełni niezależną od pozostałych warstw firmware'u.


## Mentor Graphics

### Jednostka akwizycji danych (Data Acquisition Unit)
Element rozwiązania SCADA — jednostka zbierająca dane z wejść i sterująca wyjściami, tłumacząca sygnały na format Open Manufacturing Language (XML/JSON) i przesyłająca je protokołem XMPP. Sprzęt oparty na procesorach Intel Quark i ARM, z dostosowanym systemem Linux zbudowanym w oparciu o projekt Yocto. Aplikacja napisana w C++ i C, zarówno w przestrzeni użytkownika, jak i jądra systemu.

### Xpedition PCB – sterowanie widokiem i komponentami
Dynamicznie tworzone okno dialogowe do sterowania ponad tysiącem typów elementów w Xpedition PCB, z możliwością włączania/wyłączania widoczności, koloru i wzoru każdego elementu, a także funkcjami ulubionych, zapisu/wczytywania schematów, wyszukiwania i ukrywania elementów. Uzupełnione o eksplorator komponentów do zarządzania ich rozmieszczeniem na płytce. Zbudowane w C++, MFC i COM, dla Windows i Linux (32/64-bit); testowanie w pełni zautomatyzowane.
Demo: https://www.youtube.com/watch?v=tRvLLJtTwW4&feature=youtu.be

### Xpedition PCB – pakiet Wirebonding
Zaawansowana funkcjonalność do projektowania i weryfikacji połączeń drutowych w obudowach scalonych:
- Modelowanie drutów za pomocą równań parametrycznych, z zaokrąglonymi narożami lub krzywymi Béziera
- Weryfikacja reguł projektowych w 3D (3D DRC) pod kątem zagrożeń wynikających z bliskości elementów, w trybie online i wsadowym
- Automatyczne generowanie wzorów połączeń drutowych z pełną walidacją 3D DRC
- Konfigurowalne reguły i parametry dla połączeń wielodrutowych
- Obsługa układania stosów (die stacking) i wnęk (cavities)

Zbudowane w C++, MFC, COM i OpenGL, dla Windows, Linux, SunOS i HP-UX (32/64-bit); w pełni zautomatyzowane testy jednostkowe i funkcjonalne.
Demo: https://youtu.be/xMeAEk12Yfw

### Xpedition PCB – projektowanie RF
Funkcjonalność do projektowania elementów wielkiej częstotliwości (RF) na płytce PCB:
- Generowanie przelotek (stitch via) minimalizujących straty promieniowania, rozmieszczanych wewnątrz płaszczyzn, wzdłuż konturu lub we wzorach promienistych bądź macierzowych
- Reguły wejścia określające kierunek połączeń elementów RF, w trybie ręcznym i automatycznym

Zbudowane w C++, MFC i COM, dla Windows, Linux, SunOS i HP-UX (32/64-bit); w pełni zautomatyzowane testy jednostkowe i funkcjonalne.
Demo: https://youtu.be/qaeOii1rLN0

### Xpedition PCB – elementy bierne wbudowane
Funkcjonalność do projektowania wbudowanych elementów biernych bezpośrednio na płytce PCB. Zbudowane w C++, MFC i COM, dla Windows, Linux, SunOS i HP-UX (32/64-bit); w pełni zautomatyzowane testy jednostkowe i funkcjonalne.


## Proventus sp. z o.o. *(dodatkowe zlecenie, kontrakt B2B)*

### Aplikacja do zarządzania krosownicami
Aplikacja desktopowa dla Windows do audytowania krosownic telekomunikacyjnych, zbudowana w C++ z lokalną bazą danych SQLite.


## Centrum Elektryfikacji i Automatyzacji Górnictwa „EMAG” - ośrodek badawczo rozwojowy

Seria aplikacji wbudowanych i desktopowych w C/C++, wspierających bezpieczeństwo, monitoring i komunikację przemysłową w kopalniach:

- **Konsola identyfikacji połączeń** — nasłuch rozmów telefonicznych, wykrywanie przesyłanych sygnałów DTMF i prowadzenie rejestru połączeń, komunikacja z urządzeniem nasłuchowym przez port szeregowy.
- **Serwer sterowania tablicą LED** — obsługa tablicy LED w pomieszczeniu dyspozytorskim, przypisywanie diod LED do czujników.
- **Serwer komunikacyjny MODBUS** — ujednolicona biblioteka do komunikacji przez protokół Modbus.
- **System monitorowania przemieszczania się ludzi** — śledzenie lokalizacji górników w poszczególnych rejonach kopalni, z aplikacją monitorującą i rejestrem zdarzeń.
- **Iskrobezpieczny miernik teletechniczny MIT** — urządzenie do audytu linii elektrycznych w kopalni; obejmowało projekt konstrukcji mechanicznej, projekt PCB oraz oprogramowanie miernika i aplikacji na PC.
- **Biblioteka transmisji danych** — ujednolicona biblioteka komunikacyjna umożliwiająca konfigurację różnych kanałów komunikacji szeregowej.
- **Serwer dystrybucji danych** — serwer w trybie publisher-subscriber, działający pod Linuksem.
