# 🐧 Awesome Linux & Dev Resources

Una raccolta curata di risorse su Linux Kernel, System Design, Algoritmi e Low-Level Engineering.
*Work in progress.*

## Indice
- [Linux Internals & Kernel](#linux-internals--kernel)
- [Virtualization & QEMU](#virtualization--qemu)
- [System Design & Distributed Systems](#system-design--distributed-systems)
- [Algorithms & CS Fundamentals](#algorithms--cs-fundamentals)
- [DevOps, Networking & Cloud](#devops-networking--cloud)
- [AI, ML & GPU](#ai-ml--gpu)

---

## Linux Internals & Kernel
Approfondimenti su come funziona il pinguino sotto il cofano.

- **Understanding the Linux Kernel** - Risorse generali sull'architettura del kernel.
- **The /proc filesystem** - *Quick Insight*: Strumenti come top e ps leggono file di testo da qui. Se fai `ls /proc`, vedi cartelle numerate per ogni processo.
- **Polling vs Event-Driven** - Perché Linux evita i loop di controllo (polling) e usa meccanismi come `epoll`/`inotify` per risparmiare CPU.
- **Linux Kernel Memory Management APIs for Low-Level Engineers** - Guida tecnica alle API di gestione memoria (via Avinash Pal).
- **QEMU + GDB Lab for Linux Kernel Debugging** - Setup per il debugging avanzato del kernel (via Phil Garcia).
- **[RHCSA Practice Questions](https://github.com/ive663/RHCSA)** - Collezione di domande pratiche e ambienti lab per la certificazione Red Hat.

## Virtualization & QEMU
Virtualizzazione leggera e hacking di sistemi operativi.

- **Run Linux inside Linux (UML)** - Usare User-Mode Linux invece di QEMU/VirtualBox per un'architettura più leggera.
- **QEMU "Superpower": Boot without Install** - Avviare una VM Linux completa usando solo il kernel (`bzImage`) e un filesystem, senza installazione o dischi virtuali.
- **VM Networking without Networking** - Connettersi alle VM senza IP, SSH keys o routing tables (probabilmente via VSock) sulla stessa macchina fisica.
- **Stop downloading 4GB ISOs** - Come costruire ambienti custom usando semplici directory di file invece di installazioni complete.
- **Making a micro Linux distro** - Creare una distribuzione minimale da zero.
- **Making a mini computer from scratch** - Progetto DIY con Raspberry Pi e Linux.

## System Design & Distributed Systems
Architetture scalabili, latenza e gestione dati.

- **[The Log](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying-abstraction)** - What every software engineer should know about real-time data's unifying abstraction.
- **Kafka is not a Queue** - È un commit log mascherato. Non "spinge" messaggi, tu "tiri" (pull) dal database/log.
- **How Apache Kafka Works** - Deep dive per chi costruisce sistemi distribuiti (via Dr. Milan Milanović).
- **10 Latency Facts Every Engineer Should Know**
  - L1 cache hit: ~0.5 ns
  - RAM access: ~100 ns
  - *Context:* Accedere alla cache CPU è 200,000x più veloce di una chiamata di rete.
- **The impact of Latency (Pavel Durov)** - "Se c'è una latenza extra di 50ms, miliardi di utenti aprono l'app meno spesso."
- **Synchronizing server clocks to within 10 ns** - Sincronizzazione precisa senza hardware costoso (via Urs Hölzle).

## Algorithms & CS Fundamentals
Teoria, grafi e strutture dati.

- **[BM25 Retrieval Method](https://en.wikipedia.org/wiki/Okapi_BM25)** - Il motore dietro la ricerca ibrida RAG. Migliora il TF-IDF basandosi sui termini.
- **[Shortest Path: Dijkstra](https://algorithms.discrete.ma.tum.de/graph-algorithms/spp-dijkstra/index_en.html)** - Visualizzazione interattiva (TU München).
- **[Shortest Path: A* (A-Star)](https://algorithms.discrete.ma.tum.de/graph-algorithms/spp-a-star/index_en.html)** - Visualizzazione interattiva dell'algoritmo euristico.
- **[Testing A-Star Algorithm](https://www.researchgate.net/figure/Testing-A-Star-algorithm-on-graph_fig5_348997309)** - Paper e figure su ResearchGate.
- **[Espectre (Spectre Exploit)](https://github.com/francescopace/espectre)** - Repo relativa alle vulnerabilità della CPU.
- **Discovering a new quantum algorithm** - News dal blog IBM Quantum Computing.
- **Algorithms and Data Structures Tutorial** - Corso completo per principianti.

## DevOps, Networking & Cloud
Gestione infrastruttura e reti.

- **Architecture as Code** - Creare diagrammi architetturali e software architecture direttamente via codice.
- **How to import provider network routes to OpenShift via BGP** - Guida avanzata di networking Red Hat.
- **Kubernetes & OpenShift ecosystem** - Risorse su Platform Engineering, SRE e GitOps.

## AI, ML & GPU
Intelligenza artificiale e calcolo parallelo.

- **Stanford AI & ML Cheatsheets** - Anni di lezioni condensate in guide visive ufficiali.
- **Inside NVIDIA GPUs** - Anatomia dei kernel ad alte prestazioni per la moltiplicazione di matrici (matmul).
- **CUDA Tile IR** - Simplified GPU Programming with cuTile and Tile IR.
- **MIT CS & GenAI** - Risorse su LLMs e Computer Science dal MIT.

---
*Ultimo aggiornamento: [Inserisci Data]*
