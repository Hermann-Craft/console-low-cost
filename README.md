# Projet Console Portable Low Cost

**Slogan :**  
*« La qualité époustouflante accessible à tous »*

---

## 1. Public Cible

- **Utilisateurs finaux :**
  - **Joueurs à budget limité** souhaitant une expérience de jeu immersive et de qualité.
  - **Développeurs indépendants et passionnés de rétro** capables d’installer et d’optimiser leurs propres titres (les jeux rétro ne seront pas préinstallés pour respecter les droits d’auteur).
  - **Familles et enfants** : la console intégrera une gestion d’âge (système PEGI) pour offrir un contenu contrôlé aux plus jeunes et un mode libre pour les adultes.

- **Valeur ajoutée supplémentaire :**
  - Un **système économique circulaire** : les fonds récoltés seront réinvestis dans des services financiers dédiés à soutenir la création de nouveaux jeux par des talents indépendants.
  - Possibilité d’un **développement open source** de la plateforme (à discuter avec le collaborateur) pour encourager l’innovation et l’implication de la communauté.

---

## 2. Vision et Promesse

- **Accessibilité & Performance :**  
  Offrir une console low cost basée sur le Raspberry Pi (ex. Pi 5) qui prouve qu’un hardware abordable peut délivrer des performances exceptionnelles et des graphismes de qualité.

- **Écosystème Ouvert et Social :**  
  Un SDK/API complet, une documentation riche et des outils dédiés pour permettre aux développeurs de créer des jeux optimisés.  
  L’OS intégrera un **mode social poussé** pour faciliter la communication entre joueurs, incluant :
  - Un navigateur intégré.
  - Un dossier cloud pour le partage de fichiers.
  - Une gestion intuitive des fichiers et dossiers adaptée aux contrôles via manette et écran tactile.
  - Un **mode expert/développeur** offrant des paramètres avancés et des actions supplémentaires.

---

## 3. Choix du Hardware

- **Plateforme retenue :**  
  - **Raspberry Pi (ex. Pi 5)**
    - **Avantages :** Excellente performance, grande communauté et écosystème éprouvé.
    - **Coût :** Le SBC seul coûte environ 110 €, mais l’ensemble des composants (écran, audio, batterie, boîtier, etc.) peut atteindre environ 250 €.

- **Fonctionnalités attendues :**
  - Connectivité complète (WiFi, Bluetooth, USB, port SD, port jack, GPIO pour intégration de contrôleurs).
  - Écran tactile adapté pour une utilisation portable (avec option 4K en mode stationnaire).
  - Systèmes audio de qualité, refroidissement optimisé, lecteur RFID, montage de LED interactives.
  - Batterie intégrée avec circuit de charge.

---

## 4. Écosystème Logiciel & Contenus

- **Système d’exploitation :**
  - Basé sur un **fork du Raspberry OS** pour bénéficier d’une base stable et d’une interface intuitive.
  - Interface optimisée via Wayland/Wayfire garantissant rapidité, réactivité et support complet du tactile.
  - Gestion adaptée des fichiers et dossiers pour une navigation fluide via manette et écran tactile.
  - Fourniture de headers en C permettant aux jeux de communiquer efficacement avec l’OS.

- **Fonctionnalités sociales et collaboratives :**
  - **Mode social poussé** intégré à l’OS pour favoriser l’interaction entre joueurs :
    - Messagerie, ajout d’amis et notifications intégrées.
    - API permettant aux jeux d’accéder aux données sociales (scores, invitations, etc.).
    - Navigateur intégré et dossier cloud pour le partage de fichiers et contenus.
  - **Mode expert/développeur** offrant des paramètres avancés et des actions supplémentaires.

- **Contenus et jeux :**
  - Remakes et concepts inspirés des classiques, adaptés aux contraintes du hardware.
  - Compatibilité avec divers moteurs de jeux légers (Godot, Armory3D, GDevelop, etc.).
  - Développement d’un jeu « porte-étendard » valorisant la Réunion, vitrine du projet.

- **Support pour les développeurs :**
  - SDK/API complet, documentation détaillée, tutoriels, webinaires.
  - Forum de support et marketplace intégrée pour favoriser la collaboration entre développeurs et studios indépendants.

---

## 5. Plan de Développement & Lancement

- **Méthodologie :**
  - **Mode agile** avec des objectifs mensuels permettant des mises à jour continues et des livraisons progressives.
  - Collaboration synchronisée entre équipes hardware, software et design pour garantir une évolution harmonieuse.

- **Phases clés :**
  1. **Recherche & Prototypage :**  
     - Choix définitif du Raspberry Pi et réalisation des premiers prototypes.
  2. **Développement Logiciel :**  
     - Adaptation du fork de Raspberry OS, développement du SDK et intégration du mode social.
  3. **Intégration Hardware :**  
     - Assemblage de l’écran, des contrôles (gamepad), du système audio, du lecteur RFID, des LED, du refroidissement, de la batterie et conception du boîtier (prototype en impression 3D).
  4. **Tests & Optimisation :**  
     - Bêta-tests, recueil des feedbacks et suivi des indicateurs de performance via un cahier de mesures.
  5. **Lancement Commercial :**  
     - Mise en place d’une boutique en ligne, partenariats locaux et campagne de crowdfunding si nécessaire.

- **Indicateurs de performance et cahier de mesures :**
  - **Temps de réponse de l’OS** : Mesurer la réactivité générale et le temps de démarrage.
  - **Stabilité du système** : Taux d’erreurs/crash et stabilité lors de sessions prolongées.
  - **Performance graphique** : FPS moyen dans divers scénarios et temps de rendu.
  - **Durée de chargement des jeux** : Temps de lancement et de transitions entre les menus et les jeux.
  - **Bêta-testeurs et satisfaction utilisateur** : Taux de retours positifs, score de satisfaction sur l’interface tactile et mode manette.
  - **Performance du mode social** : Latence dans les interactions (messagerie, ajout d’amis), nombre d’utilisateurs actifs et volume d’échanges sur le dossier cloud.
  - **Efficacité énergétique** : Durée de vie de la batterie sous une utilisation typique.
  - **Suivi des mises à jour** : Stabilité et taux d'erreurs après chaque mise à jour logicielle.

- **Post-Lancement :**
  - Mises à jour logicielles régulières.
  - Support technique complet (forum, assistance en visio et présentiel) et programme de reprise/recyclage du hardware pour bénéficier de remises sur les nouvelles versions.

---

## Résumé

Notre projet vise à démocratiser l’accès à une expérience de jeu de haute qualité à un coût abordable. En misant sur le Raspberry Pi (ex. Pi 5) et un OS optimisé et riche en fonctionnalités (social, collaboratif et expert), nous démontrons qu’un hardware modeste peut délivrer des performances exceptionnelles et une interactivité poussée. Avec un écosystème ouvert (SDK, API, documentation complète) et une approche agile, cette console portable séduira tant les joueurs que les développeurs, tout en favorisant une économie circulaire pour soutenir l’innovation dans le monde du jeu vidéo.
