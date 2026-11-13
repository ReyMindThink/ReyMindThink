<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=210&section=header&text=Rasyid%20Rayhan%20Novandy&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Cybersecurity%20%C2%B7%20Secure%20Software%20%C2%B7%20Technical%20Leadership&descAlignY=62&descSize=19" alt="banner" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=38BDF8&center=true&vCenter=true&width=700&lines=Cybersecurity+%E2%80%A2+Secure+Software+%E2%80%A2+Technical+Leadership;Phishing+detection+%E2%80%A2+SIEM+%E2%80%A2+Secure+SDLC;Membangun+lab+kecil+yang+berbasis+bukti;Mencari+magang+di+cybersecurity+atau+secure+software)](https://github.com/ReyMindThink)

![Mencari magang](https://img.shields.io/badge/Mencari%20magang-cybersecurity%20%2F%20secure%20software-2ea44f?style=flat-square)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-rasyidrayhan-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rasyidrayhan/)
[![Email](https://img.shields.io/badge/Email-rasyidrayhan1611%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:rasyidrayhan1611@gmail.com)
![Profile views](https://komarev.com/ghpvc/?username=ReyMindThink&label=Pengunjung&color=0e75b6&style=flat-square)

</div>

---

## 👋 Tentang saya

Saya tertarik pada keamanan siber: **bagaimana sistem diserang, diuji, dan dibangun agar tahan.**

Saya belajar dengan membangun: aplikasi web dan desktop, simulasi, dasbor IoT, lab SIEM, dan eksperimen keamanan, baik sendiri, dalam tim, maupun bersama tim yang saya bimbing. Di samping kode, saya memimpin tim teknis. Saya merencanakan dengan teliti, mendokumentasikan dengan jelas, dan menjaga keamanan sejak desain pertama.

> _Learning cybersecurity and secure software by building small, evidence-backed projects._

| 🔐 Cybersecurity | 🧱 Secure software | 🧭 Technical leadership |
| :-- | :-- | :-- |
| Secure SDLC, threat modeling, SAST / DAST, analisis phishing, lab SIEM | API backend, basis data, pengujian otomatis, CI | Memimpin tim teknis Hackathon hingga ratusan peserta |

---

## 🧠 Cara saya bekerja

| 🧾 Bukti dulu | 📏 Ukur sebelum dan sesudah | 🚧 Catat batasannya |
| :-- | :-- | :-- |
| Hasil diperlakukan sebagai hipotesis dan dicek manual. Tidak ada yang dicentang tanpa bukti. | Hardening Linux dinilai dengan audit sebelum dan sesudah perbaikan, bukan dengan perasaan. | Setiap lab mencatat kendala dan keterbatasannya, termasuk angka yang tidak layak dipercaya. |

---

## 📈 Sekilas dalam angka

<div align="center">
<table>
<tr>
<td align="center"><h2>698</h2>peserta Hackathon<br/>Find IT! 2026<br/><sub>dipimpin sebagai Head of Technical</sub></td>
<td align="center"><h2>58</h2>REST endpoint<br/>PassGo<br/><sub>backend, Node.js + Express</sub></td>
<td align="center"><h2>0,7919</h2>recall pada phishing modern<br/>vs 0,9467 di uji internal<br/><sub>selisihnya adalah temuan utama</sub></td>
<td align="center"><h2>95</h2>tes otomatis<br/>phishing-detection-ml<br/><sub>164 commit</sub></td>
</tr>
</table>
</div>

---

## 🎣 Temuan utama: skor tinggi belum tentu bisa dipercaya

[**phishing-detection-ml**](https://github.com/ReyMindThink/phishing-detection-ml) adalah detektor email phishing yang saya bangun untuk mencari tahu **seberapa jauh angkanya sendiri bisa dipercaya**.

| Uji | Recall | |
| :-- | :-: | :-- |
| Uji internal (sumber sama dengan data latih) | **0,9467** | `███████████████████░` |
| 3.075 email phishing modern (2015 – 2025) | **0,7919** | `████████████████░░░░` |

Pada set eksternal berisi 60.648 email (MeAJOR), **4,28%** email biasa salah ditandai sebagai phishing.

> Skor tinggi pada pembagian data sendiri hanya sedikit bercerita tentang serangan baru. Jadi proyek ini mencatat selisihnya, bukan menyembunyikannya.

<details open>
<summary><b>Alur proyek</b></summary>

```mermaid
flowchart LR
    A[📧 Email] --> B[TF-IDF]
    B --> C[Regresi Logistik<br/>ham · spam · phishing]
    C --> D[Evaluasi per kelompok<br/>cegah kebocoran data]
    C --> E[SHAP<br/>penjelasan model]
    D --> F[Flask lokal]
    E --> F
    F --> G[Rilis model<br/>hash SHA256]
```

</details>

---

## 🚀 Proyek

| Proyek | Peran | Isi | Status |
| :-- | :-- | :-- | :-- |
| 🎣 [phishing-detection-ml](https://github.com/ReyMindThink/phishing-detection-ml) | Peneliti dan developer (solo) | TF-IDF + regresi logistik, SHAP, aplikasi Flask, pytest, GitHub Actions, rilis model dengan hash SHA256 | ![Selesai](https://img.shields.io/badge/-Selesai-2ea44f?style=flat-square) |
| 🧪 [security-lab](https://github.com/ReyMindThink/security-lab) | Pembelajar (solo) | Lab keamanan aplikasi dalam tiga fase: secure SDLC, honeypot dan detection engineering, IoT security (opsional). Belum ada temuan yang dipublikasikan | ![Berjalan](https://img.shields.io/badge/-Berjalan%20(fase%201)-d29922?style=flat-square) |
| 🎫 [PassGo](https://github.com/gadicandra/PassGo) | Team lead, backend | Platform tiket untuk komunitas kreatif: kuota tidak bisa terlampaui, QR unik per tiket, validasi di pintu masuk. Node.js, Express, MongoDB, Midtrans Snap, Supabase Storage | ![Aktif](https://img.shields.io/badge/-Aktif%20(backend)-0e75b6?style=flat-square) |
| 🚦 [Simulasi perempatan](https://github.com/ReyMindThink/simulasi-perempatan-mm-ugm) | Pencetus ide, lead developer | Simulasi berbasis agen (Python, Mesa, Streamlit) yang membandingkan dua aturan belok kiri. Hasil awal: waktu tunggu rata-rata −25,5%, kendaraan lolos +26,1% | ![Selesai](https://img.shields.io/badge/-Selesai-2ea44f?style=flat-square) |
| 🧾 [PatunganKu](https://github.com/ReyMindThink/PatunganKu) | Cloud dan software engineer | Aplikasi patungan: basis data dan penyimpanan struk (Node.js, Express, Prisma, SQL, Docker). Azure dan verifikasi struk dengan AI baru rencana | ![Tahap awal](https://img.shields.io/badge/-Tahap%20awal-6e7681?style=flat-square) |
| 🌱 [GreenRide](https://github.com/ReyMindThink/GreenRide) | Cloud dan software engineer | Aplikasi desktop pelacak jejak karbon perjalanan harian (C# .NET 8, PostgreSQL) | ![Dijeda](https://img.shields.io/badge/-Dijeda-6e7681?style=flat-square) |
| 🪵 [ALoRa](https://github.com/ReyMindThink/ALORA_ASC_MAN2PONOROGO) dan 🧫 [AMBER](https://github.com/ReyMindThink/AMBER_ASC_MAN2PONOROGO) | Mentor teknis, pembuat aplikasi web pemantau | Ide dan perangkat sensor adalah karya tim binaan untuk lomba ASC 2026. Bagian saya: mendampingi tim dan membangun dasbor (Vite, TypeScript, Gemini API / Firebase RTDB, Vercel) | ![ALoRa demo](https://img.shields.io/badge/-ALoRa%20demo%20aktif-2ea44f?style=flat-square) ![AMBER dijeda](https://img.shields.io/badge/-AMBER%20dijeda-6e7681?style=flat-square) |

### 🔬 Isi repo [`cybersec`](https://github.com/ReyMindThink/cybersec) <sub>(dikerjakan November 2026)</sub>

| Lab | Yang dikerjakan | Label |
| :-- | :-- | :-- |
| 🛡️ [Wazuh](https://github.com/ReyMindThink/cybersec/tree/main/labs/wazuh) | SIEM di Docker, simulasi brute force SSH ke target milik sendiri, alert dipetakan ke MITRE ATT&CK, satu aturan deteksi kustom | ![Hands-on lab](https://img.shields.io/badge/-Hands--on%20lab-0e75b6?style=flat-square) |
| 🐧 [Hardening Linux](https://github.com/ReyMindThink/cybersec/tree/main/linux-hardening-audit) | Audit dengan SCA Wazuh (CIS Ubuntu 24.04) dan Lynis, perbaikan SSH, ukur sebelum dan sesudah | ![Hands-on lab](https://img.shields.io/badge/-Hands--on%20lab-0e75b6?style=flat-square) |
| 🌐 [Analisis jaringan](https://github.com/ReyMindThink/cybersec/tree/main/labs/network) | Satu rekaman trafik SSH dibaca Wireshark, Suricata, dan Zeek, lalu dibandingkan | ![Hands-on lab](https://img.shields.io/badge/-Hands--on%20lab-0e75b6?style=flat-square) |
| 📘 [Playbook phishing](https://github.com/ReyMindThink/cybersec/tree/main/incident-response-playbook) | Playbook insiden (acuan NIST SP 800-61 Rev. 3, MITRE T1566) dan satu aturan Sigma yang divalidasi sintaksnya | ![Dokumen](https://img.shields.io/badge/-Dokumen%2C%20belum%20diuji%20insiden%20nyata-6e7681?style=flat-square) |

<details>
<summary><b>Alur lab Wazuh</b></summary>

```mermaid
flowchart LR
    A[Simulasi brute force SSH<br/>ke target milik sendiri] --> B[Agent Wazuh]
    B --> C[Alert di SIEM]
    C --> D[Dipetakan ke<br/>MITRE ATT&CK]
    D --> E[Aturan deteksi kustom]
```

</details>

> 🔒 Semua pengujian dilakukan pada mesin atau container milik sendiri.

---

## 🧭 Kepemimpinan teknis

| Peran | Cakupan | Skala |
| :-- | :-- | :-- |
| **Head of Technical Division**, Find IT! 2026 (Hackathon) | Memimpin 6 orang. Mengubah Hackathon dari tugas bawa pulang menjadi maraton coding 24 jam di lokasi, lengkap dengan dokumentasi teknis, matriks penilaian, juri, dan penanganan krisis | 179 tim · 698 peserta · panitia 140 orang |
| **Technical Division**, Find IT! 2025 (Hackathon) | Konsep dan alur, guidebook, ToR, matriks penilaian, juri, sesi pitching | 84 tim · 248 peserta |
| **Technical Division**, Technocorner (IoT) | Format dan panduan lomba, form penilaian, final offline, koordinasi juri | 32 tim · 96 peserta |
| **Mentor teknis**, ASC 2026 (teknologi tepat guna) | Mendampingi dua tim dari ide sampai prototipe bertema aksi iklim: sensor suara penebangan liar dan biofilter mikroalga | 2 tim · 2 prototipe |

---

## 🧪 Teknologi

**🔐 Keamanan**

![Secure SDLC](https://img.shields.io/badge/Secure_SDLC-C8321F?style=for-the-badge)
![Threat Modeling](https://img.shields.io/badge/Threat_Modeling-7C5CE0?style=for-the-badge)
![SAST / DAST](https://img.shields.io/badge/SAST_%2F_DAST-D9A648?style=for-the-badge)
![Wazuh](https://img.shields.io/badge/Wazuh-005571?style=for-the-badge&logo=wazuh&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Suricata](https://img.shields.io/badge/Suricata-EF6C00?style=for-the-badge)
![Zeek](https://img.shields.io/badge/Zeek-1F77B4?style=for-the-badge)
![Lynis](https://img.shields.io/badge/Lynis-2E7D32?style=for-the-badge)
![Sigma](https://img.shields.io/badge/Sigma-5C6BC0?style=for-the-badge)

**💻 Bahasa dan data**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![C#](https://img.shields.io/badge/C%23_.NET_8-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)

**⚙️ Membangun dan merilis**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)

**☁️ Cloud, jaringan, IoT**

![AWS](https://img.shields.io/badge/AWS_re%2FStart-FF9900?style=for-the-badge)
![Azure](https://img.shields.io/badge/Azure_AI_Foundry-0078D4?style=for-the-badge)
![Cisco Packet Tracer](https://img.shields.io/badge/Cisco_Packet_Tracer-049FD9?style=for-the-badge)
![Linux](https://img.shields.io/badge/Linux_%C2%B7_Bash-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Arduino](https://img.shields.io/badge/Arduino_%C2%B7_ESP32-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

---

## 📜 Sertifikasi

| Sertifikasi | Penyelenggara | Waktu |
| :-- | :-- | :-- |
| CCNA: Introduction to Networks | Cisco Networking Academy | Jun 2026 |
| AWS re/Start | Orbit Future Academy, Jakarta | Des 2025 |
| Lima sertifikat Python untuk data dan ML (statistika, deep learning, cleaning data, EDA, reduksi dimensi), 50 jam | DataCamp | Okt 2025 – Sep 2026 |
| Python, Gen AI dengan Microsoft Azure, data science dengan Microsoft Fabric | Dicoding | Des 2025 – Jun 2026 |
| Tiga sertifikat data science dengan R | DQLab | Des 2024 – Jan 2025 |

---

## 🌱 Sedang saya pelajari

| Topik | Lewat |
| :-- | :-- |
| 🕸️ Pemindaian dan pengujian web: Nmap, Burp Suite | Latihan terpandu |
| 🔍 Forensik dan SIEM lain: Splunk, Elastic | Latihan terpandu |
| 🍯 Honeypot dan detection engineering | Fase 2 [security-lab](https://github.com/ReyMindThink/security-lab) |

---

## 📊 Jejak aktivitas

<div align="center">

![Repo publik](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2FReyMindThink&query=%24.public_repos&label=Repo%20publik&color=0e75b6&style=for-the-badge&logo=github)
![Followers](https://img.shields.io/github/followers/ReyMindThink?style=for-the-badge&logo=github&label=Followers&color=203a43)
![Bahasa utama](https://img.shields.io/github/languages/top/ReyMindThink/phishing-detection-ml?style=for-the-badge&label=Bahasa%20utama&color=3776AB)
![Commit phishing-detection-ml](https://img.shields.io/github/commit-activity/t/ReyMindThink/phishing-detection-ml?style=for-the-badge&label=Commit%20phishing-detection-ml&color=C8321F)
![Update terakhir cybersec](https://img.shields.io/github/last-commit/ReyMindThink/cybersec?style=for-the-badge&label=Update%20terakhir%20cybersec&color=2ea44f)

</div>

---

## 🤝 Mari terhubung

Saya sedang mencari **magang di bidang cybersecurity atau secure software**. Kalau ingin berdiskusi tentang proyek, atau mencari kandidat magang yang memimpin dan membangun, silakan hubungi saya.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Terhubung_di_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rasyidrayhan/)
[![Email](https://img.shields.io/badge/Kirim_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rasyidrayhan1611@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,100:0f2027&height=100&section=footer" alt="footer" />

</div>
