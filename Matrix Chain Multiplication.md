#alg 
- Problema cere determinarea **ordinii optime de înmulțire** a unei secvențe de matrici pentru a **minimiza numărul total de operații**.
- Nu se schimbă rezultatul, ci doar **parantezarea** înmulțirilor pentru eficiență.
- Relația de recurență:  
  `dp[i][j] = min(dp[i][k] + dp[k+1][j] + p[i−1]*p[k]*p[j])`,  
  unde `p` este vectorul dimensiunilor matricilor.
- Evaluarea se face bottom-up pe o matrice `dp[n][n]`, unde `n` este numărul de matrici.
- Complexitate: O(n³) timp și O(n²) spațiu.
- Aplicații: baze de date (optimizare de interogări), compilatoare, algebră computațională.

