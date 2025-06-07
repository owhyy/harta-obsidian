#PL 

- Un **segmentation fault** apare atunci când un program încearcă să **aceseze o zonă de memorie nepermisă**.
- Cauze comune: [[dangling pointers]], dereferențierea unui `nullptr`, acces peste limita unui [[vector]], scriere în zone protejate.
- Este o eroare la runtime, frecventă în [[C]] / [[C++]], unde accesul direct la memorie este permis.
- Sistemul de operare întrerupe execuția programului când detectează acces ilegal – de obicei cu mesajul „**Segmentation fault (core dumped)**”.

