## Structuri statice  
#statice #structuridate #c++

- Structurile statice au **dimensiune fixă** și sunt alocate complet la momentul compilării.
- Exemplu clasic: [[vector]] cu dimensiune cunoscută (`int v[100];` în C++).
- Avantaje: **acces rapid**, nu necesită [[pointeri]] sau gestionare manuală a memoriei.
- Limitare: **flexibilitate scăzută** – nu pot crește sau scădea în timpul execuției.
- Ideale pentru situații predictibile, unde spațiul maxim este cunoscut dinainte.
- Se alocă în zona de **stack**, spre deosebire de structurile [[dinamice]] care folosesc [[heap]].

