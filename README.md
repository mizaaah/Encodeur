# Encodeur

🛠️ Cyber Utility Kit (Encodeur / Décodeur / Hasher)

Application Web Mono-Fichier pour les opérations de sécurité de base.

Ce kit est un outil indispensable pour tout pentester, développeur ou étudiant en sécurité qui a besoin de manipuler rapidement des chaînes de caractères pour l'analyse de payloads, l'étude des paramètres d'URL, et la vérification des hachages.

🚀 Fonctionnalités

Cet outil regroupe les fonctions de manipulation de données les plus courantes dans une interface simple et sombre de style terminal.

Opération

Description

Utilité en Pentest

Base64 Encoder

Convertit une chaîne de texte en son équivalent Base64.

Préparation de payloads ou d'informations d'identification pour l'injection dans des requêtes.

Base64 Decoder

Décode une chaîne Base64 en texte lisible.

Analyse des paramètres de cookies, de jetons JWT ou de payloads encodés dans les requêtes HTTP.

URL Encoder (%XX)

Encode les caractères spéciaux selon le format % (pourcent-encoding).

Création de payloads pour l'exploitation de failles XSS ou d'Injections SQL.

URL Decoder

Convertit les codes %XX en leur caractère d'origine.

Analyse rapide des paramètres d'URL complexes ou doublement encodés.

SHA-256 Hasher

Calcule le hachage unidirectionnel (empreinte) d'une chaîne.

Vérification de l'intégrité de fichiers ou comparaison d'une chaîne connue avec un hachage trouvé.

💻 Installation et Utilisation

L'avantage majeur de ce kit est sa simplicité : il ne nécessite aucune installation ni connexion Internet.

Téléchargement : Téléchargez le fichier unique utilitaire_securite.html sur votre machine.

Exécution : Ouvrez simplement le fichier utilitaire_securite.html avec n'importe quel navigateur Web moderne (Chrome, Firefox, Edge, etc.).

Utilisation :

Entrez la chaîne de données dans la zone "Données à traiter (Input)".

Sélectionnez l'opération souhaitée dans le menu déroulant.

Cliquez sur le bouton "Exécuter l'Opération". Le résultat apparaît instantanément dans la zone "Résultat (Output)".

🛡️ Sécurité et Vie Privée

Étant donné que cet outil est un fichier HTML/JS local :

Toutes les opérations sont exécutées localement dans votre navigateur.

Aucune donnée n'est envoyée à un serveur externe.

Le hachage SHA-256 utilise l'API native crypto.subtle du navigateur, garantissant l'utilisation d'une cryptographie standard et performante.

🔑 Technologies Utilisées

HTML5 / JavaScript : Le cœur fonctionnel de l'application.

Tailwind CSS** :** Utilisé pour le style responsive et l'interface sombre (mode "hacker").