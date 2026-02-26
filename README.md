# Talk & NameServer - Socket Programming

Dette projekt er resultatet af en workshop i socket-programmering på 3. semester. Formålet var at opbygge en dybdegående forståelse for netværkskommunikation og distribuerede systemer gennem implementering af en chat-klient og en tilhørende navneservice.

## Funktioner
* **Multi-threaded Chat:** Implementering af en Talk-klient/server, der via trådhåndtering (`SenderTråd` og `RecieverTråd`) tillader asynkron beskedudveksling (full-duplex).
* **TCP & UDP Implementering:** Erfaring med både forbindelsesorienteret (TCP) og forbindelsesløs (UDP) kommunikation.
* **NameServer (Service Discovery):** En central navneservice, der holder styr på aktive klienters netværksidentifikation, så brugere kan finde hinanden via kaldenavne frem for IP-adresser.
* **Client Handling:** Server-logik der kan håndtere flere klienter samtidigt via dedikerede `ClientHandlers`.

## Teknologier
* **Sprog:** Java
* **Netværk:** Java Sockets (TCP/UDP), IP/Port håndtering
* **Concurrency:** Java Threads (Multi-threading)
* **Værktøjer:** IntelliJ IDEA, Git

## Struktur
Projektet er opdelt i iterationer:
1. **Version 1:** Simpel sekventiel TCP-chat.
2. **Version 2:** Trådbaseret chat for samtidig afsendelse/modtagelse.
3. **Version 3:** Integration af navneservice med både TCP og UDP understøttelse.

## Forfattere
Karsten Kirkegaard, Rune Hyldgaard Jensen og Sidse Borch Mogensen
