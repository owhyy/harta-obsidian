#ds 

- Stocare secvențială în memorie, cu dimensiune fixă (sau dinamică – [[std::vector]] în C++).
- Permite **acces direct** la orice element: `a[i]` în O(1).
- Inserarea și ștergerea sunt lente (O(n)), în afară de sfârșit (O(1) amortizat).
- Util pentru parcurgeri rapide, tabele de valori, algoritmi de bază.
- Ideal când dimensiunea datelor este cunoscută sau crește rar.

