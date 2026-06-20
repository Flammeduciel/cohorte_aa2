Hub Cohorte 2 – Akieni Academy

Vitrine collective et point d’entrée central de la Cohorte 2 – Promotion 2026.

Ce dépôt contient le site web officiel du hub de la Cohorte 2. Il respecte scrupuleusement les exigences pédagogiques d’Akieni Academy : HTML5 sémantique, CSS classless et accessibilité.

---

📑 Table des matières

· Contexte et objectifs
· Fonctionnalités
· Technologies utilisées
· Structure du projet
· Installation et utilisation locale
· Déploiement
· Contribution
· Licence
· Contact

---

🎯 Contexte et objectifs

Ce projet est réalisé dans le cadre de la formation Akieni Academy, promotion 2026. Il a pour vocation de :

· Centraliser les informations relatives à la Cohorte 2 (présentation, projets, actualités).
· Offrir une vitrine collective des travaux des académiciens.
· Appliquer les bonnes pratiques du développement web (HTML sémantique, accessibilité, organisation).
· Servir de support pédagogique pour l’apprentissage du versionnement et du déploiement continu.

---

✨ Fonctionnalités

· Page d’accueil présentant le hub et la promotion.
· Liste des projets de la cohorte avec liens et descriptions.
· Formulaire de contact / indexation des académiciens.
· Navigation simple et cohérente entre les pages.
· Design épuré et responsive grâce à une feuille de style classless.
· Accessibilité renforcée (hiérarchie des titres, labels de formulaires).

---

🛠️ Technologies utilisées

Technologie Rôle
HTML5 sémantique Structure des pages (header, nav, main, section, article, aside, footer)
CSS classless Mise en forme via semanstyle.css (fourni par Akieni) – aucune classe ni identifiant
Git & GitHub Gestion de version et hébergement du code source
GitHub Pages Déploiement automatique sur la branche main

Absence de dépendances externes : zéro framework, zéro librairie JavaScript.

---

📂 Structure du projet

```
/
├── index.html          # Page d’accueil du hub
├── projets.html        # Liste des projets de la cohorte
├── contact.html        # Formulaire d’indexation (contact)
├── semanstyle.css      # Feuille de style classless (fournie)
└── README.md           # Documentation du projet (ce fichier)
```

---

🚀 Installation et utilisation locale

1. Cloner le dépôt :
   ```bash
   git clone https://github.com/flammeduciel/cohorte_aa2.git
   ```
2. Ouvrir le fichier index.html dans votre navigateur.
   Ou lancer un serveur local (optionnel) :
   ```bash
   npx serve
   ```
   Puis ouvrir http://localhost:3000.

---

🌐 Déploiement

Le site est automatiquement déployé via GitHub Pages sur la branche main.
Chaque push sur main déclenche une mise en ligne immédiate.

➡️ URL de production : https://flammeduciel.github.io/cohorte_aa2/

---

🤝 Contribution

Ce hub est maintenu collectivement par les académiciens de la Cohorte 2.
Toute contribution est la bienvenue !

Processus de contribution :

1. Créer une branche depuis main :
   ```bash
   git checkout -b feat/nom-fonctionnalite
   ```
2. Respecter les conventions de développement :
   · HTML : uniquement des balises sémantiques, pas de <div> ou <span> inutiles.
   · CSS : aucune classe ni ID – le style est exclusivement géré par semanstyle.css.
   · Validation W3C : chaque modification doit passer le validateur HTML sans erreur.
3. Tester la validation W3C avant de commit :
   · Utiliser le validateur W3C ou l’extension de votre navigateur.
4. Commiter avec des messages clairs (convention Conventional Commits) :
   · feat: pour une nouvelle fonctionnalité
   · fix: pour une correction de bug
   · docs: pour une mise à jour de la documentation
   · etc.
5. Ouvrir une Pull Request vers main et la soumettre à la relecture des pairs.

---

📄 Licence

Projet pédagogique réalisé dans le cadre d’Akieni Academy – Promotion 2026.
Usage interne à la Cohorte 2. Toute reproduction ou diffusion externe est soumise à l’autorisation des responsables pédagogiques.

---

📬 Contact

Pour toute question relative au hub, utilisez les canaux officiels de la Cohorte 2 sur WhatsApp.
Vous pouvez également ouvrir une issue sur ce dépôt GitHub pour signaler un problème ou suggérer une amélioration.

---

Dernière mise à jour : 18 juin 2026