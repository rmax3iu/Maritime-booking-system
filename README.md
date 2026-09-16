<!-- |-------------------------------------------------------------------------------------------| -->
<!-- |                                         LANGUAGE                                          | -->
<!-- |-------------------------------------------------------------------------------------------| -->
<div align="right">
  <a href="README.md">
    <img src="https://img.shields.io/badge/🇫🇷 Français-1e3a5f?style=for-the-badge" alt="Français"/>
  </a>
  <a href="README.en.md">
    <img src="https://img.shields.io/badge/🇬🇧 English-555555?style=for-the-badge" alt="English"/>
  </a>
</div>

<!-- |-------------------------------------------------------------------------------------------| -->
<!-- |                                          HEADER                                           | -->
<!-- |-------------------------------------------------------------------------------------------| -->
<h1 align="left">🚢 Maritime Booking System</h1>

<p align="justify">
Ce projet est un système de réservation pour une compagnie maritime fictive, développé en binôme dans le cadre d'un projet. Il se compose d'une application console en C# permettant d'effectuer une réservation, et d'un site web permettant de consulter les informations liées à cette réservation.
</p>

> **L'API scolaire utilisée par le site web est aujourd'hui fermée**. Le code reste disponible pour montrer le travail effectué, mais le site ne peut plus récupérer de données en direct pour certaines pages.
</p>

<!-- |-------------------------------------------------------------------------------------------| -->
<!-- |                                    TECHNOLOGIES                                           | -->
<!-- |-------------------------------------------------------------------------------------------| -->
## Technologies utilisées

![C#](https://img.shields.io/badge/C%23-239120?logo=csharp&logoColor=white&style=for-the-badge) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white&style=for-the-badge) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white&style=for-the-badge) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black&style=for-the-badge) ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?logo=visualstudiocode&logoColor=white&style=for-the-badge) ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white&style=for-the-badge)

<!-- |-------------------------------------------------------------------------------------------| -->
<!-- |                                       À PROPOS                                            | -->
<!-- |-------------------------------------------------------------------------------------------| -->
## À propos du projet

<p align="justify">
L'application C# permet à un utilisateur de réserver une traversée pour des personnes et des véhicules. À l'issue de la réservation, un fichier au format JSON est généré et récapitule l'ensemble des informations saisies.
</p>

<p align="justify">
Le site web permet ensuite de consulter les informations liées à cette réservation : carte d'embarquement avec QR code, facture, tableau de bord et statistiques. Il propose également des pages indépendantes des données de réservation : présentation des bateaux, horaires et tarifs, ainsi qu'une page de paramètres.
</p>

<p align="justify">
L'application C# utilise la bibliothèque Newtonsoft.Json pour la génération du fichier JSON. Le site web utilise QRCode.js pour la génération des QR codes des cartes d'embarquement, et html2canvas pour le téléchargement des factures. La mise en page du site s'appuie sur Flexbox et le site est responsive, y compris sur mobile.
</p>

<!-- |-------------------------------------------------------------------------------------------| -->
<!-- |                                        APERÇU                                             | -->
<!-- |-------------------------------------------------------------------------------------------| -->
## 📸 Aperçu

**Image du menu d'accueil du site :**
<div align="center">
  <img src="Images/image1.png" alt="Menu d'accueil" width="600"/>
</div>
<div align="center">
  <img src="Images/image2.png" alt="Menu d'accueil" width="600"/>
</div>
<br>

**Image de la page de consultation d'une réservation :**
<div align="center">
  <img src="Images/image3.png" alt="Consultation d'une réservation" width="600"/>
</div>
<br>

**Image de la page des horaires et tarifs :**
<div align="center">
  <img src="Images/image4.png" alt="Horaires et tarifs" width="600"/>
</div>
<br>

**Image de la page de présentation des bateaux :**
<div align="center">
  <img src="Images/image5.png" alt="Présentation des bateaux" width="600"/>
</div>
<br>

**Image de la page de paramètres :**
<div align="center">
  <img src="Images/image6.png" alt="Paramètres" width="600"/>
</div>
<br>

<p align="justify">
Les pages carte d'embarquement, facture, tableau de bord et statistiques ont bien été développées, mais ne peuvent plus être démontrées en conditions réelles depuis la fermeture de l'API scolaire.
</p>
<br>

<!-- |-------------------------------------------------------------------------------------------| -->
<!-- |                                        UTILISATION                                        | -->
<!-- |-------------------------------------------------------------------------------------------| -->
## 🚀 Lancer le projet

<p align="justify">
<b>Application C# :</b> Pour lancer l'application C#, il faut ouvrir le dossier Prog dans Visuel Studio, puis lancez l'exécution en appuyant sur F5 ou en cliquant sur la flèche verte. Vous pouvez également compiler le projet puis exécuter directement le fichier .exe généré.
</p>

<p align="justify">
<b>Site web :</b> Pour lancer le site web, il faut ouvrir le dossier Web dans Visual Studio Code, puis lancez le site avec l'extension Live Server en cliquant sur le bouton Go Live en bas à droite de l'éditeur.
</p>
<br>

<!-- |-------------------------------------------------------------------------------------------| -->
<!-- |                                    STRUCTURE DU PROJET                                    | -->
<!-- |-------------------------------------------------------------------------------------------| -->
## 📁 Structure du projet

```text
Maritime-booking-system/
├── Prog/                     # Application console C#
├── Web/                      # Site web après-vente (HTML, CSS, JS)
├── Images/                   # Images utilisées dans le README
├── Rapport SAÉ 11.pdf        # Rapport du projet
├── LICENSE
└── README.md
└── README.en.md
```
<br>

<!-- |-------------------------------------------------------------------------------------------| -->
<!-- |                                       LIMITATIONS                                         | -->
<!-- |-------------------------------------------------------------------------------------------| -->
## 🔧 Limitations connues

<p align="justify">
Une fois un numéro de réservation saisi sur le site, il n'est actuellement pas possible de se déconnecter pour en consulter une autre sans recharger manuellement la page. C'est un point d'amélioration identifié pour une future version. Le design du site, dont je me suis chargé à l'époque, était adapté aux exigences du projet, mais je le trouve aujourd'hui un peu dépassé avec le recul.
</p>
<br>

<!-- |-------------------------------------------------------------------------------------------| -->
<!-- |                                       CONTRIBUTEURS                                       | -->
<!-- |-------------------------------------------------------------------------------------------| -->
## 👥 Contributeurs

Travail réalisé en binôme dans le cadre d'un projet à l'IUT Robert Schuman.

<div align="center">

[![rmax3iu](https://img.shields.io/badge/rmax3iu-1e3a5f?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rmax3iu)
[![AgentOutsiders](https://img.shields.io/badge/AgentOutsiders-1e3a5f?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AgentOutsiders)

</div>
