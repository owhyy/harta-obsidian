#alg 

- **Complexitatea spațială** măsoară **cantitatea de memorie suplimentară** de care are nevoie un algoritm pentru a funcționa, în funcție de dimensiunea datelor de intrare (`n`).
- Este exprimată în notație asimptotică ([[Big-O]], [[Big-Ω]], [[Big-Θ]]) – indică doar ordinul de mărime, nu valorile exacte.
- Exemple:
  - **O(1)** – constantă: nu crește cu dimensiunea (ex: schimbarea a două variabile).
  - **O(n)** – liniară: alocare de vector auxiliar.
  - **O(n²)** – matrice, algoritmi brute-force cu stocare completă.
- Se analizează împreună cu [[complexitate temporală|complexitatea temporală]], pentru a evalua eficiența completă a unui algoritm.
- Importantă în sisteme cu memorie limitată (embedded, mobile) sau când datele sunt masive (big data).
- Poate crește din cauza: stocării temporare (stack, cache), structurilor auxiliare, recursivității (stivă de apeluri).
- Optimizarea spațiului poate implica reutilizarea memoriei, programare in-place, sau transformări iterative.
