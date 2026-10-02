Guide Complet : TP & Évaluations Réseaux Windows (Modules INF341 / INF261)

Bienvenue dans le guide de gestion et d'utilisation du dépôt des travaux pratiques et examens de réseaux sous Windows. Ce document vous explique de quoi il s'agit, comment configurer votre poste de travail, et comment préparer ou lancer une évaluation.

 1. De quoi s'agit-il ?

Ce répertoire regroupe le matériel pédagogique destiné à l'apprentissage et au contrôle des compétences en administration système et réseaux sous environnement Windows.

Il se compose de :

Sujets de TP Blancs : Pour s'exercer dans les conditions d'un examen réel.

Sujets d'Examens Pratiques : Les épreuves officielles (modules INF341 et INF261).

Fichiers de Réponses (.ans) : Des exemples de compositions et de résolutions d'étudiants servant de repères méthodologiques.

 2. Comment configurer son environnement de travail ?

Pour réaliser les exercices, simuler les pannes et configurer les services réseau, vous devez mettre en place un environnement virtualisé isolé.

Prérequis matériels et logiciels :

Hyperviseur : VirtualBox, VMware Workstation ou Hyper-V.

Systèmes d'exploitation requis :

Au moins une machine virtuelle Windows Server (ex: Windows Server 2016/2019/2022).

Au moins une machine virtuelle Windows Client (ex: Windows 10 ou 11) pour tester la connectivité et les services (DHCP, DNS).

Configuration réseau virtuelle :

Créez un réseau privé virtuel (Internal Network ou Host-Only) dans votre hyperviseur pour relier vos machines virtuelles entre elles sans les exposer directement à votre réseau physique principal.

Désactivez temporairement ou configurez finement le pare-feu de l'hôte si des interférences surviennent lors des tests de communication inter-machines.

 3. Comment lancer et passer une évaluation ?

Si vous êtes enseignant, formateur ou étudiant souhaitant s'auto-évaluer en conditions réelles, suivez cette procédure:

Étape A : Préparation de la session

Distribution du sujet : Ouvrez le fichier de sujet correspondant (fichiers .paper) pour prendre connaissance des consignes, de la topologie réseau demandée et des objectifs à atteindre (ex: configuration d'un domaine Active Directory, mise en place d'une étendue DHCP, résolution de noms DNS).

Isolation : Assurez-vous que l'environnement virtuel est vierge ou remis à un état initial (snapshots propres) avant le début du temps imparti.

Étape B : Déroulement et chronomètre

Lancez un chronomètre selon la durée indiquée sur le sujet (généralement entre 2h et 3h pour une épreuve pratique de TP).

Effectuez les configurations étape par étape sur votre machine virtuelle Windows Server / Client.

Étape C : Vérification et Correction

Réalisez les tests de validation demandés dans le sujet (commandes ipconfig, nslookup, ping, vérification des baux DHCP, journaux d'événements).

Comparez votre démarche et vos résultats finaux avec les fichiers de correction ou de compositions d'étudiants disponibles dans le dossier (.ans) pour identifier les axes d'amélioration.
