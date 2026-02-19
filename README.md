# 🌟 Lumo — Agent IA pour enfants

> Un compagnon magique et bienveillant pour les enfants de 3 à 10 ans, propulsé par [Groq API](https://console.groq.com).

![Lumo](https://img.shields.io/badge/Lumo-Agent%20IA%20Enfants-FFD93D?style=for-the-badge&logo=sparkles)
![HTML](https://img.shields.io/badge/HTML-Pure-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-llama--3.3--70b-6BCB77?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-B185F5?style=for-the-badge)

---

## ✨ Fonctionnalités

- 🎂 **Adapté à l'âge** — langage automatiquement ajusté pour 3-5, 6-8 et 9-10 ans
- 🎤 **Reconnaissance vocale** — l'enfant peut parler au lieu de taper (Chrome / Edge)
- 🔊 **Synthèse vocale** — Lumo peut lire ses réponses à voix haute
- 📖 Histoires, devinettes, blagues, dessin, jeux à la demande
- 🛡️ **Sécurité intégrée** — refuse tout contenu inapproprié pour les enfants
- ⚡ **Ultra-rapide** — réponses en < 1 seconde grâce à Groq
- 📦 **Zéro dépendance** — un seul fichier HTML, aucun framework

---

## 🚀 Démo en ligne

👉 **[Ouvrir Lumo](https://ton-pseudo.github.io/lumo/)** ← *(remplace avec ton URL GitHub Pages)*

---

## 🛠️ Installation locale

```bash
# Cloner le repo
git clone https://github.com/ton-pseudo/lumo.git
cd lumo

# Servir localement (important pour que le micro fonctionne sans re-demande)
python -m http.server 8000

# Ouvrir dans le navigateur
# http://localhost:8000
```

> ⚠️ **Ne pas ouvrir `index.html` en double-cliquant** (protocole `file://`).  
> Chrome ne mémorise pas les permissions micro pour les fichiers locaux.  
> Utilise toujours `http://localhost:8000` ou GitHub Pages.

---

## 🔑 Configuration

1. Obtiens une clé API **gratuite** sur [console.groq.com](https://console.groq.com)
2. Ouvre l'app, entre ta clé dans le champ **🔑 Clé API Groq**
3. Choisis l'âge de l'enfant
4. Clique sur **Commencer !** 🚀

La clé est uniquement stockée en mémoire pendant la session — elle n'est jamais sauvegardée ni envoyée ailleurs que vers l'API Groq.

---

## 🎮 Ce que Lumo sait faire

| Activité | Exemple |
|----------|---------|
| 📖 Histoires | *"Raconte-moi une histoire avec un dragon !"* |
| 🎲 Devinettes | *"On joue aux devinettes ?"* |
| 🌈 Curiosité | *"Pourquoi le ciel est bleu ?"* |
| 😂 Blagues | *"Invente une blague !"* |
| 🎨 Créativité | *"Aide-moi à inventer un personnage"* |
| 🎮 Jeux | *"On joue à je pense à un animal ?"* |

---

## 🏗️ Architecture

```
index.html          ← toute l'application (HTML + CSS + JS)
README.md
LICENSE
```

Un seul fichier HTML autonome. Aucun build, aucune dépendance, aucun serveur requis.

**Stack :**
- **UI** : HTML / CSS / JS vanilla
- **IA** : [Groq API](https://console.groq.com) — modèle `llama-3.3-70b-versatile`
- **Vocal** : Web Speech API (natif navigateur)

---

## 🚢 Déploiement sur GitHub Pages

1. Fork ou clone ce repo
2. Va dans **Settings → Pages**
3. Source : **Deploy from a branch** → `main` → `/ (root)`
4. Ton app sera disponible sur `https://ton-pseudo.github.io/lumo/`

---

## 🛡️ Sécurité & Confidentialité

- ✅ Aucune donnée personnelle collectée
- ✅ Aucun cookie, aucun tracking
- ✅ La clé API reste dans le navigateur de l'utilisateur
- ✅ Les conversations ne sont pas sauvegardées
- ✅ Lumo refuse systématiquement tout contenu inapproprié pour les enfants

---

## 🤝 Contribuer

Les contributions sont les bienvenues ! N'hésite pas à :
- 🐛 Signaler un bug via les [Issues](https://github.com/ton-pseudo/lumo/issues)
- 💡 Proposer une fonctionnalité
- 🔀 Soumettre une Pull Request

---

## 📄 Licence

Ce projet est sous licence **MIT** — voir le fichier [LICENSE](LICENSE) pour les détails.

---

<p align="center">Fait avec ❤️ pour les enfants curieux du monde entier 🌍</p>
