#alg 
- **Topological Sort** produce o ordonare liniară a nodurilor dintr-un graf orientat aciclic (DAG), astfel încât fiecare muchie `u → v` respectă `u înaintea lui v`.
- Se aplică doar pe [[DAG]] (Directed Acyclic Graphs).
- Se rezolvă cu [[DFS]] (sortarea inversă a momentului de terminare) sau folosind [[Kahn’s algorithm]] (cu coadă și graduri de intrare).
- Timp de rulare: O(V + E), unde V = noduri, E = muchii.
- Aplicații: planificare sarcini, compilatoare, ordonarea dependențelor.

