# 🔍 Matrix Rebels: Security Audit & Adversary Emulation

**Team:** Matrix Rebels | **Contesto:** Build Week 2 @ EPICODE Institute of Technology

Questo progetto documenta un'attività intensiva di simulazione d'attacco (Adversary Emulation) e Vulnerability Assessment. L'obiettivo è stato analizzare, sfruttare e mitigare vulnerabilità complesse su applicazioni web, sistemi operativi e intelligenze artificiali, emulando le TTPs (Tactics, Techniques, and Procedures) di attaccanti reali al fine di consolidare le difese aziendali.

---

### 🎯 Obiettivi e Scenario
- **Perimetro d'azione:** Web application (DVWA), ambienti Linux/Windows, AI LLM e macchine CTF isolate (Boot2Root).
- **Sfida:** Condurre Penetration Test in scenari Black Box e Gray Box, identificare i vettori d'attacco e proporre strategie di mitigazione (Blue Teaming) rigorosamente documentate.

---

### 🛠️ Tecnologie e Strumenti Utilizzati

![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)
![Nessus](https://img.shields.io/badge/Nessus-000000?style=for-the-badge&logo=tenable&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-000000?style=for-the-badge&logo=metasploit&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-2B2D31?style=for-the-badge&logo=nmap&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

### ⚙️ Dettagli delle Fasi Operative

#### 1. Web Application Security (OWASP)
- **SQL Injection:** Sfruttamento di vulnerabilità SQLi per estrazione dati, con tecniche di bypass filtri e codifica URL tramite Burp Suite.
- **Cross-Site Scripting (XSS):** Esecuzione di attacchi XSS Stored per il Session Hijacking.
- **Mitigazione:** Redazione di raccomandazioni tecniche per l'implementazione di Input Validation, Parametrized Queries e flag HttpOnly sui cookie.

#### 2. Memory Corruption & Secure Coding
- Analisi architetturale di codice C vulnerabile.
- Sfruttamento di vulnerabilità **Stack-Based Buffer Overflow** per manipolare l'esecuzione del programma in memoria.
- Riscrittura del codice sorgente implementando logiche di programmazione difensiva e sanitizzazione degli input.

#### 3. AI & LLM Security
- Testing di sicurezza su sistemi basati su Intelligenza Artificiale.
- Esecuzione di tecniche avanzate di **Prompt Injection**, evasione delle policy DLP (Data Loss Prevention) e Jailbreak deduttivo su motori LLM.

#### 4. CTF & Privilege Escalation (MITRE ATT&CK)
Risoluzione e mappatura completa di macchine Boot2Root (Jangow 01, LupinOne):
- **Initial Access:** Exploitation di servizi esposti e vulnerabilità note.
- **Privilege Escalation:** Abuso di permessi SUID, Python Library Hijacking e manipolazione delle configurazioni sudoers.
- **Reporting:** Mappatura dell'intera Kill Chain sul framework MITRE ATT&CK e redazione di remediation per l'hardening dei sistemi operativi.

---

### 📂 Risorse del Progetto

- 📄 **[Report Tecnico Finale - Security Audit & CTF (PDF)](INCOLLA_QUI_IL_LINK_CHE_COPIERAI)**: Documentazione completa di tutte le fasi di assessment, metodologie d'attacco e raccomandazioni di sicurezza.
