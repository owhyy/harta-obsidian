#alg
- **LCS** între două șiruri X și Y este cea mai lungă secvență (nu neapărat continuă) prezentă în ambele.
- Relația de recurență:  
  `dp[i][j] = 1 + dp[i−1][j−1]` dacă X[i]=Y[j]  
  altfel `dp[i][j] = max(dp[i−1][j], dp[i][j−1])`.
- Se construiește o matrice (len(X)+1 × len(Y)+1), evaluare bottom-up.
- Complexitate: O(n · m), unde n și m sunt lungimile celor două șiruri.
- Aplicații: comparare fișiere, bioinformatică, control versiuni (diff).

