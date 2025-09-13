# Asteroid Game
![image](https://cdn.discordapp.com/attachments/1133783225341321237/1399816520296562728/image.png?ex=68c65c79&is=68c50af9&hm=dae446913e1f1eeab1932c003617136be3149a36129b530d13d7e18fda1b5d25&)
Un jeu d'astéroïdes développé en Python avec **UV**, inspiré des classiques jeux d'arcade. Ce projet a été réalisé dans le cadre de la formation **Boot.dev** pour explorer les concepts de programmation orientée objet.

---

## 📌 Fonctionnalités

- **Contrôle du vaisseau** : Utilise les touches directionnelles pour déplacer le vaisseau et éviter les astéroïdes.
- **Génération aléatoire d'astéroïdes** : Les astéroïdes apparaissent de manière aléatoire et se déplacent à différentes vitesses.
- **Game Over** : La partie se termine en cas de collision avec un astéroïde.

---

## 🛠 Prérequis

- Python 3.10 ou supérieur
- [uv](https://docs.astral.sh/uv/getting-started/installation) project and package manager
- Access to a unix-like shell (e.g. zsh or bash)

---

## 🚀 Installation

1. Clone ce dépôt sur ta machine locale :
   ```bash
   git clone https://github.com/Rhaven3/asteroids.git
   cd asteroid-game
   ```
2. Créer un environnement virtuel et l'activé
   ```bash
   uv venv
   source .venv/bin/activate
   ```

3. lancé le jeu
   ```bash
   uv run main.py
   ```
