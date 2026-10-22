# Politique de Confidentialité pour Mes Honoraires

**Dernière mise à jour :** 22 octobre 2026

**Inova Labs** exploite l'application mobile **Mes Honoraires** (ci-après l'« Application »). La présente Politique de Confidentialité vous informe de nos politiques concernant la collecte, l'utilisation et la divulgation des informations personnelles et de l'appareil lorsque vous utilisez notre Application.

---

### 1. Architecture Locale & Souveraineté des Données
Mes Honoraires est conçue comme une application fonctionnant localement sur l'appareil. **Nous n'exploitons, ne possédons ni ne maintenons aucune base de données centrale ni serveur cloud tiers pour stocker vos dossiers de bénéficiaires ou vos enregistrements d'honoraires.** Tous les noms de bénéficiaires, journaux d'interventions, statuts de paiement et notes saisies dans l'Application sont stockés **strictement et exclusivement dans la mémoire locale de votre appareil**.

---

### 2. Informations Traitées et Collectées

* **Dossiers Bénéficiaires & Honoraires (Gérés par l'Utilisateur) :** Toutes les données financières et administratives que vous saisissez restent localement sur votre téléphone.

* **Sauvegardes Google Drive (via Application Web Apps Script) :** Si vous choisissez de sauvegarder votre base de données, l'Application transmet vos données de sauvegarde de manière sécurisée à votre compte Google Drive personnel via une application web Google Apps Script personnalisée, déployée sous votre contrôle. Aucun serveur tiers ne traite ni ne stocke ces données de sauvegarde ; elles vont directement de votre application vers votre espace de stockage personnel Google Drive.

* **Performance de l'Application & Analyses (Firebase) :** Nous intégrons **Firebase Analytics**, **Firebase Crashlytics** et **Firebase Remote Config** (services fournis par Google LLC) pour collecter des données techniques non identifiables :
  * **Analytics :** Métriques d'utilisation, parcours de navigation dans l'application et fréquence d'utilisation des fonctionnalités afin de nous aider à améliorer l'expérience utilisateur.
  * **Crashlytics :** Rapports de plantage automatisés, traces d'exécution et état de l'appareil au moment d'une erreur pour nous aider à diagnostiquer et résoudre les dysfonctionnements.
  * **Remote Config :** Utilisé pour vérifier les mises à jour de l'application et les annonces de maintenance.

* **Architecture Hors Ligne & Connectivité Réseau :** L'application fonctionne entièrement hors ligne pour la gestion quotidienne des dossiers bénéficiaires et le suivi des établissements. Elle se connecte au réseau uniquement lorsque l'utilisateur exécute une sauvegarde Google Apps Script ou lorsque Firebase traite les données d'analyse et de plantage en arrière-plan.

* **Données Biométriques Locales :** Si vous activez la sécurité biométrique (empreinte digitale / déverrouillage facial), l'authentification est gérée entièrement par le module de sécurité du système d'exploitation de votre appareil. L'Application n'accède, n'enregistre ni ne stocke jamais vos données biométriques brutes.

---

### 3. Utilisation de Vos Informations
* **Opérations Locales :** Pour afficher, rechercher, organiser et calculer localement sur votre appareil les soldes de paiement des bénéficiaires et générer votre bilan des honoraires.

* **Stabilité & Amélioration de l'Application :** Les données Crashlytics sont utilisées strictement pour identifier les bogues, les problèmes de stabilité et les ralentissements de performance. Les données Analytics nous aident à comprendre comment les fonctionnalités sont utilisées afin d'en améliorer l'ergonomie.

* **Maintenance & Mises à Jour :** Remote Config est utilisé pour gérer les configurations au niveau de l'application et vous informer des mises à jour obligatoires ou optionnelles.

---

### 4. Services Tiers
Notre Application intègre les services tiers de confiance suivants :
* **Firebase (Google LLC) :** Pour les analyses, les rapports de plantage et la gestion de la configuration à distance. Les politiques de confidentialité de Google régissent les données traitées par Firebase.
* **Google Apps Script & Google Drive :** Utilisés uniquement pour faciliter les sauvegardes de base de données initiées par l'utilisateur vers son compte Google Drive personnel.

---

### 5. Conservation, Contrôle et Suppression des Données
* **Jetons d'Activation & de Licence :** L'accès à l'Application nécessite un jeton d'activation valide. Vous êtes responsable de la préservation de vos identifiants d'activation.

* **Suppression dans l'Application :** Vous pouvez supprimer des dossiers bénéficiaires individuels ou supprimer un établissement entier — ce qui supprimera automatiquement tous les dossiers bénéficiaires associés à cet établissement, à tout moment depuis l'Application, ou réinitialiser votre base de données locale.

* **Désinstallation & Invalidation du Jeton :** La désinstallation de l'Application ou l'effacement des données de l'application via les paramètres de votre téléphone supprimera définitivement toutes les bases de données locales de votre appareil (sauf si elles ont été sauvegardées via votre routine Google Apps Script). De plus, la désinstallation ou l'effacement des données révoque l'état d'activation local, les jetons précédemment utilisés deviendront invalides et un nouveau jeton d'activation sera nécessaire pour réactiver l'Application.

---

### 6. Conformité Professionnelle et Protection des Données
Mes Honoraires fonctionne uniquement comme un outil de suivi administratif pour les praticiens indépendants. Il relève de la seule responsabilité de l'utilisateur (praticien) de s'assurer que le stockage et la gestion des informations sur les clients et les honoraires sont conformes aux lois locales sur la comptabilité commerciale, la confidentialité et la protection des données applicables dans sa juridiction.

---

### 7. Protection de la Vie Privée des Enfants
L'Application est strictement destinée à un usage professionnel par des praticiens et exploitants adultes. Nous ne collectons pas sciemment d'informations personnelles auprès d'enfants de moins de 13 ans.

---

### 8. Modifications de la Présente Politique de Confidentialité
Nous pouvons mettre à jour notre Politique de Confidentialité de temps à autre. Toute modification sera publiée sur cette page avec une date de « Dernière mise à jour » révisée.

---

### 9. Nous Contacter
Si vous avez des questions ou des préocupations concernant cette Politique de Confidentialité, veuillez nous contacter à :
* **E-mail :** patienttracker.support@gmail.com
