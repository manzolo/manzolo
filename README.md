# 👋 [🇮🇹 Italiano](#-italiano) · [🇬🇧 English](#-english)

---

# 🇮🇹 Italiano

## Ciao, sono Andrea 👋

Appassionato di Linux, Docker, AI locale e retrogaming — costruisco tool, laboratori e container, soprattutto per divertimento e per imparare. Vivo in Toscana e lavoro al CNR-IFAC.

> 🗂️ **Menu interattivo dei progetti:** [manzolo.github.io/manzolo](https://manzolo.github.io/manzolo/) — una home coi macroargomenti e sottopagine dedicate ([🤖 AI & LLM](https://manzolo.github.io/manzolo/#/ai) · [🧪 Laboratori](https://manzolo.github.io/manzolo/#/labs) · [🐳 Docker](https://manzolo.github.io/manzolo/#/docker) · [🔬 Scienza](https://manzolo.github.io/manzolo/#/science)), con ricerca globale.

### 🤖 AI & LLM

Mi piace far girare l'AI **in locale**: riconoscimento vocale, voice cloning, agenti LLM, analisi documenti — tutto Dockerizzato, senza API key cloud. Tutti questi progetti formano il **[Local AI Lab](https://github.com/manzolo/local-ai-lab)**: condividono le stesse convenzioni (rete `local-ai-net`, `OLLAMA_HOST`) e si combinano in pipeline.

#### 🎙️ Voce e parlato

| Repo | Descrizione |
|------|-------------|
| [openai-whisper-docker](https://github.com/manzolo/openai-whisper-docker) ⭐174 | Ambiente Docker per OpenAI Whisper, riconoscimento vocale automatico |
| [myshell-openvoice-docker](https://github.com/manzolo/myshell-openvoice-docker) ⭐40 | OpenVoice (MyShell AI) in Docker: manipolazione e conversione della voce |
| [ai-voice-offline](https://github.com/manzolo/ai-voice-offline) | Conversazione vocale AI offline con GPU e voice cloning |
| [ai-voice-tts](https://github.com/manzolo/ai-voice-tts) / [ai-voice-stt](https://github.com/manzolo/ai-voice-stt) | Sintesi e trascrizione vocale offline con interfaccia web |
| [bark-tts-server](https://github.com/manzolo/bark-tts-server) | Servizio HTTP FastAPI per Suno Bark TTS, Dockerizzato con GPU |
| [whisper-audio-transcriber](https://github.com/manzolo/whisper-audio-transcriber) | Pipeline di conversione audio e trascrizione con Whisper su GPU |
| [poetry-voice](https://github.com/manzolo/poetry-voice) | Trasforma poesie in audiolibri espressivi: analisi prosodica LLM + TTS |
| [uvr-docker](https://github.com/manzolo/uvr-docker) | Ultimate Vocal Remover in Docker: separa voce e strumenti |

#### 🧠 LLM, agenti e Ollama

| Repo | Descrizione |
|------|-------------|
| [local-ai-lab](https://github.com/manzolo/local-ai-lab) 🧠 | L'hub della famiglia AI locale: mappa dei progetti, convenzioni e pipeline componibili |
| [ollama-docker](https://github.com/manzolo/ollama-docker) | Ollama + Open WebUI con supporto NVIDIA: il cuore del Local AI Lab |
| [mcp-lab](https://github.com/manzolo/mcp-lab) | Playground Model Context Protocol: dai "braccia e gambe" a un LLM con tool locali |
| [ollama-agents](https://github.com/manzolo/ollama-agents) | Architettura Docker Compose per agenti AI specializzati |
| [ollama-actions](https://github.com/manzolo/ollama-actions) | Agente LLM che ragiona ed esegue azioni Bash/HTTP in sicurezza |
| [ollama-model-train-guide](https://github.com/manzolo/ollama-model-train-guide) | Guida per addestrare e personalizzare modelli Ollama · [🌐 Guida online](https://manzolo.github.io/ollama-model-train-guide/) |
| [qemu-lab-generator](https://github.com/manzolo/qemu-lab-generator) | Meta-prompt che fa generare a un'AI laboratori QEMU completi |
| [claude-cheatsheets](https://github.com/manzolo/claude-cheatsheets) | Cheatsheet PDF su Claude Code e Claude.ai (IT/EN) · [🌐 Sito](https://manzolo.github.io/claude-cheatsheets/) |
| [claude-statusline](https://github.com/manzolo/claude-statusline) | Statusline personalizzata per Claude Code: contesto, git e Docker |

#### 📄 Documenti intelligenti

| Repo | Descrizione |
|------|-------------|
| [ollapdf](https://github.com/manzolo/ollapdf) | Chatta con i tuoi PDF in locale via Ollama |
| [PDF-Chatbot-Ollama-Langchain-Docker](https://github.com/manzolo/PDF-Chatbot-Ollama-Langchain-Docker) | Chatbot sui tuoi PDF con LangChain e Ollama |
| [pdf2text-converter](https://github.com/manzolo/pdf2text-converter) | Estrazione testo da PDF con AI (FastAPI + Docker) |
| [dots.ocr-docker](https://github.com/manzolo/dots.ocr-docker) | OCR Dockerizzato con modello vision-language dots.ocr su vLLM |
| [text-converter](https://github.com/manzolo/text-converter) | Conversione testi in DOCX/PDF/HTML/Markdown con AI locale |
| [memvid-docker](https://github.com/manzolo/memvid-docker) | Documenti codificati come QR-code in MP4, interrogabili via Ollama |

#### 🎨 Generazione immagini

| Repo | Descrizione |
|------|-------------|
| [fooocus-docker](https://github.com/manzolo/fooocus-docker) | Fooocus (Stable Diffusion XL) con Docker Compose |

### 🧪 Virtualizzazione e laboratori

| Repo | Descrizione |
|------|-------------|
| [qlab](https://github.com/manzolo/qlab) | Laboratori QEMU pronti all'uso, a plugin (DNS, firewall, RAID, LDAP, mail…) |
| [qemu-storage-lab](https://github.com/manzolo/qemu-storage-lab) | Impara RAID mdadm e LVM in una VM usa-e-getta |
| [multipass-microk8s-cluster-demo](https://github.com/manzolo/multipass-microk8s-cluster-demo) | Cluster MicroK8s dimostrativo su VM Multipass |
| [linux-builder](https://github.com/manzolo/linux-builder) | Costruisci una distro Linux minimale da zero (kernel + BusyBox) |
| [cybersecurity-lab](https://github.com/manzolo/cybersecurity-lab) | Ambiente didattico di cybersecurity con servizi vulnerabili su Multipass |

### 🐳 Tool Docker

| Repo | Descrizione |
|------|-------------|
| [cisco-packet-tracer-docker](https://github.com/manzolo/cisco-packet-tracer-docker) | Cisco Packet Tracer in un container |
| [nextcloud-onlyoffice-docker](https://github.com/manzolo/nextcloud-onlyoffice-docker) | Stack Nextcloud + OnlyOffice |
| [wordpress-docker-manager](https://github.com/manzolo/wordpress-docker-manager) | Gestione multi-sito WordPress con Nginx Proxy Manager |
| [ubuntu-repo-docker](https://github.com/manzolo/ubuntu-repo-docker) | Il tuo repository di pacchetti Ubuntu/Debian personale (stile PPA) |

### 🔬 Scienza e didattica

Tutti provabili subito nel browser, senza installare nulla. 👇

#### 🌌 Scienza in 3D

| Repo | Descrizione | 🌐 Demo |
|------|-------------|---------|
| [TavolaPeriodica3D](https://github.com/manzolo/TavolaPeriodica3D) | Tavola periodica interattiva 3D con orbite elettroniche animate | [Apri](https://manzolo.github.io/TavolaPeriodica3D/) |
| [SistemaSolare](https://github.com/manzolo/SistemaSolare) | Simulatore interattivo del sistema solare: pianeti, orbite e schede informative | [Apri](https://manzolo.github.io/SistemaSolare/) |
| [IfacGalaxy](https://github.com/manzolo/IfacGalaxy) | Simulatore 3D interattivo di esopianeti | [Apri](https://manzolo.github.io/IfacGalaxy/) |
| [GeoTimeVoyage](https://github.com/manzolo/GeoTimeVoyage) | Viaggio 3D in 4,6 miliardi di anni di storia della Terra | [Apri](https://manzolo.github.io/GeoTimeVoyage/) |
| [EvoTree3D](https://github.com/manzolo/EvoTree3D) | Albero filogenetico 3D della vita, da LUCA alle specie moderne | [Apri](https://manzolo.github.io/EvoTree3D/) |
| [GeneFlow3D](https://github.com/manzolo/GeneFlow3D) | DNA, RNA, trascrizione e traduzione in 3D | [Apri](https://manzolo.github.io/GeneFlow3D/) |
| [StarLife3D](https://github.com/manzolo/StarLife3D) | Ciclo di vita delle stelle in 3D interattivo | [Apri](https://manzolo.github.io/StarLife3D/) |
| [CellCycle3D](https://github.com/manzolo/CellCycle3D) | Simulatore 3D della divisione cellulare (mitosi e meiosi) | [Apri](https://manzolo.github.io/CellCycle3D/) |
| [ProteinSuite](https://github.com/manzolo/ProteinSuite) | Web app didattica su proteine, FASTA e proprietà biochimiche (IT/EN) | [Apri](https://manzolo.github.io/ProteinSuite/) |
| [MuseoScientificoVirtuale](https://github.com/manzolo/MuseoScientificoVirtuale) | Portale di esperienze scientifiche interattive | [Apri](https://manzolo.github.io/MuseoScientificoVirtuale/) |
| [quiz-didattici](https://github.com/manzolo/quiz-didattici) | Raccolta di quiz educativi interattivi | [Apri](https://manzolo.github.io/quiz-didattici/) |

#### 💻 Informatica interattiva (EDU)

| Repo | Descrizione | 🌐 Demo |
|------|-------------|---------|
| [NumberSimulator](https://github.com/manzolo/NumberSimulator) | Come i computer rappresentano i numeri, ogni bit passo per passo: basi, complemento a due, IEEE 754, UTF-8, 14 livelli guidati + sandbox (IT/EN) | [Apri](https://manzolo.github.io/NumberSimulator/) |
| [AssemblerSimulator](https://github.com/manzolo/AssemblerSimulator) | Impara l'assembly su una CPU didattica 16-bit: 14 livelli guidati + sandbox (IT/EN) | [Apri](https://manzolo.github.io/AssemblerSimulator/) |
| [OsSimulator](https://github.com/manzolo/OsSimulator) | Come un sistema operativo sparte il computer: gestione della memoria (allocazione + paging) e scheduling della CPU, passo per passo, 2 piani + sandbox (IT/EN) | [Apri](https://manzolo.github.io/OsSimulator/) |
| [NetworkSimulator](https://github.com/manzolo/NetworkSimulator) | Impara le reti TCP/IP con pacchetti animati e comandi Linux: 14 livelli guidati + sandbox (IT/EN) | [Apri](https://manzolo.github.io/NetworkSimulator/) |
| [RegexSimulator](https://github.com/manzolo/RegexSimulator) | Impara le regex vedendole girare come automi animati: 14 livelli guidati + sandbox (IT/EN) | [Apri](https://manzolo.github.io/RegexSimulator/) |
| [SqlSimulator](https://github.com/manzolo/SqlSimulator) | Impara SQL vedendo ogni fase della query animata su un database in-memoria: 14 livelli guidati + sandbox (IT/EN) | [Apri](https://manzolo.github.io/SqlSimulator/) |
| [GitSimulator](https://github.com/manzolo/GitSimulator) | Apri il cofano di Git: object store content-addressed, SHA-1 reale, 14 livelli guidati + sandbox (IT/EN) | [Apri](https://manzolo.github.io/GitSimulator/) |
| [GitBranchingSimulator](https://github.com/manzolo/GitBranchingSimulator) | Impara i branch di git sul DAG animato: merge, rebase, cherry-pick, 14 livelli guidati + sandbox (IT/EN) | [Apri](https://manzolo.github.io/GitBranchingSimulator/) |
| [CryptoSimulator](https://github.com/manzolo/CryptoSimulator) | Impara la crittografia guardandola girare: cifrari classici, chiave pubblica/RSA e hashing, motori scritti a mano, livelli guidati + sandbox (IT/EN) | [Apri](https://manzolo.github.io/CryptoSimulator/) |
| [NeuralSimulator](https://github.com/manzolo/NeuralSimulator) | Impara le reti neurali e il pre-training degli LLM: backprop animata, attention heatmap, un Transformer giocattolo, 14 livelli guidati + sandbox (IT/EN) | [Apri](https://manzolo.github.io/NeuralSimulator/) |

---

# 🇬🇧 English

## Hi, I'm Andrea 👋

Linux enthusiast, Docker addict, local-AI tinkerer and retrogamer — I build tools, hands-on labs and containers, mostly for fun and learning. Based in Tuscany, Italy · CNR-IFAC.

> 🗂️ **Interactive project menu:** [manzolo.github.io/manzolo](https://manzolo.github.io/manzolo/) — a home page of macro-topics with dedicated subpages ([🤖 AI & LLM](https://manzolo.github.io/manzolo/#/ai) · [🧪 Labs](https://manzolo.github.io/manzolo/#/labs) · [🐳 Docker](https://manzolo.github.io/manzolo/#/docker) · [🔬 Science](https://manzolo.github.io/manzolo/#/science)), with global search.

### 🤖 AI & LLM

I love running AI **locally**: speech recognition, voice cloning, LLM agents, document intelligence — all Dockerized, no cloud API keys required. Together these projects form the **[Local AI Lab](https://github.com/manzolo/local-ai-lab)**: they share the same conventions (`local-ai-net` network, `OLLAMA_HOST`) and compose into pipelines.

#### 🎙️ Speech & Voice

| Repo | Description |
|------|-------------|
| [openai-whisper-docker](https://github.com/manzolo/openai-whisper-docker) ⭐174 | Docker environment for OpenAI Whisper automatic speech recognition |
| [myshell-openvoice-docker](https://github.com/manzolo/myshell-openvoice-docker) ⭐40 | OpenVoice (MyShell AI) voice manipulation & conversion in Docker |
| [ai-voice-offline](https://github.com/manzolo/ai-voice-offline) | Local GPU-accelerated AI voice conversation with voice cloning |
| [ai-voice-tts](https://github.com/manzolo/ai-voice-tts) / [ai-voice-stt](https://github.com/manzolo/ai-voice-stt) | Local TTS & STT services with web UI, fully offline |
| [bark-tts-server](https://github.com/manzolo/bark-tts-server) | FastAPI HTTP service for Suno Bark TTS, Dockerized with GPU support |
| [whisper-audio-transcriber](https://github.com/manzolo/whisper-audio-transcriber) | Audio conversion + transcription pipeline with Whisper on GPU |
| [poetry-voice](https://github.com/manzolo/poetry-voice) | Poems → expressive audiobooks: LLM prosody analysis + configurable TTS |
| [uvr-docker](https://github.com/manzolo/uvr-docker) | Ultimate Vocal Remover in Docker: split vocals & instrumentals |

#### 🧠 LLM, Agents & Ollama

| Repo | Description |
|------|-------------|
| [local-ai-lab](https://github.com/manzolo/local-ai-lab) 🧠 | The hub of the local AI family: project map, shared conventions and composable pipelines |
| [ollama-docker](https://github.com/manzolo/ollama-docker) | Ollama + Open WebUI with NVIDIA support: the heart of the Local AI Lab |
| [mcp-lab](https://github.com/manzolo/mcp-lab) | Model Context Protocol playground: give an LLM "arms and legs" with local tools |
| [ollama-agents](https://github.com/manzolo/ollama-agents) | Docker Compose architecture for multiple specialized AI agents |
| [ollama-actions](https://github.com/manzolo/ollama-actions) | LLM agent that reasons and executes Bash/HTTP actions safely |
| [ollama-model-train-guide](https://github.com/manzolo/ollama-model-train-guide) | Train, customize and manage Ollama models with Docker Compose · [🌐 Online guide](https://manzolo.github.io/ollama-model-train-guide/) |
| [qemu-lab-generator](https://github.com/manzolo/qemu-lab-generator) | Meta-prompt that makes any AI generate a complete working QEMU lab |
| [claude-cheatsheets](https://github.com/manzolo/claude-cheatsheets) | PDF cheatsheets for Claude Code and Claude.ai (IT/EN) · [🌐 Site](https://manzolo.github.io/claude-cheatsheets/) |
| [claude-statusline](https://github.com/manzolo/claude-statusline) | Custom Claude Code statusline: context window, git & Docker info |

#### 📄 Document Intelligence

| Repo | Description |
|------|-------------|
| [ollapdf](https://github.com/manzolo/ollapdf) | Chat with your PDFs locally via Ollama |
| [PDF-Chatbot-Ollama-Langchain-Docker](https://github.com/manzolo/PDF-Chatbot-Ollama-Langchain-Docker) | Chat with your PDFs via LangChain and Ollama |
| [pdf2text-converter](https://github.com/manzolo/pdf2text-converter) | AI-powered PDF text extraction (FastAPI + Docker) |
| [dots.ocr-docker](https://github.com/manzolo/dots.ocr-docker) | Dockerized OCR with the dots.ocr vision-language model on vLLM |
| [text-converter](https://github.com/manzolo/text-converter) | Ollama-powered text transformation to DOCX/PDF/HTML/Markdown |
| [memvid-docker](https://github.com/manzolo/memvid-docker) | Documents encoded as QR-codes in MP4, queried via Ollama |

#### 🎨 Image Generation

| Repo | Description |
|------|-------------|
| [fooocus-docker](https://github.com/manzolo/fooocus-docker) | Fooocus (Stable Diffusion XL) with Docker Compose |

### 🧪 Virtualization & Hands-on Labs

| Repo | Description |
|------|-------------|
| [qlab](https://github.com/manzolo/qlab) | Plugin-based hands-on QEMU labs (DNS, firewall, RAID, LDAP, mail…) |
| [qemu-storage-lab](https://github.com/manzolo/qemu-storage-lab) | Learn mdadm RAID & LVM inside a disposable QEMU VM |
| [multipass-microk8s-cluster-demo](https://github.com/manzolo/multipass-microk8s-cluster-demo) | MicroK8s cluster demo on Multipass VMs |
| [linux-builder](https://github.com/manzolo/linux-builder) | Build a minimal Linux distro from scratch (kernel + BusyBox) |
| [cybersecurity-lab](https://github.com/manzolo/cybersecurity-lab) | Vulnerable services on Multipass VMs for security education |

### 🐳 Docker Tools

| Repo | Description |
|------|-------------|
| [cisco-packet-tracer-docker](https://github.com/manzolo/cisco-packet-tracer-docker) | Cisco Packet Tracer in a container |
| [nextcloud-onlyoffice-docker](https://github.com/manzolo/nextcloud-onlyoffice-docker) | Nextcloud + OnlyOffice stack |
| [wordpress-docker-manager](https://github.com/manzolo/wordpress-docker-manager) | Manage multiple WordPress instances with Nginx Proxy Manager |
| [ubuntu-repo-docker](https://github.com/manzolo/ubuntu-repo-docker) | Your own PPA-like Ubuntu/Debian package repository |

### 🔬 Science & Education

All playable right in your browser, nothing to install. 👇

#### 🌌 Science in 3D

| Repo | Description | 🌐 Demo |
|------|-------------|---------|
| [TavolaPeriodica3D](https://github.com/manzolo/TavolaPeriodica3D) | Interactive 3D periodic table with animated electron orbits | [Open](https://manzolo.github.io/TavolaPeriodica3D/) |
| [SistemaSolare](https://github.com/manzolo/SistemaSolare) | Interactive solar-system simulator: planets, orbits and info cards | [Open](https://manzolo.github.io/SistemaSolare/) |
| [IfacGalaxy](https://github.com/manzolo/IfacGalaxy) | Interactive 3D exoplanet simulator | [Open](https://manzolo.github.io/IfacGalaxy/) |
| [GeoTimeVoyage](https://github.com/manzolo/GeoTimeVoyage) | 3D journey through 4.6 billion years of Earth's history | [Open](https://manzolo.github.io/GeoTimeVoyage/) |
| [EvoTree3D](https://github.com/manzolo/EvoTree3D) | Interactive 3D phylogenetic tree of life, from LUCA to modern species | [Open](https://manzolo.github.io/EvoTree3D/) |
| [GeneFlow3D](https://github.com/manzolo/GeneFlow3D) | 3D visualization of DNA, RNA, transcription and translation | [Open](https://manzolo.github.io/GeneFlow3D/) |
| [StarLife3D](https://github.com/manzolo/StarLife3D) | Interactive 3D stellar life-cycle viewer | [Open](https://manzolo.github.io/StarLife3D/) |
| [CellCycle3D](https://github.com/manzolo/CellCycle3D) | Interactive 3D cell-division simulator (mitosis & meiosis) | [Open](https://manzolo.github.io/CellCycle3D/) |
| [ProteinSuite](https://github.com/manzolo/ProteinSuite) | Educational web app for proteins, FASTA and biochemical properties (IT/EN) | [Open](https://manzolo.github.io/ProteinSuite/) |
| [MuseoScientificoVirtuale](https://github.com/manzolo/MuseoScientificoVirtuale) | Portal of interactive science experiences | [Open](https://manzolo.github.io/MuseoScientificoVirtuale/) |
| [quiz-didattici](https://github.com/manzolo/quiz-didattici) | Collection of interactive educational quizzes | [Open](https://manzolo.github.io/quiz-didattici/) |

#### 💻 Interactive Computer Science (EDU)

| Repo | Description | 🌐 Demo |
|------|-------------|---------|
| [NumberSimulator](https://github.com/manzolo/NumberSimulator) | How computers represent numbers, every bit step by step: bases, two's complement, IEEE 754, UTF-8, 14 guided levels + sandbox (IT/EN) | [Open](https://manzolo.github.io/NumberSimulator/) |
| [AssemblerSimulator](https://github.com/manzolo/AssemblerSimulator) | Learn assembly on a 16-bit educational CPU: 14 guided levels + sandbox (IT/EN) | [Open](https://manzolo.github.io/AssemblerSimulator/) |
| [OsSimulator](https://github.com/manzolo/OsSimulator) | How an OS shares the computer: memory management (allocation + paging) and CPU scheduling, step by step, 2 floors + sandbox (IT/EN) | [Open](https://manzolo.github.io/OsSimulator/) |
| [NetworkSimulator](https://github.com/manzolo/NetworkSimulator) | Learn TCP/IP networking with animated packets and Linux-style commands: 14 guided levels + sandbox (IT/EN) | [Open](https://manzolo.github.io/NetworkSimulator/) |
| [RegexSimulator](https://github.com/manzolo/RegexSimulator) | Learn regex by watching them run as animated automata: 14 guided levels + sandbox (IT/EN) | [Open](https://manzolo.github.io/RegexSimulator/) |
| [SqlSimulator](https://github.com/manzolo/SqlSimulator) | Learn SQL by watching each query phase animate on an in-memory database: 14 guided levels + sandbox (IT/EN) | [Open](https://manzolo.github.io/SqlSimulator/) |
| [GitSimulator](https://github.com/manzolo/GitSimulator) | Open the hood on Git: content-addressed object store, real SHA-1, 14 guided levels + sandbox (IT/EN) | [Open](https://manzolo.github.io/GitSimulator/) |
| [GitBranchingSimulator](https://github.com/manzolo/GitBranchingSimulator) | Learn git branching on an animated commit DAG: merge, rebase, cherry-pick, 14 guided levels + sandbox (IT/EN) | [Open](https://manzolo.github.io/GitBranchingSimulator/) |
| [CryptoSimulator](https://github.com/manzolo/CryptoSimulator) | Learn cryptography by watching it run: classic ciphers, public-key/RSA and hashing, hand-written engines, guided levels + sandbox (IT/EN) | [Open](https://manzolo.github.io/CryptoSimulator/) |
| [NeuralSimulator](https://github.com/manzolo/NeuralSimulator) | Learn neural networks and LLM pre-training: animated backprop, attention heatmaps, a toy Transformer, 14 guided levels + sandbox (IT/EN) | [Open](https://manzolo.github.io/NeuralSimulator/) |

---

## 📊 Stats

![Andrea's GitHub stats](https://github-readme-stats.vercel.app/api?username=manzolo&show_icons=true&theme=transparent)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=manzolo&layout=compact&theme=transparent)
