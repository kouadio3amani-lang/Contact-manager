# ContactSpaceM
Une application de gestion de contact
## Description
Ce projet est une application de **gestion de contact** permettant de centraliser et organiser les informations personnelles des employés d'une entreprise ou autre service. Elle a pour but d'éviter la désorganisation et les pertes de données,Tout en redant plus flexible l'accès au information.
## Implémentation futures
* Intégration d'une interface graphique
* Intégration de code qr
* intégration d'une version web
## Fonctionnalités
- **Ajouter un contact**
- **Modifier** 
- **Supprimer**
- **Voir**
- **Rechercher**
## Fonctionnalités futures
* Historique des opérations
* Interface de connexion
## Technoligie utilisées
* Frontend : **HTML, CSS**
* Backend : **Python**
* Framework : **Flask**
* Base de données : **SQLITE**
## Installation 
1. **Cloner le repo**

     git clone https://github.comkouadio3amani-lang/Contact-manager.
     git 

    cd Contact-manager
2. **Creér un environnement virtuel** 

    *python -m venv venv*
     
    **Activer l'environnment :**\
        **Windows:** 
        venv\Scripts\activate  
        **Mac / Linux:**
        source venv/bin/activate
3. **Intaller les dependances**

pip install -r requirements.txt
4. **Lancer l'application**

python app.py
5. **Pour le web**
http://127.0.0.1:5000
## Utilisation
1. **Fonctionnement général**
* Page d'acceuil
* Formulaire
* Liste des contacts
2. **Ajouter un contact**
- Remplir le formulaire 
- Valider
- Le contact apparaît dans la liste
3. **Modifier un contact**
- Selectionner le contact dans la liste
- Cliquer sur le bouton modifier
- Changer les informations
- Enregistrer
4. **Supprimer un contact**
- Selectionner le contact dans la liste
- Cliquer sur le bouton supprimer
- Le contact disparaît de la liste
5. **Recherche**
- Rechercher par (Information)
- filtrer les résultats
## Structure du projet

Le projet est organisé en deux parties principales :

###  Application Web (Flask)
- Dossier : `web_app/`
- Permet d'accéder à une interface via navigateur
- Gère les contacts via des routes Flask

###  Application Desktop (CustomTkinter)
- Dossier : `desktop_app/`
- Interface graphique locale
- Permet de gérer les contacts sans navigateur

###  Données
- Dossier : `data/`
- Stocke les contacts (JSON ou base de données)
- Partagé entre les deux applications
## Licence
Ce projet est sous licence MIT.

*MIT License*

*Copyright (c) 2026 Manassé*

*Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:*

*The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.*

*THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.*
