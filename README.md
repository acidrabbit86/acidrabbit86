## 🚀 Progetti Principali (Buildweek)

| Progetto | Dominio | Tecnologie & Tools | Link |
| :--- | :--- | :--- | :--- |
| **Buildweek 1** | Network Architecture & Perimeter Defense | Cisco Packet Tracer, pfSense, IDS/IPS, Python | [Vedi Repo](./Epicode---Buildweek-1) |
| **Buildweek 2** | Penetration Testing & Vulnerability Assessment | Metasploit, SQLi, XSS, LLM Exploit, CTF | [Vedi Repo](./Epicode---Buildweek-2) |
| **Buildweek 3** | SOC Analysis, Incident Response & Forensics | Security Onion, Kibana, Wireshark, Splunk | [Vedi Repo](./Epicode---Buildweek-3) |

---

## 📑 Dettaglio delle Buildweek

### 🏢 Buildweek 1: Progettazione e Definizioni di Rete Aziendale
Progettazione e testing dell'infrastruttura di rete per un edificio aziendale su 6 piani (120 host totali):
* **Architettura:** Segregazione di rete, segmentazione per piano (20 PC per piano) e zona DMZ per servizi critici (Web Server DVWA/Metasploitable e NAS centralizzato).
* **Sicurezza Perimetrale:** Configurazione di Firewall perimetrale integrato con 3 moduli IDS/IPS per il monitoraggio attivo del traffico.
* **Validazione:** Modellazione logica con Cisco Packet Tracer, verifica del traffico a basso livello tramite script Python e simulazione in ambiente reale con pfSense.

### ⚔️ Buildweek 2: Web & Infrastructure Exploitation + CTF
Attività pratiche di Penetration Testing e risoluzione di sfide CTF:
* **Web Application Exploitation:** Identificazione e sfruttamento di vulnerabilità SQL Injection (SQLi) e Cross-Site Scripting (XSS).
* **Adversarial AI:** Tecniche di exploit applicate a modelli di linguaggio (LLM Exploitation / Prompt Injection).
* **Infrastructure Exploitation:** Testing di vulnerabilità di sistema con Metasploit su macchine target Linux (Metasploitable) e Windows.
* **Capture The Flag (CTF):** Risoluzione di 3 sfide pratiche CTF focalizzate su escalation di privilegi e vulnerabilità web.

### 🛡️ Buildweek 3: SOC Analysis, Malware Forensics & Threat Hunting
Progetto multidisciplinare focalizzato sul monitoraggio, analisi dei log e risposta agli incidenti:
* **Malware Analysis & Sandbox:** Static/Dynamic Analysis di campioni malware (AdwCleaner, Any.run Sandbox) e stesura di report di remediation per il management.
* **Network & PCAP Forensics:** Analisi del traffico di rete (HTTP/HTTPS) tramite `tcpdump` e `Wireshark`, ricostruzione di flussi TCP ed estrazione di payload eseguibili malevoli (es. Nimda) da catture pcap.
* **Threat Hunting & SIEM (Security Onion & Kibana):** 
  * Investigazione di attacchi SQL Injection ed esfiltrazione dati nascosta tramite sottodomini DNS esadecimali.
  * Isolamento di host compromessi tramite 5-Tupla (Sguil & Kibana), rilevamento di accessi `root` non autorizzati e furto di dati via FTP.
* **SIEM Log Analysis (Splunk):** Creazione di query SPL per identificare tentativi di attacco Brute Force SSH, errori del server interno e analisi comportamentale degli utenti.
* **Laboratori Avanzati:** Analisi del codice sorgente di malware storici (Mydoom) e studio teorico/pratico delle dinamiche di Buffer Overflow (gestione stack x86, EIP/ESP, badchars e meccanismi RCE).

---

## 🛠️ Tech Stack & Strumenti
* **Sistemi Operativi:** Kali Linux, Security Onion, Windows, pfSense
* **Networking & Monitoring:** Wireshark, tcpdump, Cisco Packet Tracer, Netstat, Telnet
* **SIEM & Analytics:** Kibana, Sguil, Splunk
* **Pentesting & Exploitation:** Metasploit, Nmap, SQLi, XSS, Mona.py, Immunity Debugger
* **Linguaggi:** Python, Bash, SQL, SPL
<!--
**acidrabbit86/acidrabbit86** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
