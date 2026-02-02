# 🐧 Awesome Linux & Dev Resources

Una raccolta curata di risorse su Linux Kernel, System Design, Algoritmi, Low-Level Engineering e architetture distribuite.
*Aggiornato regolarmente.*

## Indice
- [Linux Internals & Kernel](#linux-internals--kernel)
- [Virtualization, QEMU & Embedded](#virtualization-qemu--embedded)
- [System Design & Distributed Systems](#system-design--distributed-systems)
- [Algorithms & CS Fundamentals](#algorithms--cs-fundamentals)
- [DevOps, Networking & Cloud](#devops-networking--cloud)
- [AI, ML & GPU](#ai-ml--gpu)
- [License & Disclaimer](#-disclaimer--license)

---

## Linux Internals & Kernel
Approfondimenti su come funziona il sistema operativo, gestione della memoria e security.

- **Understanding the Linux Kernel** - Risorse generali sull'architettura del kernel.
- **The /proc filesystem** - *Quick Insight*: Strumenti come top e ps leggono file di testo da qui.
- **Polling vs Event-Driven** - Perché Linux evita i loop di controllo e usa interrupt/eventi per risparmiare CPU.
- **Linux Kernel Memory Management APIs** - Guida tecnica per Low-Level Engineers.
- **[Massey Linux Kernel Exploitation](https://rvasec.com/slides/2025/Massey_Linux_Kernel_Exploitation_For_Beginners.pdf)** - Guida per principianti all'exploitation del kernel (PDF).
- **OPEN_TREE_NAMESPACE** - Security & Performance win per la gestione dei Container.
- **QEMU + GDB Lab for Kernel Debugging** - Setup avanzato per il debugging (via Phil Garcia).
- **How to Clear RAM Cache and Memory** - Metodi sicuri per la gestione della cache su Linux.
- **FAQ: How to Contribute to the Linux Kernel** - Guida ufficiale per contribuire.
- **Linux Kernel: Virtual File System** - Approfondimento sul VFS.

## Virtualization, QEMU & Embedded
Hacking di VM, container runtime e costruzione di OS minimali.

- **Run Linux inside Linux (UML)** - Usare User-Mode Linux invece di QEMU/VirtualBox.
- **QEMU "Superpower": Boot without Install** - Avviare una VM Linux completa usando solo il kernel (`bzImage`) e initrd.
- **VM Networking without Networking** - Connettersi alle VM senza IP o SSH (VSock).
- **Stop downloading 4GB ISOs** - Costruire ambienti custom usando directory di file invece di installazioni complete.
- **Making a micro Linux distro** - Creare una distribuzione minimale da zero.
- **Making a mini computer from scratch** - Progetto DIY con Raspberry Pi e Linux.

## System Design & Distributed Systems
Latenza, log, streaming dati e architetture scalabili.

- **[The Log](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying-abstraction)** - "What every software engineer should know about real-time data's unifying abstraction".
- **Kafka is not a Queue** - È un commit log. Differenza tra modello Push e Pull.
- **How Apache Kafka Works** - Deep dive per chi costruisce sistemi distribuiti.
- **10 Latency Facts Every Engineer Should Know** - L1 Cache (0.5ns) vs Network Calls vs RAM.
- **The impact of Latency (Pavel Durov)** - Come 50ms di latenza extra influenzano miliardi di utenti.
- **Synchronizing server clocks to 10 ns** - Sincronizzazione precisa senza hardware atomico.
- **21 Lessons from 14 Years at Google** - Lezioni di ingegneria del software su larga scala.
- **Computational Storage & Subsystem Local Memory** - Nuovi paradigmi di architettura hardware/software.
- **[IBM Redbook: Storage Solutions](https://www.redbooks.ibm.com/redbooks/pdfs/sg248502.pdf)** - PDF tecnico sulle soluzioni storage enterprise.

## Algorithms & CS Fundamentals
Teoria, strutture dati e logica computazionale.

- **BM25 Retrieval Method** - Il metodo term-based che potenzia la ricerca ibrida RAG (migliore di TF-IDF).
- **[Shortest Path: Dijkstra](https://algorithms.discrete.ma.tum.de/graph-algorithms/spp-dijkstra/index_en.html)** - Visualizzazione interattiva.
- **[Shortest Path: A* (A-Star)](https://algorithms.discrete.ma.tum.de/graph-algorithms/spp-a-star/index_en.html)** - Visualizzazione interattiva.
- **[Testing A-Star Algorithm](https://www.researchgate.net/figure/Testing-A-Star-algorithm-on-graph_fig5_348997309)** - Analisi performance su grafi.
- **[Espectre (Spectre Exploit)](https://github.com/francescopace/espectre)** - Repo sulle vulnerabilità della CPU.
- **Discovering a new quantum algorithm** - News dal blog IBM Quantum Computing.
- **Algorithms and Data Structures Tutorial** - Corso completo per principianti.

## DevOps, Networking & Cloud
Infrastruttura come codice e gestione reti.

- **Architecture as Code** - Creare diagrammi architetturali direttamente via codice.
- **Import provider network routes to OpenShift via BGP** - Guida networking avanzata Red Hat.
- **[IBM Storage Scale MCP Server](https://github.com/IBM/ibm-storage-scale-mcp-server)** - Server MCP costruito su API IBM Storage per far interagire gli LLM con lo storage.
- **[RHCSA Practice Questions](https://github.com/ive663/RHCSA)** - Lab per la certificazione Red Hat.
- **Kubernetes & OpenShift ecosystem** - Risorse generali.

## AI, ML & GPU
Hardware acceleration, CUDA e intelligenza artificiale.

- **Inside NVIDIA GPUs: High Performance Matmul** - Anatomia dei kernel per la moltiplicazione di matrici.
- **[How to Write High-Performance Matrix Multiply](https://developer.nvidia.com/blog/how-to-write-high-performance-matrix-multiplication-cuda-tensor-cores/)** - Guida tecnica NVIDIA CUDA Tile.
- **CUDA Tile IR** - Simplified GPU Programming.
- **Stanford AI & ML Cheatsheets** - Lezioni di Stanford condensate in visual guides.
- **MIT CS & GenAI** - Risorse su LLMs e Computer Science.

---

### ⚖️ Disclaimer & License

**Disclaimer**
Questa repository è una raccolta personale di link e risorse trovate sul web.
Tutti i marchi, i loghi e i contenuti linkati appartengono ai legittimi proprietari.
Questa lista non ha alcuno scopo di lucro e serve unicamente come indice di studio e condivisione.

**License**
Il codice sorgente di questa lista (la struttura del file e l'organizzazione dei contenuti) è rilasciato sotto licenza **BSD 2-Clause License**.

> Copyright (c) 2024, [Tuo Nome/Username]
> All rights reserved.
>
> Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:
> 1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
> 2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
>
> THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
