# LunarHack_chatbot

# 🧠🎓 Smart Campus Assistant – Project Reveal

Welcome to the Smart Campus Assistant, developed as part of **Lunar Hack 1.0**. This unified platform consists of two intelligent components:

1. **Campus Navigation and Inquiry Bot**
2. **Lost-and-Found Assistant**

---

## 📌 Project Overview

This application aims to improve the daily life of students on campus by combining AI-powered tools to:
- Guide users through campus buildings and rooms.
- Provide detailed administrative procedure information.
- Efficiently handle lost and found items using smart matching.

---

## 🧭 PART 1: Navigation and Inquiry Bot

An intelligent chatbot that helps users:
- Navigate the university campus .
- Understand administrative procedures .

🧳 PART 2: Lost-and-Found Assistant
Un assistant intelligent conçu pour faciliter la gestion des objets perdus ou trouvés sur le campus.

🎯 Objectif
Simplifier la déclaration et la recherche d’objets perdus grâce à une interface conversationnelle et un système de correspondance automatisée.

💬 Interface Utilisateur
Zone de saisie : pour écrire des messages au chatbot.

Deux boutons principaux :

🔍 LOST – pour déclarer un objet perdu.

🧾 FOUND – pour déclarer un objet trouvé.

⚙️ Fonctionnement
Déclaration :

Si vous avez perdu un objet, décrivez-le aussi précisément que possible.

Si vous avez trouvé un objet, entrez également une description détaillée.

Correspondance intelligente :

Le chatbot compare automatiquement les descriptions saisies.

Si une correspondance est trouvée, il vous affiche le numéro de téléphone de la personne concernée pour permettre une prise de contact directe.

🔁 Modes d’interaction
Ce module, comme celui de navigation, fonctionne avec un système de modes exclusifs :

L’utilisateur active un mode (LOST ou FOUND) en cliquant sur l’un des boutons.

Le mode actif reste en surbrillance jusqu’à ce qu’un autre soit sélectionné.

Cela garantit une interaction claire et ciblée.

### 🔧 Technologies used
- **Embeddings**: SentenceTransformers (`all-MiniLM-L6-v2`)
- **RAG**: FAISS 
- **Interface**: Python Flask with HTML5

