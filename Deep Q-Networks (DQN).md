#ai 
- **DQN (Deep Q-Network)** este un algoritm de învățare prin întărire **off-policy** care folosește o **rețea neuronală profundă** pentru a aproxima funcția Q – adică valoarea acțiunilor într-o anumită stare.

- Este o extensie a algoritmului **Q-Learning** clasic, concepută pentru a funcționa în medii complexe cu **spații de stare mari sau continue**, unde stocarea unei tabele Q este imposibilă.

## Scop

- Învățarea unei politici optime pentru a maximiza recompensa pe termen lung
- Estimarea funcției Q:  
  `Q(s, a) ≈ Q̂(s, a; θ)`  
  unde `θ` sunt parametrii rețelei neuronale

## Componente principale

- **[[Neural Network|Rețea neurală]]** 
- **[[Replay buffer]]**   
- **Target network** – o copie a rețelei Q care se actualizează mai rar, pentru stabilitate
- **Strategie de explorare** – ex: ε-greedy