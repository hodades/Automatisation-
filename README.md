# Optimisation Automatisée des Emails et Réunions avec des Solutions IA
![s)](https://github.com/user-attachments/assets/0dc02283-f30c-40a2-b12c-5043d1ccd643)




## Description

Ce projet propose une automatisation complète des flux de travail pour la gestion des emails et des réunions Google Meet, en utilisant des outils IA comme ChatGPT, Whisper API, Google Sheets, et Hugging Face. L'objectif est de simplifier les processus d'analyse, de tri et de récapitulation des emails et réunions en automatisant les tâches manuelles et répétitives.

## Workflow

### Workflow 1 : Automatisation des Emails

1. **Email** : Les emails sont reçus et capturés pour traitement.
2. **Traitement ChatGPT** : Utilisation de ChatGPT pour extraire des informations clés comme la date, l'objet, le contenu et l'urgence de l'email.
3. **Retranscription dans Google Sheets** : Les données extraites sont automatiquement transcrites dans une feuille Google Sheets pour un suivi structuré.
![image](https://github.com/user-attachments/assets/aaa79c3d-df10-43c0-adcd-164286c06aa0)



### Workflow 2 : Automatisation des Réunions Google Meet

1. **Réunion Google Meet** : Enregistrement d'une réunion Google Meet dans un dossier dans le drive.
2. **Enregistrer la Réunion et Stockage sur Google Drive** : La réunion est enregistrée et stockée dans Google Drive pour une utilisation ultérieure.
3. **Speech-to-Text Whisper API** : Transcription de l'audio de la réunion en texte à l'aide de l'API Whisper.
4. **Hugging Face (Modèle de Résumé Automatique)** : Utilisation de l'API Hugging Face pour générer automatiquement un résumé basé sur la transcription obtenue.
   ![image](https://github.com/user-attachments/assets/fb9f50f8-6134-4809-81f9-c8bfa9c57718)


### Résultat

- **Envoi d'un Email avec le Résumé** : Une fois le résumé généré, on a le résultat dans notre folder sur le drive
  ![ 2024-10-11 at 15 15 51](https://github.com/user-attachments/assets/371cfb9a-efdd-4335-a4e3-8a9e14a3c7cc)

  ![image](https://github.com/user-attachments/assets/632b5a53-f15b-40c0-9db0-acc17723e798)


## Technologies Utilisées
J'ai choisi 5 minutes d'une video meeting random sur youtube : https://www.youtube.com/watch?v=rOqgRiNMVqg&t=2s
- **ChatGPT** : Pour l'analyse et l'extraction d'informations à partir des emails.
- **Google Sheets** : Pour stocker et organiser les données extraites des emails.
- **Google Meet** : Outil de visioconférence utilisé pour organiser et enregistrer les réunions.
- **Google Drive** : Pour stocker les enregistrements des réunions.
- **Whisper API** : API de reconnaissance vocale pour transcrire les enregistrements de réunions.
- **Hugging Face** : Modèle NLP utilisé pour générer des résumés automatiques des réunions.
- **MAKE**: https://www.make.com/en
## Bénéfices

- **Gain de temps** : Automatisation des tâches répétitives comme le tri des emails et la rédaction de résumés de réunions.
- **Réduction des erreurs** : Minimisation des erreurs humaines dans le traitement des emails et la gestion des réunions.
- **Centralisation des informations** : Toutes les données sont centralisées et organisées dans Google Sheets et Google Drive pour un accès facile.

## Installation et Utilisation

1. **Pré-requis** :
   - Un compte Google pour utiliser Google Sheets, Google Meet, et Google Drive.
   - Un compte Make pour automatiser le processus de connexion entre les différents outils.
   - Accès à ChatGPT et Whisper API pour les fonctionnalités d'IA.
   - Accès à Hugging Face pour les modèles NLP de génération de résumés.

2. **Mise en place** :
   - Créer les automatisations avec Zapier pour connecter Gmail, Google Sheets, et les autres services.
   - Configurer ChatGPT et Whisper API pour analyser les emails et transcrire les réunions.
   - Utiliser Hugging Face pour générer automatiquement des résumés.

Voici le tableau Comparatif :

| **Tâche**                          | **Manuel**                   | **Automatisé avec IA**        |
|-------------------------------------|------------------------------|-------------------------------|
| **Lecture/Tri d'emails**            | 1 heure/jour                 | Quelques minutes/jour         |
| **Enregistrement de réunions**      | 1 minute                     | Automatique                   |
| **Prise de notes**                  | 30 min à 1 h par réunion     | Automatisé (Whisper API)      |
| **Rédaction de compte-rendu**       | 30 min à 1 h par réunion     | Automatisé (Hugging Face)     |
| **Envoi de compte-rendu**           | Manuel                       | Automatique                   |
| **Temps total estimé (par semaine)**| 15 heures                    | ~1 à 2 heures                 |


## Conclusion
Grâce à l'automatisation avec des outils IA comme ChatGPT, Whisper API et Hugging Face, le workflow est considérablement accéléré, réduisant le temps de traitement des emails et des réunions de plusieurs heures par semaine à seulement quelques minutes. L'IA permet également de minimiser les erreurs humaines et d'améliorer l'efficacité globale.

