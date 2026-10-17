# Politique de confidentialité de Gestion Patients

**Dernière mise à jour :** 16 octobre 2026

**Inova Labs** exploite l’application mobile **Gestion Patients** (ci-après, l’« Application »). La présente politique de confidentialité décrit nos pratiques concernant la collecte, l’utilisation et la divulgation des informations personnelles et des informations relatives à l’appareil lorsque vous utilisez l’Application.

---

### 1. Architecture « Local-First » et souveraineté des données

Gestion Patients est conçue selon une architecture **Local-First** (priorité au stockage local). **Nous n’exploitons, ne possédons et ne maintenons aucune base de données backend indépendante ni aucun serveur cloud destiné à stocker vos dossiers patients ou vos données financières.** Tous les noms des patients, historiques de consultation, statuts de paiement et notes saisis dans l’Application sont stockés **exclusivement dans la mémoire locale de votre appareil**.

---

### 2. Informations traitées et collectées

* **Dossiers patients et données de paiement (sous le contrôle de l’utilisateur) :** toutes les données financières que vous saisissez restent stockées localement sur votre téléphone.

* **Sauvegardes Google Drive (via une application Web Apps Script) :** si vous choisissez de sauvegarder votre base de données, l’Application transmet les données de sauvegarde de manière sécurisée vers votre compte Google Drive personnel, au moyen d’une application Web personnalisée Google Apps Script déployée sous votre contrôle. Aucun serveur tiers ne traite ni ne stocke le contenu de cette sauvegarde : les données sont transférées directement depuis l’Application vers votre espace de stockage Google Drive personnel.

* **Performances et statistiques d’utilisation de l’Application (Firebase) :** nous intégrons **Firebase Analytics**, **Firebase Crashlytics** et **Firebase Remote Config** (services fournis par Google LLC) afin de collecter des données techniques ne permettant pas, à elles seules, de vous identifier :
  * **Analytics :** statistiques d’utilisation, parcours de navigation dans l’Application et fréquence d’interaction avec les fonctionnalités, afin d’améliorer l’expérience utilisateur.
  * **Crashlytics :** rapports automatiques de plantage, traces de pile (*stack traces*) et informations sur l’état de l’appareil au moment du plantage, afin de diagnostiquer et de corriger les anomalies.
  * **Remote Config :** gestion de la configuration à distance, notamment pour vérifier les mises à jour de l’Application, activer ou désactiver certaines fonctionnalités et communiquer des annonces de maintenance.

* **Fonctionnement « Offline-First » et connectivité réseau :** l’Application fonctionne entièrement hors ligne pour la gestion quotidienne des dossiers patients et le suivi des consultations en clinique. Une connexion réseau est utilisée uniquement lorsque l’utilisateur lance une sauvegarde via Google Apps Script ou lorsque Firebase traite en arrière-plan les données analytiques et les rapports de plantage.

* **Données biométriques locales :** si vous activez la sécurité biométrique (déverrouillage par empreinte digitale ou reconnaissance faciale), l’authentification est entièrement gérée par le module de sécurité du système d’exploitation de votre appareil. L’Application n’accède jamais aux données biométriques brutes, ne les enregistre pas et ne les stocke pas.

---

### 3. Utilisation de vos informations

* **Fonctionnement local :** afficher, rechercher et organiser les dossiers patients, ainsi que calculer localement sur votre appareil les soldes dus par les patients.

* **Stabilité et amélioration de l’Application :** les données Crashlytics sont utilisées exclusivement pour identifier les anomalies, les problèmes de stabilité et les ralentissements. Les données Analytics nous aident à comprendre l’utilisation des fonctionnalités afin d’améliorer l’ergonomie de l’Application.

* **Maintenance et mises à jour :** Remote Config permet de gérer les paramètres de l’Application et de vous informer des mises à jour obligatoires ou facultatives.

---

### 4. Services tiers

L’Application intègre les services tiers suivants :

* **Firebase (Google LLC) :** utilisé pour les statistiques d’utilisation, les rapports de plantage et la gestion de la configuration à distance. Le traitement des données effectué par Firebase est soumis aux règles de confidentialité de Google.

* **Google Apps Script et Google Drive :** utilisés uniquement pour permettre les sauvegardes de la base de données vers votre compte Google Drive personnel, à votre initiative.

---

### 5. Conservation, contrôle et suppression des données

* **Activation et codes de licence :** l’accès à l’Application nécessite un code d’activation valide. Il vous appartient de protéger vos identifiants d’activation.

* **Suppression depuis l’Application :** vous pouvez à tout moment supprimer des dossiers patients individuellement, supprimer une clinique entière, ce qui supprime automatiquement tous les dossiers patients qui lui sont associés, ou réinitialiser votre base de données locale.

* **Désinstallation de l’Application et invalidation du licence :** la désinstallation de l’Application ou l’effacement de ses données depuis les paramètres de votre appareil supprime définitivement de celui-ci toutes les bases de données locales de l’Application, sauf si elles ont été sauvegardées au moyen de votre procédure Google Apps Script. En outre, la désinstallation ou l’effacement des données de l’Application réinitialise son état d’activation local : les licences précédemment utilisés deviennent invalides et un nouveau code d’activation est nécessaire pour réactiver l’Application.

---

### 6. Santé et conformité en matière de protection des données

Gestion Patients est exclusivement un outil de suivi administratif destiné aux professionnels de santé. Il incombe à l’utilisateur (médecin) de s’assurer que le stockage et le traitement des informations relatives aux patients respectent les règles de confidentialité médicale, de protection de la vie privée des patients et de protection des données applicables dans sa juridiction.

---

### 7. Confidentialité des enfants

L’Application est strictement destinée à un usage professionnel par des praticiens adultes. Nous ne collectons pas sciemment de données personnelles concernant des enfants de moins de 13 ans.

---

### 8. Modifications de la présente politique de confidentialité

Nous pouvons modifier la présente politique de confidentialité à tout moment. Toute modification sera publiée sur cette page, accompagnée d’une date de mise à jour révisée.

---

### 9. Nous contacter

Pour toute question ou préoccupation concernant cette politique de confidentialité, vous pouvez nous contacter à l’adresse suivante :

* **E-mail :** patienttracker.support@gmail.com
