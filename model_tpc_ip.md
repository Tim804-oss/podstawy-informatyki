# Porównanie modelu OSI i TCP/IP

## Różnice między modelem OSI a TCP/IP:

| Cecha                 | Model OSI                          | Model TCP/IP                      |
|-----------------------|------------------------------------|-----------------------------------|
| Liczba warstw         | 7 warstw                           | 4 warstwy                         |
| Warstwa aplikacji     | Warstwa aplikacji, prezentacji, sesji | Tylko warstwa aplikacji          |
| Protokół              | Zawiera protokoły takie jak HTTP, FTP, SMTP, itp. w różnych warstwach | Opiera się głównie na protokołach IP, TCP, UDP |
| Podejście             | Zbudowany w sposób teoretyczny i modularny | Oparty na praktyce, protokoły skupione na komunikacji w internecie |
| Warstwa transportowa  | Podzielona na dwie warstwy (transportowa, sesji) | Obejmuje tylko jedną warstwę transportową (TCP/UDP) |

---

# Najpopularniejsze protokoły TCP/IP

- **HTTP (HyperText Transfer Protocol)** – Protokół wykorzystywany w przeglądarkach internetowych do przesyłania stron WWW.
- **FTP (File Transfer Protocol)** – Używany do przesyłania plików między komputerami.
- **SMTP (Simple Mail Transfer Protocol)** – Protokół do wysyłania e-maili.
- **TCP (Transmission Control Protocol)** – Protokół transportowy zapewniający niezawodność transmisji danych.
- **UDP (User Datagram Protocol)** – Protokół transportowy, który nie zapewnia gwarancji dostarczenia danych, ale jest szybszy od TCP.
- **IP (Internet Protocol)** – Protokół odpowiedzialny za trasowanie i adresowanie pakietów danych w sieci.

---

# Tabela z warstwami OSI

| Nazwa Warstwy        | Opis                                                         |
|----------------------|--------------------------------------------------------------|
| Warstwa aplikacji    | Umożliwia komunikację między aplikacjami. Przykłady: HTTP, FTP   |
| Warstwa prezentacji  | Odpowiada za kodowanie, kompresję i szyfrowanie danych.    |
| Warstwa sesji        | Ustanawia, utrzymuje i kończy sesje między komputerami.           |
| Warstwa transportowa | Zapewnia niezawodność transmisji danych (TCP/UDP).                  |
| Warstwa sieciowa     | Odpowiada za trasowanie danych (IP, ICMP).                 |
| Warstwa łącza danych | Odpowiada za komunikację na poziomie fizycznym (Ethernet).            |
| Warstwa fizyczna     | Zajmuje się przesyłaniem surowych danych przez medium transmisyjne.   |
