# Privacy Policy for Mes Honoraires

**Last updated:** October 22, 2026

**Inova Labs** operates the **Mes Honoraires** mobile application (the "App"). This Privacy Policy informs you of our policies regarding the collection, use, and disclosure of personal and device information when you use our App.

---

### 1. Local-First Architecture & Data Sovereignty
Mes Honoraires is designed as a local-first application. **We do not operate, own, or maintain any independent backend databases or cloud servers to store your bénéficiaire or honoraires records.** All bénéficiaire names, intervention logs, payment statuses, and notes entered into the App are stored **strictly and exclusively on your local device memory**.

---

### 2. Information We Process and Collect

* **Bénéficiaire & Payment Records (User-Controlled):** All honoraires data you input stays locally on your phone.

* **Google Drive Backups (via Apps Script Web App):** If you choose to back up your database, the App transmits your backup data securely to your personal Google Drive via a custom Google Apps Script Web App deployed under your control. No third-party servers handle or store this backup payload; it goes directly from your app to your personal Google Drive storage.

* **App Performance & Analytics (Firebase):** We integrate **Firebase Analytics**, **Firebase Crashlytics**, and **Firebase Remote Config** (services provided by Google LLC) to collect non-identifiable technical data:
  * **Analytics:** Usage metrics, app navigation patterns, and feature interaction frequencies to help us improve the app experience.
  * **Crashlytics:** Automated crash reports, stack traces, and device state information at the time of a crash to help us diagnose and fix bugs.
  * **Remote Config:** Used to check for app updates, feature flags, or maintenance announcements.

* **Offline-First Architecture & Network Connectivity:** The app operates fully offline for day-to-day bénéficiaire record management and établissement tracking, connecting to the network only when the user executes a Google Apps Script backup or when Firebase processes background analytics/crash logs.

* **Local Biometric Data:** If you enable biometric security (fingerprint/face unlock), authentication is handled entirely by your device’s operating system security module. The App never accesses, records, or stores raw biometric measurements.

---

### 3. How We Use Your Information
* **Local Operations:** To display, search, organize, and calculate bénéficiaire payment balances and generate your bilan des honoraires locally on your device.

* **App Stability & Improvement:** Crashlytics data is used strictly to identify bugs, stability issues, and performance bottlenecks. Analytics data helps us understand how features are used so we can improve usability.

* **Maintenance & Updates:** Remote Config is used to manage app-level configurations and notify you of mandatory or optional updates.

---

### 4. Third-Party Services
Our App integrates the following trusted third-party services:
* **Firebase (Google LLC):** For analytics, crash reporting, and remote configuration management. Google's privacy policies govern data processed through Firebase.
* **Google Apps Script & Google Drive:** Used solely to facilitate your user-initiated database backups to your personal Google Drive account.

---

### 5. Data Retention, Control, and Deletion
* **Activation & License Tokens:** Access to the App requires a valid activation token. You are responsible for safeguarding your activation credentials.

* **In-App Deletion:** You can delete individual bénéficiaire records, delete an entire établissement—which will automatically remove all bénéficiaire records associated with that établissement—at any time from within the App, or reset your local database.

* **App Uninstallation & Token Invalidation:** Uninstalling the App or clearing app data via your mobile settings will permanently remove all local app databases from your device (unless backed up via your Google Apps Script routine). Additionally, uninstalling or clearing app data revokes the local activation state; previously used tokens will become invalid, and a new activation token will be required to reactivate the App.

---

### 6. Professional & Data Privacy Compliance
Mes Honoraires functions purely as an administrative tracking tool for independent practitioners. It is the sole responsibility of the user (praticien) to ensure that storing and handling client and fee information complies with local business accounting, confidentiality, and data protection laws applicable in their jurisdiction.

---

### 7. Children’s Privacy
The App is intended strictly for professional use by adult practitioners and business operators. We do not knowingly collect personal information from children under 13.

---

### 8. Changes to This Privacy Policy
We may update this Privacy Policy from time to time. Any changes will be posted on this page with a revised "Last updated" date.

---

### 9. Contact Us
If you have questions or concerns regarding this Privacy Policy, please contact us at:
* **Email:** patienttracker.support@gmail.com
