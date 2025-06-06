Un **array** este o structură de date liniară care stochează elemente de același tip într-o zonă de memorie contiguă. Accesul la elemente se face prin **index numeric**, ceea ce permite timpi de acces foarte rapizi.

## Caracteristici

- Elemente stocate **în ordine** și **în memorie continuă**
- Acces prin index: `A[i]` (începând de la 0)
- Timp de acces: **O(1)** pentru citire/scriere
- Dimensiune fixă (în majoritatea limbajelor statice)

## Tipuri de array-uri

- **Unidimensional** – ex: `int a[5];`
- **Bidimensional** – matrice: `int m[3][3];`
- **Multidimensional** – mai multe niveluri: `int x[2][2][2];`
- **Array dinamic** – dimensiune variabilă (ex: `vector` în [[C++]], `list` în [[Python]])

## Operații comune

- Acces la element: `a[i]`
- Modificare: `a[i] = noua_valoare`
- Iterare: bucle for/while
- Căutare: secvențială sau binară (dacă e sortat)
- Inserare/ștergere: **costisitoare** – O(n)