<!-- ╔══════════════════════════════════════════════════════════╗ -->
<!-- ║       DEEPAK KUMAR KUNWAR — GitHub Profile README       ║ -->
<!-- ╚══════════════════════════════════════════════════════════╝ -->

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=800&color=1F618D&center=true&vCenter=true&width=700&height=60&lines=Deepak+Kumar+Kunwar;SOC+Analyst+L1+%7C+C-DOT%2C+Govt.+of+India;SIEM+%E2%80%A2+Threat+Detection+%E2%80%A2+Incident+Response" alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/deepakkumarkunwar)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/deepakkumarkunwar)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/deepakkumarkunwar)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:deepakkumarkunwar@outlook.com)

<br/>

![](https://komarev.com/ghpvc/?username=deepakkumarkunwar&color=1F618D&style=flat-square&label=Profile+Views)

</div>

---

## 👨‍💻 About Me

> **SOC Analyst L1** at **C-DOT** (Centre for Development of Telematics), Govt. of India —
> operating **Trinetra SIEM** for real-time security monitoring.
> Previously a **Cybersecurity Trainee at CERT-In** (MeitY, Govt. of India).

- 🔭 Currently working on: **Zeek + ELK Stack NSM pipeline** (live SOC lab)
- 🌱 Deepening skills in: **threat hunting, detection engineering, DFIR**
- 🎯 Executed **MITRE ATT&CK** adversary emulation via Atomic Red Team (T1003, T1548, T1053)
- 🏆 **TryHackMe Top 7%** — 94 Rooms | 15 Badges | 163-Day Streak | Level: [0x8][HACKER]
- 💬 Ask me about: **SIEM, log analysis, alert triage, Zeek, ELK Stack**
- 📫 Reach me: [deepakkumarkunwar@outlook.com](mailto:deepakkumarkunwar@outlook.com)

---

## 🛡️ Technical Skills

### SIEM & Security Monitoring
![ELK Stack](https://img.shields.io/badge/ELK_Stack-005571?style=flat-square&logo=elastic&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Kibana](https://img.shields.io/badge/Kibana-E8478B?style=flat-square&logo=kibana&logoColor=white)
![Zeek](https://img.shields.io/badge/Zeek_NSM-2C2C2C?style=flat-square&logoColor=white)
![Filebeat](https://img.shields.io/badge/Filebeat-005571?style=flat-square&logo=elastic&logoColor=white)

### Threat Detection & Incident Response
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-FF0000?style=flat-square&logoColor=white)
![Atomic Red Team](https://img.shields.io/badge/Atomic_Red_Team-FF4500?style=flat-square&logoColor=white)
![IOC Analysis](https://img.shields.io/badge/IOC_Analysis-1F618D?style=flat-square&logoColor=white)
![DFIR](https://img.shields.io/badge/DFIR-2C3E50?style=flat-square&logoColor=white)

### Operating Systems & Infrastructure
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white)

### Programming & Scripting
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

### ML & NLP (Security Applications)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-3776AB?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

---

## 🚀 Featured Projects

### 🔵 End-to-End Network SIEM Pipeline
`Zeek → Filebeat → ELK Stack (Docker)` | Kali Linux (ARM) | Dec 2025 – Ongoing

Production-grade NSM pipeline replicating a real SOC monitoring environment.

- Live packet capture via **Zeek v8.0.4** on eth0 → structured logs (conn/dns/http/ssl/files/weird)
- **Filebeat v9.2.2** ships logs to **Elasticsearch 8.x** running in Docker
- Custom **Kibana dashboards** for real-time detection: DNS anomalies, brute-force, suspicious traffic
- Correlated **MITRE ATT&CK TTPs** (T1003, T1548, T1053) with Zeek log output in Kibana Discover

> 🏷️ `Zeek` `Filebeat` `ELK Stack` `Docker` `Kibana` `MITRE ATT&CK` `NSM` `Threat Detection`

[View Repo →](https://github.com/deepakkumarkunwar/network-siem-pipeline)

---

### 🟡 Trust-SBoT — Social Bot Detection via Behavioral ML
`Python · Scikit-learn · Random Forest · SVM` | Feb 2025

- Trained on **55K+ Twitter/X profiles**; Random Forest achieved **90% accuracy**
- Engineered behavioral features (follower-friend ratio: importance 0.35, post frequency)
- **12% precision improvement** over baseline; **92% malicious bot detection rate**
- Addressed class imbalance via stratified sampling; validated with confusion matrices

> 🏷️ `Machine Learning` `Random Forest` `SVM` `Bot Detection` `NLP` `Pandas` `NumPy`

[View Repo →](https://github.com/deepakkumarkunwar/trust-sbot)

---

### 🟢 Mental Disorder Prediction — NLP & ML
`Python · Scikit-learn · NLTK · TF-IDF · Streamlit` | May 2025

- Preprocessed **53K+ Reddit posts** across 7 mental health categories
- TF-IDF vectorization + SVM classifier achieving **78% multi-class accuracy**
- Deployed as a **live Streamlit web app** with real-time text classification

> 🏷️ `NLP` `TF-IDF` `SVM` `Streamlit` `NLTK` `Text Classification` `Python`

[View Repo →](https://github.com/deepakkumarkunwar/mental-disorder-nlp)

---

## 🏅 Certifications & Training

| Certification | Issuer | Year |
|---|---|---|
| BelkaGPT: AI in DFIR | BelkaSoft | Dec 2025 |
| Machine Learning for Cyber Security *(A+ Grade)* | C-DAC Hyderabad | Oct 2025 |
| Workshop on DSA | SSDC, SLIET | 2022 |

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=deepakkumarkunwar&show_icons=true&theme=default&hide_border=true&title_color=1B3A6B&icon_color=1F618D&text_color=4A5568" height="160" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=deepakkumarkunwar&layout=compact&hide_border=true&title_color=1B3A6B&text_color=4A5568" height="160" />

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com?user=deepakkumarkunwar&hide_border=true&date_format=M%20j%5B%2C%20Y%5D&ring=1B3A6B&fire=1F618D&currStreakLabel=1B3A6B" />

</div>

---

## 🎯 TryHackMe

<div align="center">

<img src="https://tryhackme-badges.s3.amazonaws.com/deepakkumarkunwar.png" alt="TryHackMe" />

</div>

| Stat | Value |
|---|---|
| Global Rank | **Top 7%** |
| Rooms Completed | **94** |
| Badges | **15** |
| Streak | **163 days** |
| Level | **[0x8] HACKER** |

---

## 🤝 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/deepakkumarkunwar)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Profile-212C42?style=for-the-badge&logo=tryhackme)](https://tryhackme.com/p/deepakkumarkunwar)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail)](mailto:deepakkumarkunwar@outlook.com)

</div>

---
<div align="center">
<sub>🛡️ Actively securing systems • C-DOT, New Delhi • Open to SOC / threat detection roles</sub>
</div>
