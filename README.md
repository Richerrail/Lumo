# 🌟 Lumo — Agent IA pour enfants

> Un compagnon magique et bienveillant pour les enfants de 3 à 10 ans, propulsé par [Groq](https://console.groq.com) ou [Gemini](https://aistudio.google.com).

![Lumo](https://img.shields.io/badge/Lumo-Agent%20IA%20Enfants-FFD93D?style=for-the-badge&logo=sparkles)
![HTML](https://img.shields.io/badge/HTML-Pure-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-llama--3.3--70b-6BCB77?style=for-the-badge)
![Gemini](https://img.shields.io/badge/Gemini-2.5--flash-4285F4?style=for-the-badge&logo=google)
![License](https://img.shields.io/badge/License-MIT-B185F5?style=for-the-badge)

---

## ✨ Fonctionnalités

- 🎂 **Adapté à l'âge** — langage automatiquement ajusté pour 3-5, 6-8 et 9-10 ans
- 🤖 **Choix du moteur IA** — ⚡ Groq (ultra-rapide) ou ✨ Gemini (idéal pour les bavards)
- 🎤 **Reconnaissance vocale** — l'enfant peut parler au lieu de taper (Chrome / Edge)
- 🔊 **Synthèse vocale** — Lumo lit ses réponses à voix haute, sans lire les emojis
- 🎨 **Images pour dessiner** — modèles illustrés pour 30+ sujets (animaux, nature, véhicules...)
- 🎮 **Jeux interactifs** — Lumo anime lui-même les jeux (devinettes, vrai/faux, charades...)
- 🔗 **Liens jeux en ligne** — CrazyGames & ClassicGameZone, uniquement pour les 7 ans et +
- 🛡️ **Sécurité intégrée** — refuse tout contenu inapproprié pour les enfants
- 💾 **Clés mémorisées** — plus besoin de ressaisir la clé API à chaque ouverture
- 📦 **Zéro dépendance** — un seul fichier HTML, aucun framework

---

## 🚀 Démo en ligne

👉 **[Ouvrir Lumo](https://richerrail.github.io/Lumo/)**

---

## 🔑 Configuration

### Option A — Groq (ultra-rapide ⚡)
1. Obtiens une clé API **gratuite** sur [console.groq.com](https://console.groq.com)
2. La clé commence par `gsk_...`
3. Limites gratuites : 30 req/min, 14 400 req/jour

### Option B — Gemini 2.5 Flash (idéal pour longues conversations ✨)
1. Obtiens une clé API **gratuite** sur [aistudio.google.com](https://aistudio.google.com)
2. Clique sur **Get API Key** → **Create API key**
3. La clé commence par `AIza...`
4. Limites gratuites : 15 req/min, 1 500 req/jour

> Les clés sont stockées dans `localStorage` — elles restent dans ton navigateur et ne sont jamais envoyées ailleurs que vers l'API choisie.

---

## 🎮 Ce que Lumo sait faire

| Activité | Exemple |
|----------|---------|
| 📖 Histoires | *"Raconte-moi une histoire avec un dragon !"* |
| 🎲 Devinettes | *"On joue aux devinettes ?"* |
| 🌈 Curiosité | *"Pourquoi le ciel est bleu ?"* |
| 😂 Blagues | *"Invente une blague !"* |
| 🎨 Dessin | *"Je veux dessiner un chat, aide-moi !"* |
| 🎮 Jeux | *"On joue à je pense à un animal ?"* |
| 🔗 Jeux en ligne | *"Tu connais un jeu sur internet ?"* (7 ans+) |

---

## 🏗️ Architecture

```
index.html      ← toute l'application (HTML + CSS + JS vanilla)
README.md
LICENSE
```

Un seul fichier HTML autonome. Aucun build, aucune dépendance, aucun serveur requis.

**Stack :**
- **UI** : HTML / CSS / JS vanilla
- **IA** : [Groq API](https://console.groq.com) (`llama-3.3-70b-versatile`) ou [Gemini API](https://aistudio.google.com) (`gemini-2.5-flash`)
- **Vocal** : Web Speech API (natif navigateur)
- **Images** : Pixabay CDN + Wikimedia Commons (domaine public)

---

## 🚢 Déploiement sur GitHub Pages

1. Fork ou clone ce repo
2. Va dans **Settings → Pages**
3. Source : **Deploy from a branch** → `main` → `/ (root)`
4. Ton app sera disponible sur `https://ton-pseudo.github.io/lumo/`

> ✅ Sur GitHub Pages, Chrome mémorise la permission micro définitivement.

---

## 🛠️ Utilisation locale

```bash
# Cloner le repo
git clone https://github.com/richerrail/Lumo.git
cd Lumo

# Servir localement (nécessaire pour que le micro fonctionne)
python -m http.server 8000

# Ouvrir dans Chrome
# http://localhost:8000
```

> ⚠️ Ne pas ouvrir `index.html` en double-cliquant (`file://`).  
> Chrome ne mémorise pas les permissions micro pour les fichiers locaux.

---

## 🛡️ Sécurité & Confidentialité

- ✅ Aucune donnée personnelle collectée
- ✅ Aucun cookie, aucun tracking
- ✅ Les clés API restent dans le navigateur (`localStorage`)
- ✅ Les conversations ne sont pas sauvegardées
- ✅ Lumo refuse tout contenu inapproprié pour les enfants
- ✅ Liens externes uniquement pour les 7 ans et plus

---

## 🤝 Contribuer

Les contributions sont les bienvenues !
- 🐛 Signaler un bug via les [Issues](https://github.com/richerrail/Lumo/issues)
- 💡 Proposer une fonctionnalité
- 🔀 Soumettre une Pull Request

---

## 📄 Licence

Ce projet est sous licence **MIT** — voir le fichier [LICENSE](LICENSE) pour les détails.

---

<p align="center">Fait avec ❤️ pour les enfants curieux du monde entier 🌍</p>
