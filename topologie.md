#Topologie sieci

##Sieci Fizyczne


**Topologia magistrali (Bus)**:

-Opis: W tej topologii wszystkie urządzenia są podłączone do wspólnego kabla (osi), który działa jako środek transmisji danych. Sygnalizacja wędruje wzdłuż kabla i jest odbierana przez każde urządzenie.
-Wady:
W przypadku awarii kabla cała sieć przestaje działać.
Wydajność spada przy dużej liczbie urządzeń, ponieważ wszystkie muszą dzielić pasmo.
-Zalety:
Prosta do zainstalowania.
Tańsza w porównaniu do innych topologii.
Gdzie stosowane:
Często w małych sieciach lokalnych (LAN) i w starszych systemach, szczególnie tam, gdzie nie wymaga się dużych prędkości transmisji.

**Topologia pierścienia (Ring)**:

-Opis: Urządzenia są połączone w formie zamkniętego pierścienia, a dane przechodzą od jednego urządzenia do drugiego w określonym kierunku (zwykle jednokierunkowo).
-Wady:
Jeśli jedno urządzenie lub połączenie ulegnie awarii, cały system przestaje działać.
Wysoka latencja przy dużych sieciach.
-Zalety:
Przewidywalna i uporządkowana transmisja danych.
Łatwiejsze do zarządzania w mniejszych sieciach.
Gdzie stosowane:
Często stosowana w sieciach, które wymagają wysokiej niezawodności i dużych prędkości transmisji (np. sieci MAN, FDDI).

**Topologia gwiazdy (Star)**:

-Opis: Wszystkie urządzenia są podłączone do centralnego urządzenia (np. switcha, hubu). Dane są przesyłane do centralnego punktu, który kieruje je do odpowiednich urządzeń.
-Wady:
Jeśli centralne urządzenie zawiedzie, cała sieć przestaje działać.
Większe koszty związane z urządzeniem centralnym i kablowaniem.
-Zalety:
Łatwość w rozbudowie i dodawaniu nowych urządzeń.
Mniejsze zakłócenia, ponieważ urządzenia nie dzielą pasma transmisyjnego.
Gdzie stosowane:
W większości nowoczesnych sieci LAN (np. biura, szkoły, sieci domowe).

##Sieci Logiczne

**Punkt-punkt (Point-to-Point)**:

-Opis: To najbardziej podstawowy typ połączenia, w którym dwa urządzenia są bezpośrednio połączone w celu wymiany danych.
-Wady:
Ograniczona liczba urządzeń (tylko dwa urządzenia mogą się komunikować).
Trudność w rozszerzaniu sieci.
-Zalety:
Prosta i efektywna transmisja danych.
Niska latencja i wysoka wydajność.
Zastosowanie:
Wykorzystywane w połączeniach między dwoma punktami, np. połączenia między routerami, łączy dedykowane.

**Przekazywanie żetonu (Token Passing)**:

-Opis: Mechanizm zarządzania dostępem do medium transmisyjnego, w którym "żeton" (mała jednostka informacji) jest przekazywany między urządzeniami w sieci. Tylko urządzenie, które posiada żeton, może nadawać dane.
-Wady:
Może wystąpić opóźnienie, jeśli żeton jest zablokowany lub zgubiony.
Może być trudny do zaimplementowania w dużych, złożonych sieciach.
-Zalety:
Sprawiedliwy dostęp do medium, zapobiega kolizjom.
Wysoka efektywność w sieciach o dużym natężeniu ruchu.
Zastosowanie:
Używane w sieciach typu token-ring lub w protokołach zarządzających dostępem do medium w sieciach o dużym natężeniu ruchu.

**Wielodostępowa (Multiple Access)**:

-Opis: Sieć, w której wiele urządzeń ma równoczesny dostęp do tego samego medium transmisyjnego. Mechanizmy zarządzania dostępem mogą obejmować CDMA, FDMA, TDMA i inne.
-Wady:
Możliwość wystąpienia kolizji, szczególnie w systemach bez zarządzania dostępem.
W sieciach o dużym ruchu występują problemy z wydajnością.
-Zalety:
Umożliwia efektywne dzielenie medium transmisyjnego między urządzenia.
Bardzo elastyczna i skalowalna metoda komunikacji.
Zastosowanie:
W szerokopasmowych sieciach komórkowych, Wi-Fi, Ethernet, systemy satelitarne i inne, gdzie wiele urządzeń dzieli to samo medium.



