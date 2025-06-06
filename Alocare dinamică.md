## Alocare dinamică  
#alocaredinamică #pointeri #heap

- Alocarea dinamică înseamnă **rezervarea memoriei în timpul execuției**, nu la compilare.
- Este utilă când **dimensiunea structurii nu este cunoscută** la început (ex: [[listă înlănțuită]], [[arbore]]).
- În C: `malloc`, `calloc`, `realloc`, `free`; în C++: `new` și `delete`.
- Memoria este alocată în zona **heap** (spre deosebire de stack pentru variabilele locale).
- Necesită [[pointeri]] pentru a accesa și gestiona zona alocată.
- Obligatoriu: eliberarea memoriei pentru a evita [[Memory leaks]].

