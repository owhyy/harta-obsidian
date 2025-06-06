#ds
- O **funcție de hash** transformă o cheie de tip arbitrar (ex: string, număr) într-un **index numeric** într-un hash table.
- Scopul: să distribuie cât mai uniform cheile în tabel, minimizând coliziunile
- O funcție bună este: **deterministă**, **rapidă**, **distribuie uniform**, și **reduce clusteringul**.
- Exemplu simplu: `h(key) = key % n`, dar în practică se folosesc variante mai sofisticate (ex: [[SHA]] pentru hashuri criptografice).
- În caz de coliziune: se aplică metode ca [[chaining]] sau [[open addressing]].

