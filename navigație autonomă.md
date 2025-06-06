
- **Navigația autonomă** este capacitatea unui sistem robotic de a **se deplasa în mod independent** într-un mediu, fără intervenție umană, folosind senzori, algoritmi de localizare și planificare a traseului.

- Este o componentă esențială în robotică mobilă, vehicule autonome și drone.

## Componente principale

- **Percepție** – interpretarea mediului prin senzori (camere, LIDAR, radar, ultrasonice)
- **Localizare** – determinarea poziției proprii în spațiu (ex: GPS, SLAM)
- **Hartă** – reprezentare internă a mediului (statică sau dinamică)
- **Planificare** – calcularea rutei optime de la poziția curentă la destinație
- **Control** – executarea mișcării pe traseul stabilit, cu evitarea obstacolelor

## Algoritmi și metode

- **SLAM (Simultaneous Localization and Mapping)** – folosit pentru a construi o hartă și a se localiza simultan
- **A\***, Dijkstra – algoritmi de căutare pentru trasee optime
- **RRT, PRM** – metode pentru planificare în spații complexe
- **PID, MPC** – algoritmi de control al mișcării