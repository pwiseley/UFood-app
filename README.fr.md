> 🇬🇧 [Read in English](README.md)

# UFood — Application de découverte de restaurants

Application frontend pour découvrir des restaurants, gérer des favoris et partager des visites avec des amis. Développée contre une API REST fournie par le cours.

Application développée en équipe dans le cadre du cours GLO-3012 Développement d'applications Web à l'Université Laval (Hiver 2026).

> Le dépôt original du cours est privé. Ce miroir contient uniquement ce README.

📖 [Documentation de l'API](https://ufoodapi.herokuapp.com/docs/)

🔗 [Vidéo démo complète](https://youtu.be/8KJPNR0Icmk)

---

## 📹 Démo

![Demo](assets/Demo.gif)

---

## Fonctionnalités

**Recherche et filtrage de restaurants**<br>
└─ `Rechercher des restaurants par nom, filtrer par fourchette de prix et genre.`

**Page restaurant**<br>
└─ `Détails complets : photos, informations, horaires, carte avec itinéraire, avis, recommandations, actions de visite et de favoris.`

**Suivi des visites**<br>
└─ `Enregistrer des visites avec date, évaluation et commentaire. Consulter les visites passées en lecture seule depuis le profil.`

**Listes de favoris**<br>
└─ `Créer, modifier et supprimer des listes nommées de restaurants favoris. Ajouter ou retirer des restaurants de n'importe quelle liste.`

**Mode carte**<br>
└─ `Basculer la page d'accueil entre la vue liste et la carte interactive. La recherche et les filtres fonctionnent dans les deux modes.`

**Profils utilisateurs**<br>
└─ `Consulter les restaurants récemment visités, les listes de favoris, les abonnés et les abonnements. S'abonner ou se désabonner d'un utilisateur.`

**Authentification**<br>
└─ `Connexion et inscription par courriel et mot de passe. Expiration du jeton gérée automatiquement.`

**Recherche d'utilisateurs**<br>
└─ `Rechercher d'autres utilisateurs directement depuis la barre de navigation.`

---

## 📸 Captures d'écran

*Aperçu de la page d'accueil*
![Home Page](assets/UFood-home-page.png)

*Page restaurant sur mobile*
![Restaurant Page](assets/restaurant-page-mobile.png)

---

## Technologies

- Vue 3, Vue Router, Axios
- Bootstrap 5
- Mapbox GL JS (carte et itinéraires)

---

## Structure du projet

```
src/
├── pages/          # Pages accueil, restaurant, profil, authentification
├── components/     # Composants UI réutilisables
├── router/         # Configuration Vue Router
└── services/       # Appels API Axios
App.vue
main.js
```

---

## Mes contributions

- Page restaurant complète (photos, informations, horaires, bouton visite, bouton favoris, fonctionnalité de partage)
- Carte interactive avec localisation du restaurant et itinéraires
- Section des avis du restaurant
- Section des recommandations du restaurant

---

## Contributeurs

Projet universitaire d'équipe — GLO-3102, Université Laval.

- **[Petiton Wiseley Paul-Enzer](https://github.com/pwiseley)**
- **[Ouedraogo Aliya Imann](https://github.com/aioue8)**
- **[Mamoudou Hamadou Mamoudou Hamadou](https://github.com/mamoudouhamadou)**
- **[Dongmeza Murielle Christelle](https://github.com/muriellec)**
- **[Kémila Bakary](https://github.com/kemilabakary)**

---

[petiton.dev](https://petiton.dev)
