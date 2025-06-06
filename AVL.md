#
Un **AVL Tree** este un arbore binar de căutare (BST – Binary Search Tree) care este **autoechilibrat**, adică menține o diferență controlată între înălțimile subarborilor stâng și drept pentru fiecare nod.

A fost inventat în 1962 de **Adelson-Velsky** și **Landis** — de unde și numele **AVL**.

## Proprietăți

- Diferența de înălțime (factorul de echilibru) între subarborele stâng și cel drept este **cel mult 1**
- Operațiile de inserare și ștergere pot necesita **rotații** pentru a restabili echilibrul

## Operații principale

- **Inserare**: similară cu BST, urmată de verificarea echilibrului și aplicarea rotațiilor dacă e necesar
- **Ștergere**: necesită repoziționare a nodurilor și rebalansare
- **Căutare**: eficientă – O(log n)

## Tipuri de rotații

1. **Rotație simplă la stânga**
2. **Rotație simplă la dreapta**
3. **Rotație stânga-dreapta (LR)**
4. **Rotație dreapta-stânga (RL)**

Aceste rotații mențin proprietățile BST și echilibrul AVL.

## Complexități

| Operație | Timp AVL Tree |
| -------- | ------------- |
| Căutare  | O(log n)      |
| Inserare | O(log n)      |
| Ștergere | O(log n)      |