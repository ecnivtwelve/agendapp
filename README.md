# Agendapp

Un des meilleurs logiciels pour simplifier la gestion de votre agenda scolaire, et pour faciliter la prise de notes en cours.

Il offre une alternative pratique et efficace aux agendas papier, aux calendriers classiques, aux logiciels de prise de notes comme Word ou OneNote et aux logiciels de gestion de tâches comme Todoist ou Trello.

![Capture d'écran](https://raw.githubusercontent.com/johan-perso/agendapp/master/README.png)
<!-- TODO: on verra pour mettre la bonne image plus tard -->

## Installation

> **Note :** Agendapp n'est disponible que pour Windows 10/11 à l'heure actuelle.

* Téléchargez le fichier `Agendapp.zip` dans la section [Releases](https://github.com/johan-perso/agendapp/releases) de ce dépôt.
* Décompressez le fichier ZIP puis exécutez le fichier `Agendapp.exe` pour démarrer l'application.
* Vous pouvez créer un raccourci vers `Agendapp.exe` pour lancer l'application plus facilement.

Un installateur sera disponible dans une version future.

## Utilisation

### Démarrage

Il est possible de configurer via les paramètres de l'application différents réglages pour améliorer votre expérience d'utilisation. Par exemple, le démarrage automatique de l'application au démarrage de Windows, ou encore l'onglet par défaut.

### Agenda

L'onglet "Agenda" permet d'avoir une vue d'ensemble sur les prochains devoirs à effectuer. Une zone de texte principale permet d'écrire une date (via un format pratique, voir la section "Format de date" ci-dessous) pour lister les devoirs de cette date : lors de l'écriture d'une date dans cette zone de texte, les options pour ajouter un devoir à cette date apparaissent également.

Dans la zone de texte d'un devoir (son contenu), il est possible de faire clic droit en sélectionnant une partie du texte pour le mettre en forme. Il est également possible d'utiliser certains raccourcis clavier (voir la section "Raccourcis claviers" ci-dessous).

### Notes

L'onglet "Notes" permet de prendre des courtes notes sans perdre de temps, et de les retrouver facilement via une barre de recherche. Il est possible de mettre en forme le texte de la même manière que dans l'onglet "Agenda".

## Format de date

Le format de date utilisé par Agendapp lors de l'ajout ou de la recherche d'un devoir est fait pour être le plus pratique possible. La plupart des formes de dates "humaines" sont acceptées, par exemple :

* `demain` → renvoie demain
* `après-demain` → renvoie après-demain
* `mercredi` → renvoie le mercredi le plus proche qui n'est pas encore passé
* `14` → renvoie le 14 du mois en cours, ou du mois suivant si le 14 du mois en cours est déjà passé
* `14 décembre` → renvoie le 14 décembre de l'année en cours, ou de l'année suivante si le 14 décembre de l'année en cours est déjà passé
* `15 septembre 2023` → renvoie le 15 septembre 2023
* `15/09/2023` → renvoie le 15 septembre 2023

> **Note :** le format de date est en français, et ne peut pas être changé pour l'instant. Les jours de la semaine peuvent être abrégés en utilisant les trois premières lettres du jour (par exemple `lun` pour lundi). La saisie n'est pas sensible à la casse.

## Raccourcis claviers

### Pendant l'écriture d'un devoir ou d'une note

* `Ctrl + B` → met en gras le texte sélectionné
* `Ctrl + I` → met en italique le texte sélectionné
* `Ctrl + U` → souligne le texte sélectionné
* `Ctrl + O` → permet d'attacher un fichier (maximum 1 fichier)
* `Ctrl + Enter` → enregistre le devoir ou la note

### Dans l'application

* `Échap` → ferme la fenêtre ouverte
* `Ctrl/Alt + 1/&` → ouvre l'onglet "Agenda"
* `Ctrl/Alt + 2/é` → ouvre l'onglet "Notes"
* `Ctrl/Alt + 3/"` → ouvre l'onglet "Réglages"

### Hors de l'application

* `Ctrl + Shift + A` → ouvre l'application (ou la fermer si elle est déjà ouverte)

## Licence

MIT © [Johan](https://johanstick.fr)