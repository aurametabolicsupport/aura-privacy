[Українська](#uk) · [English](#en)

<a id="uk"></a>

# Політика конфіденційності — AURA Metabolic: Food & GI

Діє з: 20.10.2026 · Остання редакція: 18.11.2026  
Розробник: Sergey D · Контакт: aurametabolic@gmail.com

## 1. Коротко

У застосунку немає акаунтів. Щоденник, профіль, вимірювання глюкози й налаштування зберігаються лише на вашому пристрої. На сервер надсилається тільки те, що потрібно для роботи ШІ-функцій (фото чи текст страви, запити до асистента, параметри меню на тиждень). Ми не продаємо дані й не показуємо рекламу.

## 2. Що зберігається лише на вашому пристрої

Щоденник харчування, збережені страви й власні продукти, нотатки, вимірювання глюкози, «Мої реакції на їжу», дані таймера голодування, профіль і денні норми, налаштування застосунку. Ми не маємо до них доступу.

## 3. Що надсилається на наш сервер і до ШІ

- **Фото їжі** (сканер) — для аналізу ШІ. Фото не зберігаються: вони існують лише на час запиту.
- **Текст опису їжі** (текстове введення).
- **Запити до ШІ-асистента.** За вашим вибором разом із запитом надсилається короткий контекст: сумарні калорії, БЖВ і середній ГІ за сьогодні, ваші цілі, назви кількох останніх страв. Дані про глюкозу в запитах не надсилаються. Контекст можна вимкнути в чаті.
- **Параметри меню на тиждень:** цільові калорії та вуглеводи, кількість днів і прийомів їжі, вибраний варіант низького ГІ, текст «чого уникати».
- **Анонімний ідентифікатор пристрою** (випадковий UUID) і лічильники використання — для денних і пробних лімітів та захисту від зловживань. У базі зберігається лише хеш ідентифікатора.

Обробка ШІ виконується через Google Gemini API (платний тариф: Google не використовує ці дані для навчання моделей). Сервер працює на Google Cloud Run (ЄС). Перед першим використанням ШІ застосунок просить вашу згоду.

## 4. Сторонні сервіси

- **Google Gemini API** — аналіз фото й тексту, відповіді асистента, меню.
- **Firebase Analytics і Crashlytics (Google)** — псевдонімна статистика (екрани, події, модель пристрою, версія ОС і застосунку) та звіти про збої, без вмісту щоденника.
- **RevenueCat** — перевірка підписки Premium. Отримує ідентифікатор транзакції; ім'я й email не отримує.
- **Google Play Billing / Apple App Store** — оплата. Платіжні дані ми не бачимо.
- **Open Food Facts** — пошук продукту за штрихкодом. Надсилається лише штрихкод.
- **Health Connect / Apple Health** — кроки, тренування, глюкоза читаються лише після вашого дозволу, залишаються на пристрої й не надсилаються на сервер. Доступ можна вимкнути в налаштуваннях.

## 5. Дозволи

Камера та вибір фото — для фото їжі; сповіщення — для нагадувань (наприклад, кінець вікна голодування); Health Connect — за згодою. Усі дозволи можна змінити в налаштуваннях системи.

## 6. Як видалити свої дані

1. **Дані на пристрої:** у застосунку відкрийте Налаштування → «Видалити всі мої дані» (видаляє щоденник, налаштування, кеш і сесію покупок). Або видаліть застосунок / очистіть його дані.
2. **Дані на сервері:** напишіть на aurametabolic@gmail.com з теми «Delete my data» і вкажіть, що ви користувач AURA Metabolic. Ми видалимо пов'язані з вашим анонімним ідентифікатором записи лімітів протягом 30 днів. Для точного пошуку запису можуть знадобитися дані зі скриншота налаштувань, які ми вкажемо у відповіді.
3. **Підписка:** скасовується в Google Play / App Store; видалення даних підписку не скасовує.

## 7. Строки зберігання

- Фото: лише на час аналізу.
- Журнали сервера (IP, час запиту): до 30 днів.
- Денні лічильники лімітів: автоматично видаляються через короткий час після завершення дня.
- Лічильник пробного використання (меню на тиждень) і хеш ідентифікатора: до отримання запиту на видалення.
- Щоденник і налаштування: на пристрої, доки ви їх не видалите.
- Аналітика Firebase: за стандартними строками Google Firebase.

## 8. Безпека

Передача даних — HTTPS/TLS. Доступ до серверної інфраструктури обмежений.

## 9. Ваші права

Залежно від країни (GDPR, CCPA/CPRA тощо) ви можете запросити доступ, виправлення, видалення чи перенесення даних — напишіть на aurametabolic@gmail.com, відповімо протягом 30 днів. Ми не продаємо персональні дані.

## 10. Діти

Застосунок не призначений для дітей до 13 років, ми свідомо не збираємо їхні дані.

## 11. Медичне застереження

AURA Metabolic — інструмент для добробуту, а не медичний виріб. Він не ставить діагнозів, не замінює лікаря. Оцінки поживності й ГІ приблизні — не використовуйте їх для розрахунку доз інсуліну. З питань терапії консультуйтеся з лікарем.

## 12. Зміни

У разі змін ми оновимо дату «Остання редакція» на цій сторінці.

---

<a id="en"></a>

# Privacy Policy — AURA Metabolic: Food & GI

Effective: 20 Oct 2026 · Last updated: 18 Nov 2026  
Developer: Sergey D · Contact: aurametabolic@gmail.com

## 1. Summary

The app has no accounts. Your diary, profile, glucose readings and settings are stored only on your device. Only what the AI features need is sent to our server (a food photo or text, assistant questions, meal-plan settings). We do not sell data and show no ads.

## 2. Stored only on your device

Food diary, saved dishes and custom products, notes, glucose readings, "My reactions to food", fasting timer data, profile and daily targets, app settings. We have no access to them.

## 3. Sent to our server and AI

- **Food photos** (scanner) for AI analysis. Photos are not stored: they exist only for the duration of the request.
- **Food description text** (text input).
- **AI assistant questions.** If you choose, a short context is sent with them: today's total calories, macros and average GI, your targets, and the names of a few recent dishes. Glucose data is not sent. You can turn context off in the chat.
- **Weekly meal plan settings:** calorie and carb targets, number of days and meals, low-GI option, and the "avoid" text.
- **Anonymous device ID** (random UUID) and usage counters, for daily and trial limits and abuse prevention. Only a hash of the ID is stored in the database.

AI processing uses the Google Gemini API (paid tier: Google does not use this content to train its models). The server runs on Google Cloud Run (EU). The app asks for your consent before the first AI use.

## 4. Third-party services

- **Google Gemini API** — photo and text analysis, assistant answers, meal plans.
- **Firebase Analytics and Crashlytics (Google)** — pseudonymous statistics (screens, events, device model, OS and app version) and crash reports, without diary content.
- **RevenueCat** — verifies the Premium subscription. It receives a transaction ID, not your name or email.
- **Google Play Billing / Apple App Store** — payments. We never see payment details.
- **Open Food Facts** — barcode lookup. Only the barcode is sent.
- **Health Connect / Apple Health** — steps, workouts and glucose are read only with your permission, stay on the device and are not sent to our server. You can disable access in settings.

## 5. Permissions

Camera and photo picking (food photos); notifications (reminders such as the end of a fasting window); Health Connect (with your consent). You can change them in system settings.

## 6. How to delete your data

1. **On-device data:** in the app go to Settings → "Delete all my data" (removes diary, settings, cache and purchase session). Or uninstall the app / clear its data.
2. **Server-side data:** email aurametabolic@gmail.com with the subject "Delete my data" and say you use AURA Metabolic. We will delete the limit records linked to your anonymous ID within 30 days. We will tell you in our reply what, if anything, we need from you to locate the record.
3. **Subscription:** cancel it in Google Play / App Store; deleting data does not cancel it.

## 7. Retention

- Photos: only for the duration of the analysis.
- Server logs (IP, request time): up to 30 days.
- Daily limit counters: removed automatically shortly after the day ends.
- Trial-use counter (weekly meal plan) and ID hash: until a deletion request is received.
- Diary and settings: on your device until you delete them.
- Firebase analytics: per Google Firebase's standard retention.

## 8. Security

Data in transit uses HTTPS/TLS. Access to server infrastructure is restricted.

## 9. Your rights

Depending on your country (GDPR, CCPA/CPRA etc.) you may request access, correction, deletion or portability of your data: email aurametabolic@gmail.com, we reply within 30 days. We do not sell personal information.

## 10. Children

The app is not intended for children under 13 and we knowingly do not collect their data.

## 11. Medical disclaimer

AURA Metabolic is a wellness tool, not a medical device. It does not diagnose and does not replace a doctor. Nutrition and GI estimates are approximate: do not use them to calculate insulin doses. Consult a healthcare professional about your therapy.

## 12. Changes

If anything changes we will update the "Last updated" date on this page.
