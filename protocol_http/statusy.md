/**
 * Grupy statusów HTTP:
 * 
 * 1XX Informacyjne:
 * - 100 Continue: Serwer otrzymał początkową część żądania i klient może kontynuować przesyłanie.
 * - 101 Switching Protocols: Serwer akceptuje żądanie zmiany protokołu.
 * - 102 Processing: Serwer przetwarza żądanie, ale nie ma jeszcze odpowiedzi.
 * 
 * 2XX Sukces:
 * - 200 OK: Żądanie zakończone sukcesem.
 * - 201 Created: Żądanie zakończone sukcesem i utworzono nowy zasób.
 * - 202 Accepted: Żądanie zaakceptowane do przetworzenia, ale jeszcze nie zakończone.
 * - 204 No Content: Żądanie zakończone sukcesem, ale brak treści do zwrócenia.
 * 
 * 3XX Przekierowania:
 * - 301 Moved Permanently: Zasób został trwale przeniesiony pod nowy URL.
 * - 302 Found: Zasób tymczasowo dostępny pod innym URL.
 * - 304 Not Modified: Zasób nie został zmodyfikowany od ostatniego żądania.
 * 
 * 4XX Błędy klienta:
 * - 400 Bad Request: Żądanie nie może być przetworzone z powodu błędu klienta.
 * - 401 Unauthorized: Brak autoryzacji do zasobu.
 * - 403 Forbidden: Dostęp do zasobu jest zabroniony.
 * - 404 Not Found: Zasób nie został znaleziony.
 * 
 * 5XX Błędy serwera:
 * - 500 Internal Server Error: Ogólny błąd serwera.
 * - 501 Not Implemented: Serwer nie obsługuje żądanej funkcjonalności.
 * - 502 Bad Gateway: Błąd bramki lub serwera pośredniczącego.
 * - 503 Service Unavailable: Serwer jest tymczasowo niedostępny.
 */