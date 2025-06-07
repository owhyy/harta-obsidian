
O **hash table** este o structură de date care stochează perechi **cheie-valoare** și permite **acces rapid** la date pe baza unei chei, folosind o funcție de dispersie (**hash function**).

Este una dintre cele mai eficiente structuri pentru operații de **căutare, inserare și ștergere** – în medie în **timp constant** O(1).

## Cum funcționează

1. Cheia este transmisă printr-o **funcție de hash**: `h(key)`
2. Funcția returnează un **index** într-un array intern
3. Valoarea este stocată la poziția respectivă

## Operații

- `insert(key, value)`
- `get(key)` – returnează valoarea asociată
- `delete(key)`