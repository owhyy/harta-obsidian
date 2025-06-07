#ds 
- Tehnică de **rezolvare a coliziunilor** în [[hash table]] folosind [[Listă înlănțuită]].
- Fiecare poziție din tabel (bucket) păstrează o **listă de elemente** care au același index hash.
- Când apar coliziuni, elementele sunt **adăugate în listă**, fără realocare globală.
- Complexitate medie: O(1) pentru inserare/căutare dacă distribuția este uniformă.
- Performanța scade dacă [[Funcția de hash]] e slabă sau dacă tabelul este prea plin.


