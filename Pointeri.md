#ds #PL 
- Un **pointer** este o variabilă care **stochează adresa de memorie** a altei variabile.
- Sunt fundamentali în [[C]] și [[C++]] pentru [[alocare dinamică]], manipulare de [[structuri de date]] și apeluri prin referință.
- Sintaxă: `int* p = &x;` → `p` pointează spre `x`.
- Se folosesc în [[liste înlănțuite]], [[arbore|arbori]], [[grafuri]], [[heap]].
- Pot duce la **erori grave** dacă nu sunt gestionați corect: [[memory leaks]], [[dangling pointers]], [[segmentation fault]].
- În C++ modern, se recomandă [[smart pointers]]: `unique_ptr`, `shared_ptr`, `weak_ptr`.

