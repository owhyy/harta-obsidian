O **funcție pură** este o funcție care, dată aceeași intrare, returnează întotdeauna aceeași ieșire și **nu are efecte secundare** (side effects).

Acest concept este esențial în **programarea funcțională** și contribuie la predictibilitate, testabilitate și optimizare.

## Proprietăți ale unei funcții pure

1. **Determinism**: pentru aceleași argumente de intrare, rezultatul este întotdeauna același.
2. **Fără efecte secundare**: nu modifică starea globală, nu scrie pe disc, nu actualizează variabile externe, nu apelează I/O etc.

### Exemplu de funcție pură (Python)

```python
def aduna(a, b):
    return a + b