**Structurile de acces direct** sunt structuri de date care permit accesul la un element într-un timp constant sau foarte apropiat de constant, fără a fi necesară parcurgerea secvențială a datelor.

Sunt utilizate acolo unde este esențială **viteza mare de căutare, inserare sau actualizare**, de exemplu în tabele de simboluri, cache-uri sau indexuri de baze de date.

## Exemple principale

### 1. **Tablouri ([[Tablou|arrays]])**
- Acces direct prin index: `A[i]`
- Timp de acces: **O(1)**
- Necesită spațiu continuu în memorie

### 2. **Tabele de dispersie (hash tables)**
- Utilizează o **funcție de hash** pentru a calcula adresa (indicele) elementului
- Pot exista **coliziuni** – gestionate prin chaining sau open addressing
- Operații tipice: `insert`, `search`, `delete` – în medie **O(1)**