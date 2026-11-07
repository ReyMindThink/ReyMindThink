# Halo, saya Rasyid

Mahasiswa yang sedang belajar **keamanan siber dan machine learning**. Fokus saya: memakai ML untuk membantu deteksi ancaman, dan membangun lab kecil untuk memahami cara deteksinya bekerja.

_Student learning cybersecurity and ML, building small, evidence-backed labs._

## Cerita utama

Dari **mendeteksi email phishing dengan ML** sampai **melihat serangan di SIEM**: satu proyek yang saya bangun dari nol, dan satu rangkaian lab yang dikerjakan langsung di laptop sendiri.

## Proyek utama

| Proyek                                                                         | Isi                                                                                                                                                                                                                                                | Status       |
| :----------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------- |
| [phishing-detection-ml](https://github.com/ReyMindThink/phishing-detection-ml) | Detektor email phishing tiga kelas (ham, spam, phishing): TF-IDF + regresi logistik, evaluasi per kelompok untuk menghindari kebocoran data, penjelasan model dengan SHAP, aplikasi lokal Flask, CI GitHub Actions, rilis model dengan hash SHA256 | Dibangun     |
| [cybersec](https://github.com/ReyMindThink/cybersec)                           | Lab keamanan: SIEM Wazuh, hardening Linux, analisis jaringan, playbook insiden                                                                                                                                                                     | Hands-on lab |

## Isi repo `cybersec` (dikerjakan November 2026)

| Lab                                                                                                | Yang dikerjakan                                                                                                               | Label                                   |
| :------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------- |
| [Wazuh](https://github.com/ReyMindThink/cybersec/tree/main/labs/wazuh)                             | SIEM di Docker, simulasi brute force SSH ke target milik sendiri, alert dipetakan ke MITRE ATT&CK, satu aturan deteksi kustom | Hands-on lab                            |
| [Hardening Linux](https://github.com/ReyMindThink/cybersec/tree/main/linux-hardening-audit)        | Audit dengan SCA Wazuh (CIS Ubuntu 24.04) dan Lynis, perbaikan SSH, ukur sebelum dan sesudah                                  | Hands-on lab                            |
| [Analisis jaringan](https://github.com/ReyMindThink/cybersec/tree/main/labs/network)               | Satu rekaman trafik SSH dibaca Wireshark, Suricata, dan Zeek, lalu dibandingkan                                               | Hands-on lab                            |
| [Playbook phishing](https://github.com/ReyMindThink/cybersec/tree/main/incident-response-playbook) | Playbook insiden (acuan NIST SP 800-61 Rev. 3, MITRE T1566) dan satu aturan Sigma yang divalidasi sintaksnya                  | Dokumen, belum diuji pada insiden nyata |

Semua pengujian dilakukan pada mesin atau container milik sendiri. Setiap lab mencatat kendala dan batasannya.

## Sedang saya pelajari

Pemindaian dan pengujian web (Nmap, Burp), serta forensik dan SIEM lain (Splunk, Elastic) lewat latihan terpandu. Ini baru rencana belajar, belum klaim kemampuan.

## Teknologi yang saya pakai langsung

Python, scikit-learn, SHAP, Flask, Docker, Git dan GitHub Actions, Wazuh, Wireshark, Suricata, Zeek, Lynis, Sigma.

## Kontak

[https://www.linkedin.com/in/rasyidrayhan/](https://www.linkedin.com/in/rasyidrayhan/)
