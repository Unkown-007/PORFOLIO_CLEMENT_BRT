# PORFOLIO_CLEMENT_BRT
MON PORTFOLIO POUR ME CONNAITRE UN PEU.
# Clément Berton — Cybersecurity & Engineering Student

> Étudiant en Bachelor Ingénierie & Cybersécurité à l'EFREI · Passionné par la sécurité offensive, les réseaux, les systèmes embarqués et l'automatisation

---

## À propos

Je suis étudiant en 1ère année de Bachelor Ingénierie & Cybersécurité à l'EFREI (Villejuif), avec une approche résolument autodidacte : je n'attends pas les cours pour apprendre. Mes certifications Cisco ont été obtenues en totale autonomie, mes audits sont réalisés sur des cibles réelles, et mes projets personnels couvrent un spectre large — du développement logiciel à l'électronique, en passant par la modélisation 3D et la création de jeux vidéo.

Ce qui me motive en cybersécurité, c'est la dimension technique et stratégique à la fois : comprendre comment un système fonctionne, trouver ses failles avant que quelqu'un de malveillant ne le fasse, et proposer des correctifs concrets. Mon intérêt va particulièrement vers la sécurité offensive (pentest, reconnaissance, analyse de surface d'attaque) et la sécurité des systèmes industriels (OT/ICS), un domaine encore trop peu sécurisé.

En dehors de l'informatique, je suis saxophoniste depuis 10 ans (plusieurs orchestres, concerts devant public), passionné d'aéronautique, de systèmes militaires embarqués et de jeux vidéo stratégiques. Ces activités m'ont appris la rigueur, la gestion de projet collaboratif et la capacité à performer sous pression.

Je recherche actuellement un **stage de minimum 2 mois en cybersécurité** pour mettre en pratique mes compétences et progresser dans ce domaine.

---

## Expérience professionnelle

### Stagiaire Développeur — Cisco France *(Juin 2023)*
**20 Rue Washington, 75008 Paris**

Stage au sein des équipes de développement de Cisco France :
- Développement en **C++** et **Python**
- Connexion et intégration d'une **API** externe
- Automatisation du traitement de données sous **Excel**
- Découverte de l'environnement professionnel d'un acteur mondial de la cybersécurité et des réseaux

---

## Certifications

| Certification | Émetteur | Date | Statut |
|---|---|---|---|
| Cisco Networking Basics | Cisco Networking Academy | Mai 2026 | ✅ Obtenu |
| Google Cybersecurity Certificate | Google / Coursera | 2026 | 🔄 En cours |
| Cisco Networking Essentials | Cisco Networking Academy | 2026 | 🔄 Prévu |
| CCNA (200-301) | Cisco | 2026–2027 | 🎯 Objectif |

> Toutes les certifications Cisco ont été préparées et obtenues **en totale autonomie**, sans formation guidée ni academy.

---

## Compétences techniques

### Sécurité & Pentest
`Kali Linux` `nmap` `sqlmap` `whatweb` `curl` `Reconnaissance passive` `Analyse de surface d'attaque` `CORS` `OSINT` `Analyse TLS/HTTPS` `Test d'intrusion web` `Analyse des en-têtes HTTP` `CVSS` `Rapport de vulnérabilités`

### Réseaux
`TCP/IP` `IPv4/IPv6` `DNS` `HTTP/2` `TLS 1.3` `DHCP` `Routage` `Protocoles réseau` `Wireshark`

### Programmation
`C` `C++` `Python` `JavaScript` `HTML` `CSS` `PHP` `SQL` `Arduino`

### Systèmes & Virtualisation
`Linux (Kali, Ubuntu)` `Windows` `VMware` `Oracle VirtualBox` `Docker` `GitHub` `VS Code`

### Architecture & Données
`Représentation binaire/flottants` `Architecture des ordinateurs` `Modélisation de données`

### 3D & Prototypage
`Blender` `SolidWorks` `Impression 3D` `Découpe laser` `Arduino` `Soudage` `Électronique`

---

## Projets

### 🔐 Audit de sécurité — ZEBRIX "Gwen" *(Mai 2026)*
**Type :** Reconnaissance passive + Tests actifs | **Cible :** Tableau de bord de supervision OT/ICS | **Outils :** Kali Linux, nmap, sqlmap, curl, whatweb

Audit complet d'un système ZEBRIX développé pour SPIE ICS, permettant de surveiller et contrôler des équipements physiques industriels exposés sur Internet.

**Résultats :**
- **Note globale : D (Dangereux)**
- 6 vulnérabilités **critiques** identifiées : CORS cross-origin exploité avec PoC, secrets hardcodés en clair dans le JS public, bypass CAPTCHA en 5 lignes, VPN PPTP cassé (MS-CHAPv2 vulnérable depuis 2012), FTP non chiffré exposé, hébergement mutualisé (shared cPanel) incompatible avec un système OT
- 8 vulnérabilités **élevées** dont URL API OT exposée sans authentification, lockout IP contournable via VPN
- Points positifs : TLS 1.3 + X25519 + AES-256-GCM, WAF/IPS actif (sqlmap bloqué)
- Rapport complet remis avec recommandations de remédiation par ordre de priorité

---

### ☀️ Système de suivi solaire automatisé *(Terminale — Projet de fin d'année)*
Conception, construction et programmation d'un tracker solaire autonome :
- Détection de luminosité multi-capteurs
- Motorisation et asservissement en temps réel
- Optimisation du rendement énergétique
- Outils : Arduino, C++, capteurs LDR, servomoteurs

---

### 🤖 Hackathon — Robot NAO — Thème Éducation *(Décembre 2024)*
Développement d'un algorithme d'IA pour l'aide aux élèves en difficulté, en équipe pluridisciplinaire sur une semaine :
- Conception et implémentation de l'algorithme
- Gestion de projet hebdomadaire
- Présentation devant jury et large public
- Langages : C++, Python, JavaScript

---

### 🎮 Développement & Modding Jeux Vidéo *(Projet personnel continu)*
- Conception et modélisation 3D d'objets avec **Blender**
- Programmation de scripts en **C++** sous Visual Studio Code
- Création, modification et publication de **mods** pour jeux vidéo
- Intégration de systèmes de gameplay personnalisés

---

### 🔧 Prototypage & Électronique *(Projets personnels)*
- Fabrication de maquettes en atelier (découpe laser, impression 3D, ponçage, soudage)
- Montage et configuration d'ordinateurs
- Expériences de prototypage avec Arduino
- Circuits simples et systèmes embarqués

---

## Formation

### EFREI — Villejuif
**Bachelor Ingénierie & Cybersécurité** *(2025 – 2027)*

Modules principaux :
- Réseaux & Systèmes : TCP/IP, bases réseaux, systèmes d'exploitation (Windows, Linux), sécurité des systèmes
- Cybersécurité : cryptographie, sécurité des bases de données, ethical hacking, supervision et gestion des infrastructures
- Programmation : C, C++, Python, JavaScript, HTML, CSS, PHP, SQL
- Virtualisation & Cloud : VMware, VirtualBox, introduction au cloud computing, Docker
- Projets & Compétences transversales : gestion de projet, communication, anglais, espagnol

### Lycée La Salle Saint-Nicolas — Issy-les-Moulineaux
**BAC Technologique STI2D** *(2025)*

---

## Langues

| Langue | Niveau |
|---|---|
| Français | Natif |
| Anglais | B2 |
| Espagnol | B1 |

---

## Passions & Centres d'intérêt

- 🎷 **Saxophone** — 10 ans de pratique, plusieurs orchestres, concerts et présentations devant public, gestion de projet artistique collaboratif
- ✈️ **Aéronautique & systèmes embarqués** — intérêt particulier pour les systèmes militaires et les véhicules technologiques terrestres
- 🎮 **Jeux vidéo stratégiques** — notamment à thématique militaire
- 🔒 **Cyberdéfense & sécurité OT/ICS** — veille active sur les enjeux de sécurité des systèmes industriels

---

## Contact

📧 clement.berton@efrei.net  
🔗 [LinkedIn](https://www.linkedin.com/in/clement-berton92)  
🐙 [GitHub](https://github.com/Unkown-007)  
📍 Île-de-France

---

*Portfolio en cours de construction — labs, write-ups CTF et projets à venir.*
