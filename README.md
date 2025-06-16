# 🛡️ Cyber Security Portfolio

Hi, I'm **Tate Pannam**, a cyber security student at Victoria University in Melbourne, Australia. This repository documents my progression through a wide range of Hack The Box (HTB) challenges, including **retired**, **active**, and **seasonal** boxes.

Each machine listed includes a proof image, a direct link to my full writeup, and a brief summary. This structure helps showcase my skills and serves as a reference for future engagements.

---

## ✅ Retired HTB Machines

| Machine        | Difficulty | Status  | Proof                                                  | Writeup                                                                                                 | Summary                                                    |
|----------------|------------|---------|---------------------------------------------------------|---------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| Lame           | Easy       | ✅ Done | <img src="https://raw.githubusercontent.com/inkedqt/ctf-writeups/main/HTB/proofs/lame.png" style="width:50%;" />         | [View](https://github.com/inkedqt/ctf-writeups/tree/main/HTB/Retired/lame)                             | Samba usermap exploit → SYSTEM shell                       |
| blue           | Easy       | ✅ Done | <img src="https://raw.githubusercontent.com/inkedqt/ctf-writeups/main/HTB/proofs/blue.png" style="width:50%;" />         | [View](https://github.com/inkedqt/ctf-writeups/tree/main/HTB/Retired/blue)                             | EternalBlue MS17-010 → SYSTEM shell                        |
| optimum        | Easy       | ✅ Done | <img src="https://raw.githubusercontent.com/inkedqt/ctf-writeups/main/HTB/proofs/optimum.png" style="width:50%;" />      | [View](https://github.com/inkedqt/ctf-writeups/tree/main/HTB/Retired/optimum)                          | Rejetto HFS RCE → SYSTEM with local tools                  |
| Bashed         | Easy       | ✅ Done | <img src="https://raw.githubusercontent.com/inkedqt/ctf-writeups/main/HTB/proofs/bashed.png" style="width:50%;" />       | [View](https://github.com/inkedqt/ctf-writeups/tree/main/HTB/Retired/Bashed)                           | Web fuzzing → PHP webshell → privesc via script abuse      |
| Beep           | Medium     | ✅ Done | <img src="https://raw.githubusercontent.com/inkedqt/ctf-writeups/main/HTB/proofs/beep.png" style="width:50%;" />         | [View](https://github.com/inkedqt/ctf-writeups/tree/main/HTB/Retired/Beep)                             | vtigerCRM LFI → legacy creds reuse → root via SSH          |
| Administrator  | Medium     | ✅ Done | <img src="https://raw.githubusercontent.com/inkedqt/ctf-writeups/main/HTB/proofs/administrator.png" style="width:50%;" />| [View](https://github.com/inkedqt/ctf-writeups/tree/main/HTB/Retired/Administrator)                    | AD domain takeover → Kerberoast → DCSync → Admin hash      |
| chemistry      | Easy       | ✅ Done | <img src="https://raw.githubusercontent.com/inkedqt/ctf-writeups/main/HTB/proofs/chemistry.png" style="width:50%;" />    | [View](https://github.com/inkedqt/ctf-writeups/tree/main/HTB/Retired/chemistry)                        | File parser RCE → LFI → SSH key reuse                      |
| headless       | Easy       | ✅ Done | <img src="https://raw.githubusercontent.com/inkedqt/ctf-writeups/main/HTB/proofs/headless.png" style="width:50%;" />     | [View](https://github.com/inkedqt/ctf-writeups/tree/main/HTB/Retired/headless)                         | Blind XSS → cookie theft → command injection → root        |
| Trick          | Medium     | ✅ Done | <img src="https://raw.githubusercontent.com/inkedqt/ctf-writeups/main/HTB/proofs/trick.png" style="width:50%;" />        | [View](https://github.com/inkedqt/ctf-writeups/tree/main/HTB/Retired/Trick)                            | DNS & SQLi → email RCE → fail2ban privesc                  |
| Waldo          | Medium     | ✅ Done | <img src="https://raw.githubusercontent.com/inkedqt/ctf-writeups/main/HTB/proofs/waldo.png" style="width:50%;" />        | [View](https://github.com/inkedqt/ctf-writeups/tree/main/HTB/Retired/Waldo)                            | LFI → SSH key → restricted shell escape → cap_dac_read     |
| alert          | Easy       | ✅ Done | <img src="https://raw.githubusercontent.com/inkedqt/ctf-writeups/main/HTB/proofs/alert.png" style="width:50%;" />        | [View](https://github.com/inkedqt/ctf-writeups/tree/main/HTB/Retired/alert)                            | Markdown XSS → LFI → group permission privesc              |

---

## 🔓 Active HTB Machines

| Machine     | Difficulty | Status  | Proof                                                  | Writeup                                                                                             | Summary                                                        |
|-------------|------------|---------|---------------------------------------------------------|-----------------------------------------------------------------------------------------------------|----------------------------------------------------------------|
| Titanic     | Easy       | ✅ Done | <img src="https://raw.githubusercontent.com/inkedqt/ctf-writeups/main/HTB/proofs/titanic.png" style="width:50%;" />     | [View](https://github.com/inkedqt/ctf-active/tree/main/HTB/Active/Titanic)                         | LFI → SQLite → Gitea → ImageMagick identify RCE → root         |
| Dog         | Easy       | ✅ Done | <img src="https://raw.githubusercontent.com/inkedqt/ctf-writeups/main/HTB/proofs/dog.png" style="width:50%;" />         | [View](https://github.com/inkedqt/ctf-active/tree/main/HTB/Active/Dog)                             | Git repo dump → CMS RCE → PHP utility privilege escalation     |
| Code        | Easy       | ✅ Done | <img src="https://raw.githubusercontent.com/inkedqt/ctf-writeups/main/HTB/proofs/code.png" style="width:50%;" />        | [View](https://github.com/inkedqt/ctf-active/tree/main/HTB/Active/Code)                            | SQLi → MD5 crack → path traversal → SSH → root                 |
| Planning    | Easy       | ✅ Done | <img src="https://raw.githubusercontent.com/inkedqt/ctf-writeups/main/HTB/proofs/planning.png" style="width:50%;" />    | [View](https://github.com/inkedqt/ctf-active/tree/main/HTB/Active/Planning)                        | Subdomain → Grafana RCE → docker escape → SUID privesc        |
| Nocturnal   | Easy       | ✅ Done | <img src="https://raw.githubusercontent.com/inkedqt/ctf-writeups/main/HTB/proofs/nocturnal.png" style="width:50%;" />   | [View](https://github.com/inkedqt/ctf-active/tree/main/HTB/Active/Nocturnal)                       | File leak → admin panel RCE → DB hash → SSH → CVE → root      |
| Environment | Medium     | ✅ Done | <img src="https://raw.githubusercontent.com/inkedqt/ctf-writeups/main/HTB/proofs/environment.png" style="width:50%;" /> | [View](https://github.com/inkedqt/ctf-active/tree/main/HTB/Active/Environment)                     | Laravel env bypass → avatar RCE → vault → sudo abuse          |

---

## 🗓️ Seasonal Boxes

| Machine       | Difficulty | Status  | Proof                                                  | Writeup                                                                                             | Summary                                                              |
|---------------|------------|---------|---------------------------------------------------------|-----------------------------------------------------------------------------------------------------|------------------------------------------------------------------------|
| TombWatcher   | Hard       | ✅ Done | <img src="https://raw.githubusercontent.com/inkedqt/ctf-writeups/main/HTB/proofs/tombwatcher.png" style="width:50%;" /> | [View](https://github.com/inkedqt/ctf-active/tree/main/HTB/Active/Tombwatcher)                     | gMSA abuse → ACL pivot → deleted obj restore → CVE → Domain Admin   |
| Fluffy        | Hard       | ✅ Done | <img src="https://raw.githubusercontent.com/inkedqt/ctf-writeups/main/HTB/proofs/fluffy.png" style="width:50%;" />      | [View](https://github.com/inkedqt/ctf-active/tree/main/HTB/Active/Fluffy)                          | NTLMv2 → shadow creds → ADCS ESC1 → Pass-the-Cert → Domain Admin    |
| Puppy         | Medium     | ✅ Done | <img src="https://raw.githubusercontent.com/inkedqt/ctf-writeups/main/HTB/proofs/puppy.png" style="width:50%;" />       | [View](https://github.com/inkedqt/ctf-active/tree/main/HTB/Active/Puppy)                           | LDAP → KeePass → password reset → DPAPI secrets → NTDS.dit dump     |
| Certificate   | Medium     | ✅ Done | <img src="https://raw.githubusercontent.com/inkedqt/ctf-writeups/main/HTB/proofs/certificate.png" style="width:50%;" /> | [View](https://github.com/inkedqt/ctf-writeups/tree/main/HTB/Active/Certificate)                   | Cert template abuse → Certipy → Evil-WinRM → Administrator shell    |

---

📂 Proof images stored in: `/HTB/proofs/`  
📚 Writeups in: `/HTB/<Category>/<Box>/README.md`

*Maintained by [inksec](https://github.com/inkedqt)*

