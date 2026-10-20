Privacy Policy — AURA Metabolic
Effective date: 20.10.2026 
Developer: Sergey D 
Contact: aurametabolic@gmail.com

This Privacy Policy explains how AURA Metabolic ("the App", "we", "us") handles your information. We designed the App to collect as little data as possible: your food diary is stored only on your device, and we never see it.

1. Overview
Data	Where it goes	Stored by us?
Food photos (when you scan a meal)	Our server → Google Gemini API	No — processed transiently, not saved
Barcode scans (product data)	Open Food Facts API	No — fetched directly to your device
Food diary entries (meals, nutrients)	Nowhere — local only	No
App settings (language, theme, profile norms)	Local only	No
Anonymous device identifier (random UUID)	Our server	Only for abuse prevention
Usage analytics (events)	Firebase Analytics (Google)	Yes, aggregated
Crash reports	Firebase Crashlytics (Google)	Yes
Purchase status (if you subscribe)	Google Play Billing → RevenueCat	Yes (entitlement only)

2. Food photo analysis
When you scan a meal, the photo is uploaded over an encrypted connection to our API hosted on Google Cloud Run in the European Union, and forwarded to the Google Gemini API for analysis.

We do not store photos on our servers. They exist only for the duration of the analysis request.
Photos are processed by Google in accordance with the Google Privacy Policy. We use the Gemini API paid tier, under which Google does not use your content to train its models.
Analysis results are returned to the App and stored only on your device.
Our hosting provider automatically records request metadata (IP address, timestamp) in server logs for security and abuse prevention; these logs are retained for a limited period (up to 30 days).
Please photograph only the food. Avoid including people, documents, or other personal information in your photos.

3. Barcode scanning and Open Food Facts
When you use the barcode scanning feature, the App requests product information directly from the open database Open Food Facts (https://world.openfoodfacts.org). 
Product data from Open Food Facts is made available under the Open Database License (ODbL).
During this process, no personal user data (such as name, email, or location) is transmitted to Open Food Facts. The product data (name, ingredients, macronutrients) is used solely to display nutritional information in your food diary and is not stored on our servers.

4. Data stored only on your device
Your food diary, saved meals, notes, profile settings and daily norms never leave your device. We have no access to them. If you delete the App (or clear its data), this information is permanently deleted and cannot be recovered. Please use your device backup (e.g. Google account backup) if you wish to keep it.

5. Analytics and crash reports
We use Firebase Analytics and Firebase Crashlytics (Google LLC) to understand how the App is used and to fix crashes:
Events such as screen views, scan attempts and successful analyses;
App instance identifiers, device model, OS version, app version;
Crash stack traces.

These data are pseudonymous and are not linked to your identity — we do not know who you are. You can read Google's privacy practices at https://policies.google.com/technologies/partner-sites.

6. Subscriptions
If you purchase a subscription, the payment is processed by Google Play Billing (and, for iOS, Apple App Store). We never receive your payment card details. Our subscription partner RevenueCat receives transaction identifiers to verify your entitlement (whether you have an active subscription). We do not receive your name or email from the store.

7. What we do NOT do
We do not require an account, name, email or phone number.
We do not collect your medical records, glucose readings, or medication data.
We do not sell or rent your data to anyone.
We do not use your data for third-party advertising.
The App is not directed to anyone under 18, and we do not knowingly collect data from children.

8. Legal bases (EEA/UK users)
We process: (a) food photos — to perform the service you request (contract); (b) analytics and crash data, anonymous device identifier — based on our legitimate interest to maintain and improve the App; (c) nothing requiring consent is shared with third parties for their own purposes.
International transfers to Google services are covered by Google's standard contractual clauses (Google Cloud Data Processing Terms).

9. Your rights
Depending on your jurisdiction (e.g. GDPR, CCPA/CPRA), you may have rights to access, correct, delete, or port your personal data. Since we hold almost no identifiable data, most requests concern analytics data, which you can reset by reinstalling the App or deleting your advertising ID in device settings. To exercise any right or ask a question, email aurametabolic@gmail.com. We respond within 30 days. We do not sell personal information (CCPA/CPRA "sale" and "sharing") and have not done so in the last 12 months.

10. Security
Data in transit is encrypted (HTTPS/TLS). Diary data never leaves your device. Access to our server infrastructure is restricted.

11. Changes to this policy
We may update this policy as the App evolves. We will post the new version here with a new effective date. Material changes will be announced in the App.

12. Contact
Sergey D — aurametabolic@gmail.com
