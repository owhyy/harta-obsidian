#alg 
- **Heap binar** este o structură de date arbore complet, în care fiecare nod respectă o proprietate de **ordine parțială**:
  - **Max-heap**: fiecare nod ≥ copii săi.
  - **Min-heap**: fiecare nod ≤ copii săi.
- Implementat eficient în vectori (indexare: copil stânga 2i, copil dreapta 2i+1).
- Operații principale: `insert`, `extract-max/min`, `heapify`, toate în timp O(log n).
- Utilizat în [[HeapSort]], [[cozi cu priorități]], [[Dijkstra]], și [[algoritmi de selecție mediană]].
- Nu este o structură de căutare rapidă (nu suportă căutare eficientă ca BST).

