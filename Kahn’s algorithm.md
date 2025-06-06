## Kahn’s Algorithm  
#kahn #topologicalsort #grafuri

- **Kahn’s Algorithm** este o metodă iterativă pentru [[Topological Sort]] pe un [[DAG]], folosind o [[queue]] și calculul gradului de intrare pentru fiecare nod.
- Pași:
  1. Se calculează **in-degree-ul** (numărul de muchii care intră) pentru fiecare nod.
  2. Se adaugă în coadă toate nodurile cu `in-degree = 0`.
  3. Se extrage din coadă, se adaugă în ordonare, și se reduce in-degree la vecini.
  4. Se repetă până la golirea cozii.
- Dacă la final nu s-au procesat toate nodurile → graful **conține cicluri**.
- Complexitate: **O(V + E)**, eficient și ușor de implementat.

