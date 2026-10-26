### Bonjour 👋

Je conçois et livre des applications, des jeux, des sites et des outils d'automatisation **en pilotant Claude Code** : je fixe la direction, je découpe le travail, je relis, je teste, et l'IA écrit l'essentiel du code.

*I build and ship apps, games, websites and automation pipelines by directing Claude Code as my main engineering tool.*

---

## Projets

| Projet | Ce que c'est | Stack |
|---|---|---|
| [**Frigo anti-gaspi**](https://github.com/aethernitas2024-jpg/frigo-anti-gaspi) | Appli Android : scan de code-barres, rappels avant péremption, recettes avec les restes, allergènes et régimes | Vite · Capacitor 8 · ML Kit · tests + CI |
| [**Botaenica**](https://github.com/aethernitas2024-jpg/botaenica) | Jeu mobile relaxant de jardin botanique, musique générée en Web Audio, illustrations produites en local | Vite · Capacitor (Android/iOS) · tests + CI |
| [**Aethernitas**](https://github.com/aethernitas2024-jpg/aethernitas-sites) | Portail d'édition indépendante : sites Obscyversum et Runikron, pages d'histoires cinématiques, assistant IA à mémoire | HTML/JS · Three.js · Node · API OpenAI |
| [**Lazy Kodo pipeline**](https://github.com/aethernitas2024-jpg/lazy-kodo-pipeline) | Chaîne de production de shorts TikTok automatisés, des données jusqu'au rendu final | Python · edge-tts · faster-whisper · Pillow · FFmpeg |
| [**wowedit**](https://github.com/aethernitas2024-jpg/wowedit) | Montage vertical automatique dont chaque coupe tombe sur un temps de la musique | Python · analyse de beat · FFmpeg |

Autres projets non publiés : un jeu de cartes et un RPG sous **Unreal Engine 5.7 (C++)**, des addons World of Warcraft en Lua, un tracker Hearthstone.

---

## Ma façon de travailler avec Claude Code

- **Je découpe le travail et je décide.** Chaque projet commence par une spécification courte. Je valide le résultat étape par étape et je recadre quand c'est hors sujet : une refonte qui ne me convient pas est annulée, pas « améliorée ».
- **Je vérifie avant de livrer.** J'écris des tests (`node --test`), une CI GitHub Actions pour les applis et des contrôles visuels dans le navigateur intégré. Je n'accepte pas un détecteur ou une fonctionnalité sans preuve à l'image.
- **J'outille l'agent.** J'utilise des skills sur mesure (dont une qui génère images et vidéos en local avec ComfyUI, FLUX et Wan 2.2 sur RTX 4090), des serveurs MCP (navigateur, Obsidian, Unreal Engine), des hooks, des sous-agents en parallèle et des tâches planifiées. J'ai trié une bibliothèque d'environ 160 skills pour n'en garder que l'utile.
- **Je garde des pipelines reproductibles.** Un script de plan puis un script de rendu : chaque vidéo ou build se relance à l'identique après une correction.
- **Je protège les secrets et les contenus.** Les clés d'API restent dans `.env`, les contenus payants et les médias lourds restent hors des dépôts, et les commits passent par une adresse e-mail masquée.

---

## Outils

`Claude Code` · `JavaScript` · `Python` · `Node.js` · `Vite` · `Capacitor` · `Three.js` · `Unreal Engine 5 / C++` · `Lua` · `FFmpeg` · `ComfyUI` · `Git / GitHub Actions`
