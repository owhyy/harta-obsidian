#alg 
- Problema **Knapsack**: alegerea unui subset de obiecte cu greutăți și valori astfel încât să **maximizăm valoarea** fără a depăși greutatea totală permisă.
- Relația de recurență:  
  `dp[i][w] = max(dp[i-1][w], dp[i-1][w-wi] + vali)`  
  (unde `wi` = greutate obiect, `vali` = valoare).
- Evaluare: [[bottom-up]] pe o matrice 2D (obiecte × greutate).
- Complexitate: O(n · W), unde n = număr obiecte, W = capacitate rucsac.
- Problemă clasică de [[Optimizare combinatorică]] și [[programare dinamică]].

