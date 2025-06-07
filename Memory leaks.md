#PL 
- Un **memory leak** apare când memoria alocată dinamic nu mai este accesibilă, dar **nu a fost eliberată**.
- Se acumulează în [[heap]] și poate duce la **scăderea performanței** sau **blocarea aplicației** (în timp).
- Cauze frecvente: lipsa `delete`/`free`, uitarea de a elibera resurse după excepții sau ieșire din funcție.
- Detectarea e dificilă manual – se recomandă instrumente ca **Valgrind**, **AddressSanitizer** sau compilatoare cu warning-uri.
- Esențial în aplicații cu rulare lungă (servere, sisteme embedded).

