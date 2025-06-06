#PL 

- Un **dangling pointer** este un pointer care **referă o zonă de memorie invalidă** – adică a fost eliberată sau nu mai aparține programului.
- Apare frecvent după `delete` / `free`, dacă pointerul nu e setat apoi la `nullptr`.
- Orice acces ulterior produce comportament **nedefinit**: blocări, coruperi de memorie, segfault.
- Exemplu clasic: `int* p = new int(5); delete p; *p = 10; // pericol!`
- Sunt greu de depistat și pot cauza **buguri intermitente** foarte greu de reprodus.

