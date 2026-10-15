Privacy Policy — AURA Metabolic
Effective date: 15.10.2026 Developer: Sergey D Contact: aurametabolicsupport@gmail.com


This Privacy Policy explains how AURA Metabolic ("the App", "we", "us") handlesyour information. We designed the App to collect as little data as possible:your food diary is stored only on your device, and we never see it.

1. Overview
Data	Where it goes	Stored by us?
Food photos (when you scan a meal)	Our server → Google Gemini API	No — processed transiently, not saved
Food diary entries (meals, nutrients)	Nowhere — local only	No
App settings (language, theme, profile norms)	Local only	No
Anonymous device identifier (random UUID)	Our server	Only for abuse prevention
Usage analytics (events)	Firebase Analytics (Google)	Yes, aggregated
Crash reports	Firebase Crashlytics (Google)	Yes
Purchase status (if you subscribe)	Google Play Billing → RevenueCat	Yes (entitlement only)
2. Food photo analysis
When you scan a meal, the photo is uploaded over an encrypted connection to ourAPI hosted on Google Cloud Run in the European Union, and forwarded to theGoogle Gemini API for analysis.

We do not store photos on our servers. They exist only for the durationof the analysis request.
Photos are processed by Google in accordance with theGoogle Privacy Policy. We use theGemini API paid tier, under which Google does not use your content to trainits models.
Analysis results are returned to the App and stored only on your device.
Our hosting provider automatically records request metadata (IP address,timestamp) in server logs for security and abuse prevention; these logs areretained for a limited period (up to 30 days).
Please photograph only the food. Avoid including people, documents, orother personal information in your photos.
3. Data stored only on your device
Your food diary, saved meals, notes, profile settings and daily norms neverleave your device. We have no access to them. If you delete the App (or clearits data), this information is permanently deleted and cannot be recovered.Please use your device backup (e.g. Google account backup) if you wish to keep it.

4. Analytics and crash reports
We use Firebase Analytics and Firebase Crashlytics (Google LLC) tounderstand how the App is used and to fix crashes:

Events such as screen views, scan attempts and successful analyses;
App instance identifiers, device model, OS version, app version;
Crash stack traces.
These data are pseudonymous and are not linked to your identity — we do notknow who you are. You can read Google's privacy practices athttps://policies.google.com/technologies/partner-sites.

5. Subscriptions
If you purchase a subscription, the payment is processed by Google PlayBilling (and, for iOS, Apple App Store). We never receive your payment carddetails. Our subscription partner RevenueCat receives transactionidentifiers to verify your entitlement (whether you have an activesubscription). We do not receive your name or email from the store.

6. What we do NOT do
We do not require an account, name, email or phone number.
We do not collect your medical records, glucose readings, or medication data.
We do not sell or rent your data to anyone.
We do not use your data for third-party advertising.
The App is not directed to anyone under 18, and we do not knowingly collectdata from children.
7. Legal bases (EEA/UK users)
We process: (a) food photos — to perform the service you request (contract);(b) analytics and crash data, anonymous device identifier — based on ourlegitimate interest to maintain and improve the App; (c) nothing requiringconsent is shared with third parties for their own purposes.

International transfers to Google services are covered by Google's standardcontractual clauses (Google Cloud Data Processing Terms).

8. Your rights
Depending on your jurisdiction (e.g. GDPR, CCPA/CPRA), you may have rights toaccess, correct, delete, or port your personal data. Since we hold almost noidentifiable data, most requests concern analytics data, which you can resetby reinstalling the App or deleting your advertising ID in device settings.To exercise any right or ask a question, email aurametabolicsupport@gmail.com. We respondwithin 30 days. We do not sell personal information (CCPA/CPRA "sale" and"sharing") and have not done so in the last 12 months.

9. Security
Data in transit is encrypted (HTTPS/TLS). Diary data never leaves your device.Access to our server infrastructure is restricted.

10. Changes to this policy
We may update this policy as the App evolves. We will post the new versionhere with a new effective date. Material changes will be announced in the App.

11. Contact
Sergey D — aurametabolicsupport@gmail.com
