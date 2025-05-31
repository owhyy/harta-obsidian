#OS
- Un **sistem de operare (OS)** este software-ul fundamental care gestionează resursele hardware și oferă servicii pentru aplicațiile software.  
- El acționează ca o interfață între utilizator și [[Hardware||hardware-ul]] [[Computer|calculatorului]], coordonând execuția proceselor, accesul la [[Memorie|memorie]], fișiere și dispozitive de [[Dispozitive input|intrare]]i/[[Dispoieșire.

## ✅ Activitatea principală

### Teorie
- Planificarea proceselor
- Gestiunea memoriei
- Sincronizarea firelor de execuție
- Sisteme de fișiere
- Virtualizare

### Experiment
- Implementare [[Kernel]] (ex: [[Linux]])
- Măsurători de performanță (ex: context switch)

### Design
- [[Microkernel]] și hypervisor-e
- Arhitecturi modulare: [[Android]], [[iOS]]
- Interfețe sistem ([[API]])

---

## 🔄 Relații cu alte domenii

- [[Arhitectura calculatoarelor]] – OS comunică direct cu hardware-ul
- [[Securitate]] – controlează accesul și izolează procesele
- [[Inteligența Artificială]] – planificare bazată pe AI
- [[Sisteme distribuite]] – coordonarea resurselor între noduri
- [[Rețele de calculatoare]] – gestionarea stivei de protocoale

---

## 🧩 Probleme deschise

- Planificare eficientă pe sisteme multi-core (>128 nuclee)
- Securitate și procesare izolată ([[Enclave]], confidential computing)
- Optimizare pentru containere și infrastructură cloud-native
- Ex: „N+1 context switches” – afectează performanța în multitasking

---

## 👤 Persoane influente

- [[Andrew S. Tanenbaum]] – MINIX
- [[Ken Thompson & Dennis Ritchie]] – UNIX
- [[Linus Torvalds]] – Linux

---

## 🌍 Foruri relevante

- **Conferințe**: USENIX OSDI, SOSP, EuroSys
- **Reviste**: ACM TOCS, IEEE Transactions on Computers

---

## 📍 UVT – Dimensiune locală

- Cursuri: *Sisteme de operare*, *Tehnologii avansate de sistem*
- Proiecte: shell, microkernel bare-metal, debugging kernel


