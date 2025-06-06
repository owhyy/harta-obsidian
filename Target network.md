**Target Network** este o copie temporar "înghețată" a rețelei principale (policy sau Q-network), folosită pentru a calcula valorile-țintă (*target values*) într-un mod **mai stabil** în timpul antrenării algoritmilor de învățare prin întărire.
## Cum funcționează

1. Se antrenează o rețea principală: `Q(s, a | θ)`
2. Se creează o rețea țintă: `Q_target(s, a | θ⁻)` care este o copie a rețelei principale
3. La fiecare pas, se calculează valoarea-țintă folosind **rețeaua țintă**:
