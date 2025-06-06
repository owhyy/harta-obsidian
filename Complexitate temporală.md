#alg 

- **Complexitatea temporală** măsoară **cât timp durează execuția unui algoritm** în funcție de dimensiunea datelor de intrare (`n`).
- Este exprimată în notație asimptotică, cel mai frecvent cu [[Big-O]], dar și cu [[Big-Ω]] și [[Big-Θ]].
- Tipuri comune:
  - **O(1)** – constantă (ex: acces direct în vector).
  - **O(log n)** – logaritmică (ex: căutare binară).
  - **O(n)** – liniară (ex: parcurgere secvențială).
  - **O(n log n)** – eficientă (ex: MergeSort, QuickSort).
  - **O(n²)** – ineficientă pentru date mari (ex: BubbleSort).
- Se analizează în:
  - **Cel mai bun caz** (optimist).
  - **Caz mediu** (probabilistic).
  - **Cel mai rău caz** (pesimist, cel mai des folosit).
- Importanța vine din necesitatea de a alege algoritmi scalabili pentru aplicații reale.
- Complexitatea temporală este independentă de limbajul folosit, compilator sau hardware.

