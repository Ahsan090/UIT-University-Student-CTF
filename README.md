# UIT-GDGoC-CTF-2025 🚩

&gt; A beginner-friendly jeopardy-style Capture-The-Flag **exclusively for UIT students**, organized by the Google Developer Group on Campus (GDGoC) to spark interest in cybersecurity.

---

## 📌 Event Snapshot
| **Who** | Undergrad / graduate students of **UIT University only** |
| **Team size** | 1 – 3 people (no cross-team help) |
| **Format** | Onsite jeopardy (no attack/defence, no external servers) |
| **Difficulty** | Easy → Medium → Hard (perfect for 1st–4th semester CS / SE) |
| **Date** | *TBA* |
| **Time** | *TBA* |
| **Venue** | UIT campus computer labs |
| **Cost** | *TBA* |
| **Prizes** | *TBA* |

---

## 🧩 Challenge Categories
1. Digital Forensics  
2. OWASP Top-10 (XSS, SQL-Injection, Broken Auth, etc.)  
3. Binary Exploitation (C, Python)  
4. Cryptography    
5. Web (HTML, JS)  

Every task ships with:
* Downloadable files / OVA file that can be opened in virtual environment   
* Hints 
* Full step-by-step solution after the contest

---

## 🏗️ Build & Run (Organizers)
```bash
# 1. Start scoreboard
cd infra
docker-compose up -d
# 2. Import challenges
python scripts/load_challenges.py challenges/
# 3. Hand out `GAME_NET` Wi-Fi creds to teams

“The best way to learn security is to break things—legally.”
— UIT-GDGoC-CTF-2025
