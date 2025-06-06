#alg
- **Algoritmul lui Dijkstra** găsește cel mai scurt drum de la un nod sursă la toate celelalte noduri dintr-un graf ponderat cu **costuri pozitive**.
- Se bazează pe o [[priority queue]], unde se extrage mereu nodul cu distanța minimă curentă.
- Etichetează progresiv nodurile cu distanțele minime și actualizează vecinii.
- Complexitate: O((V + E) log V) cu [[heap binar]]; O(V²) cu matrice de adiacență.
- Aplicații: GPS, rețele, rutare, jocuri, planificare.

