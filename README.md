# Formation professionnelle : intelligence artificielle en restauration commerciale

Kit opérationnel et pédagogique complet pour le parcours certifiant de 7 jours (49 heures) consacré à l'intelligence artificielle appliquée à la restauration commerciale indépendante.

Ce dispositif répond aux contraintes de terrain des exploitants, chefs de cuisine et responsables de salle : exécution directe dans le navigateur, zéro ligne de code à manipuler, zéro frais d'abonnement API obligatoire et conformité Qualiopi.

Programme complet accessible à l'adresse https://caroheymes.github.io/formation-ia-restauration-commerciale/
---

## Objectifs opérationnels

- Automatiser l'audit arithmétique des factures de grossistes et bloquer les dérives du coût matière à réception.
- Calibrer les fiches techniques au centime près pour garantir 70 à 72% de marge brute sur chaque plat de la carte.
- Traiter 100% des avis Google Maps et plateformes de réservation sous 24h avec validation humaine en un clic.
- Générer des devis et menus de banquet personnalisés en moins de 3 minutes dès réception d'une demande.
- Protéger les données d'exploitation sensibles (marges, fiches de paie, fichiers clients) contre les fuites et tentatives d'injection.
- Récupérer entre 6 et 8 heures de charge administrative hebdomadaire par établissement.

---

## Structure du répertoire

### 1. Diaporamas et supports de formation (44 slides)

Les diaporamas intègrent l'intégralité des 14 cas pratiques chiffrés, les solutions méthodologiques et le verbatim exhaustif du formateur pour chaque slide.

- [formation_master_ia_restauration.pptx](formation_master_ia_restauration.pptx) : version de référence ardoise sombre (palette haute horlogerie et gastronomie).
- [formation_ia_restauration_fond_clair.pptx](formation_ia_restauration_fond_clair.pptx) : version alternative fond clair optimisée pour les salles de formation très éclairées.
- [presentation.html](presentation.html) : diaporama web interactif plein écran avec défilement au clavier, sélecteur de thème (sombre, clair, contraste) et tiroir latéral de notes d'animation (touche `N`).
- [presentation-client-locked.html](presentation-client-locked.html) : version de prospection commerciale avec masquage optique des solutions des slides 8 à 43 et déblocage de la slide 44.

### 2. Outils d'exploitation et automatisation métier

- [gsheet_suite_restaurant_ia.js](gsheet_suite_restaurant_ia.js) : script Google Apps Script prêt à l'emploi pour piloter fiches techniques, mercuriales et avis directement dans Google Sheets sans clé API.
- [guide_deploiement_google_sheets.md](guide_deploiement_google_sheets.md) : pas-à-pas illustré pour installer le classeur sur tablette ou smartphone en 3 minutes.
- [portail_restaurant_ia.html](portail_restaurant_ia.html) : interface web autonome utilisable sans connexion internet pour la saisie des mercuriales et la rédaction assistée.
- [RestaurantIA.exe](RestaurantIA.exe) : exécutable Windows portable (zéro installation, zéro droit administrateur requis).
- Lanceurs multi-plateformes pour postes fixes :
  - `Lancer_Restaurant_IA_Windows.bat` (Windows)
  - `Lancer_Restaurant_IA_Mac.command` (macOS)
  - `Lancer_Restaurant_IA_Linux.sh` (Linux)

### 3. Guides et référentiels pédagogiques

- [programme_formation_ia_restauration.md](programme_formation_ia_restauration.md) : déroulé pédagogique détaillé jour par jour conforme aux exigences Qualiopi.
- [guide_ateliers_prompts_restauration.md](guide_ateliers_prompts_restauration.md) : bibliothèque complète des 14 prompts système métier avec consignes de cadrage et garde-fous de confidentialité.
- [dossier_technique_financier_restauration.md](dossier_technique_financier_restauration.md) : étude financière comparative (ROI chiffré à 12 500 € par an, plan de continuité d'activité et budget 0 € d'API).

---

## Déroulé du parcours 

- Session 1 : Diagnostic d'exploitation, détection des hémorragies de marge et cadrage des risques d'injection.
- Session 2 : Numérisation tactile et audit automatique des bordereaux de livraison et mercuriales de saison.
- Session 3 : Ingénierie des fiches techniques au centime, yield management et rentabilité des formules du midi.
- Session 4 : Réputation en ligne, protocole de réponse aux avis négatifs et requêtes juridiques CNIL.
- Session 5 : Devis express pour banquets d'entreprises, événementiel et sécurisation des acomptes.
- Session 6 : Hygiène HACCP, fiches de poste personnalisées, plannings d'équipe et plan de continuité sans internet.
- Session 7 : Examen pratique d'autonomie, remise des attestations Qualiopi et calendrier de suivi à 30, 60 et 90 jours.

---

## Prérequis et déploiement

Aucun préalable technique ou compétence en programmation n'est exigé.

1. Option Navigateur pur (recommandée) : ouvrir `presentation.html` ou importer `gsheet_suite_restaurant_ia.js` dans Google Sheets.
2. Option Bureau Windows : exécuter `RestaurantIA.exe` en double-cliquant sur le fichier.
3. Option Local sans connexion : ouvrir `portail_restaurant_ia.html` dans Chrome, Safari, Edge ou Firefox.

---

## Cadre réglementaire et propriété

Support rédigé par Caroline Heymes.
Eligibilité aux financements des opérateurs de compétences (OPCO) du secteur de l'hôtellerie-restauration.
Tous les cas pratiques reposent sur des données anonymisées de brasseries et restaurants traditionnels de la région lyonnaise.
