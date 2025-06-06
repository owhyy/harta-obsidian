 #ds 
- O structură de date reprezintă o modalitate de **organizare logică a datelor** astfel încât acestea să poată fi procesate eficient de algoritmi.
- Este baza oricărui sistem informatic eficient – de la [[baze de date]], până la [[Sistem de operare|sisteme de operare]] și aplicații web.

### Clasificare:

- [[Structuri liniare]]: datele sunt stocate secvențial (ex: [[Vector]], [[Listă]], [[Stivă]], [[coadă]]).
- [[Structuri neliniare]]: datele sunt legate ierarhic sau rețele (ex: [[arbore]], [[graf]]).
- [[Structuri dinamice]] vs [[statice]]: în funcție de modul de alocare a memoriei.
- [[Structuri de acces direct]] (ex: [[hash table]]) vs [[secvențiale]] (ex: listă înlănțuită).

### Exemple importante:

- **Vectori**: acces rapid O(1), dar inserarea/ștergerea costă O(n).
- **Liste înlănțuite**: inserare eficientă, dar accesul e lent.
- **Stivă** (LIFO): folosită în [[recursivitate]], parsări, backtracking.
- **Cozi** (FIFO): utilizate în [[BFS]], [[sisteme de operare]], [[streaming]].
- **Arbori**: folosiți în reprezentarea ierarhiilor, [[BST]], [[AVL]], [[heap]].
- **Grafuri**: pentru rețele, rute, relații complexe.
- **Hash table**: acces foarte rapid, ideal pentru mapare și căutare.

### Relevanță:

- Alegerea unei structuri greșite duce la performanțe slabe chiar și cu un algoritm bun.
- Fiecare structură are operații caracteristice cu **complexități** diferite (ex: O(1), O(n), O(log n)).
- În [[interviuri tehnice]] și [[competiții de programare]], înțelegerea profundă a acestora e esențială.
- Combinarea inteligentă a mai multor structuri este frecventă în proiecte reale.

