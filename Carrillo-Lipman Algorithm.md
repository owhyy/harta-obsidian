#bioinfo #alg

**Algoritmul Carrillo-Lipman** este o tehnică de optimizare pentru **alinierea multiplă a secvențelor** (MSA – Multiple Sequence Alignment), propusă de **Carrillo și Lipman în 1988**. Scopul este de a reduce complexitatea alinierii prin folosirea scorurilor de aliniere pereche pentru a restrânge spațiul de căutare.

## Scop

- Optimizarea **scorului sumă-de-perechi (Sum-of-Pairs – SP)** într-o aliniere multiplă.
- Reducerea spațiului de căutare necesar pentru alinierea mai multor secvențe biologice (ADN, ARN, proteine).

## Pași principali

1. **Calculul alinărilor optime pereche** între toate secvențele (2 câte 2).
2. **Determinarea limitelor inferioare și superioare** pentru scorul SP total, pe baza acestor alinieri.
3. **[[Pruning]] (tăierea spațiului de căutare)**: eliminarea alinărilor imposibil de îmbunătățit pe baza limitelor.

## Avantaje

- Reduce dramatic numărul de alinieri de verificat.
- Permite utilizarea exactă a metodei SP pentru un număr moderat de secvențe.
- Poate fi integrat în algoritmi mai complecși de aliniere multiplă.