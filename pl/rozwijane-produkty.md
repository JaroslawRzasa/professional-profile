# Rozwijane Produkty

Przegląd najważniejszych produktów, narzędzi i funkcjonalności, które zaprojektowałem i rozwijałem w trakcie mojej kariery. Wszystkie poniższe projekty realizowałem jako członek zespołu; zakres i charakter mojego indywidualnego wkładu w każdy z nich opisany jest przy danym produkcie.

## Puzzle Club

### Oprogramowanie do rozwiązywania łamigłówek
Oprogramowanie do rozwiązywania łamigłówek matematycznych i logicznych — implementacja algorytmów rozwiązujących w Pythonie, C# i C++.


## Comernal Software

### Cyclone REGISTER 360 PLUS
Oprogramowanie do rejestracji i przetwarzania chmur punktów ze skanów laserowych, rozwijane dla klienta Leica Geosystems (część Hexagon), wykorzystywane do dopasowywania ustawień skanów, zarządzania projektami rejestracji oraz generowania danych wyjściowych dla geodezji, budownictwa i procesów BIM/AEC. Główny wkład: rozwój nowego systemu GeoTag — w szczególności wieloaktywowych tagów (multi-asset GeoTags), pozwalających dołączyć do pojedynczego GeoTaga wiele plików, linków i materiałów multimedialnych, takich jak raporty odchyłek BIM, harmonogramy konserwacji czy informacje gwarancyjne — a także bieżące poprawianie błędów.

### Leica GR30 & GR50
Serwery referencyjne GNSS, rozwijane dla tego samego klienta, obsługujące wszystkie główne globalne konstelacje GNSS (GPS, GLONASS, Galileo, BeiDou) oraz systemy regionalne, z pełną funkcjonalnością serwera/klienta/castera NTRIP. Główny wkład: portowanie oprogramowania odbiornika z Windows CE na platformę linuksową (projekt Yocto), dodawanie obsługi nowych typów sygnałów GNSS równolegle do ich globalnego wdrażania na świecie, implementacja obsługi IPv6 oraz bieżące poprawianie błędów. Wprowadzenie automatycznych testów funkcjonalnych dla tej linii produktowej (pierwszego tego typu rozwiązania w zespole): framework testowy w Pythonie z wykorzystaniem Selenium i ChromeDriver.

### Meet and Play
Autorska gra na Androida (Nim, matematyczno-logiczna) tworzona po godzinach z trzema kolegami z Comernal Software, prowadzona jako rozwój własnego produktu. Zaprojektowanie podziału MVC między silnikiem gry w C# a warstwą prezentacji w Unity, połączenie ról Product Ownera i dewelopera oraz wydanie gry w Google Play.


## Rockwell Automation

### Binaryzacja stosu protokołu NetLinx
Refaktoryzacja firmware'u dla rodziny urządzeń ControlLogix — sterowników przemysłowych (PLC) firmy Rockwell Automation stosowanych w automatyce fabrycznej i procesowej — implementująca protokół NetLinx Unified Common Industrial Protocol i wydzielająca rdzenną bibliotekę komunikacyjną w pełni niezależną od pozostałych warstw firmware'u.


## Mentor Graphics

### Jednostka akwizycji danych (Data Acquisition Unit)
Produkt rozwijany dla Valor, izraelskiej firmy przejętej przez Mentor Graphics. Element rozwiązania SCADA — jednostka zbierająca dane z wejść i sterująca wyjściami, tłumacząca sygnały na format Open Manufacturing Language (XML/JSON) i przesyłająca je protokołem XMPP. Sprzęt oparty na procesorach Intel Quark i ARM, z dostosowanym systemem Linux zbudowanym w oparciu o projekt Yocto. Aplikacja napisana w C++ i C, zarówno w przestrzeni użytkownika, jak i jądra systemu.

### Xpedition PCB
Pozostałe funkcjonalności rozwijałem w ramach Xpedition PCB — profesjonalnego pakietu Mentor Graphics do projektowania i layoutu płytek drukowanych, wykorzystywanego przez inżynierów elektroników do projektowania PCB i obudów scalonych. Zbudowane głównie w C++ z MFC i COM (oraz OpenGL do wizualizacji 3D), dla Windows, Linux, SunOS i HP-UX (32/64-bit), z w pełni zautomatyzowanymi testami jednostkowymi i funkcjonalnymi:

- **Sterowanie widokiem i komponentami** (Display Control Dialog, Component Explorer) — dynamicznie tworzone okno dialogowe do sterowania ponad tysiącem typów elementów, z możliwością włączania/wyłączania widoczności, koloru i wzoru każdego elementu, funkcjami ulubionych, zapisu/wczytywania schematów, wyszukiwania i ukrywania elementów, uzupełnione o eksplorator komponentów do zarządzania ich rozmieszczeniem na płytce.
- **Pakiet Wirebonding** — zaawansowana funkcjonalność do projektowania i weryfikacji połączeń drutowych w obudowach scalonych: modelowanie drutów za pomocą równań parametrycznych z zaokrąglonymi narożami lub krzywymi Béziera, weryfikacja reguł projektowych w 3D (3D DRC) pod kątem zagrożeń wynikających z bliskości elementów (tryb online i wsadowy), automatyczne generowanie wzorów połączeń drutowych z pełną walidacją 3D DRC, konfigurowalne reguły dla połączeń wielodrutowych oraz obsługa układania stosów i wnęk.
- **Projektowanie RF** — generowanie przelotek (stitch via) minimalizujących straty promieniowania (wewnątrz płaszczyzn, wzdłuż konturu lub we wzorach promienistych bądź macierzowych) oraz reguły wejścia określające kierunek połączeń elementów RF, w trybie ręcznym i automatycznym.
- **Elementy bierne wbudowane** — projektowanie wbudowanych elementów biernych bezpośrednio na płytce PCB.


## Proventus sp. z o.o.

### Aplikacja do zarządzania krosownicami
Dodatkowe zlecenie, krótka umowa o dzieło (kilka tygodni, poza JDG Puzzle Club): aplikacja desktopowa dla Windows do audytowania krosownic telekomunikacyjnych, zbudowana w C++ z lokalną bazą danych SQLite. *(Dokładne daty realizacji: BRAK DANYCH.)*


## Centrum Elektryfikacji i Automatyzacji Górnictwa „EMAG” - ośrodek badawczo rozwojowy

Seria aplikacji wbudowanych i desktopowych w C/C++, wspierających bezpieczeństwo, monitoring i komunikację przemysłową w kopalniach:

- **Konsola identyfikacji połączeń** — nasłuch rozmów telefonicznych, wykrywanie przesyłanych sygnałów DTMF i prowadzenie rejestru połączeń, komunikacja z urządzeniem nasłuchowym przez port szeregowy.
- **Serwer sterowania tablicą LED** — obsługa tablicy LED w pomieszczeniu dyspozytorskim, przypisywanie diod LED do czujników.
- **Serwer komunikacyjny MODBUS** — ujednolicona biblioteka do komunikacji przez protokół Modbus.
- **System monitorowania przemieszczania się ludzi** — śledzenie lokalizacji górników w poszczególnych rejonach kopalni, z aplikacją monitorującą i rejestrem zdarzeń.
- **Iskrobezpieczny miernik teletechniczny MIT** — urządzenie do audytu linii elektrycznych w kopalni; obejmowało projekt konstrukcji mechanicznej, projekt PCB oraz oprogramowanie miernika i aplikacji na PC.
- **Biblioteka transmisji danych** — ujednolicona biblioteka komunikacyjna umożliwiająca konfigurację różnych kanałów komunikacji szeregowej.
- **Serwer dystrybucji danych** — serwer w trybie publisher-subscriber, działający pod Linuksem.
