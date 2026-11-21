---
title: "Goals — Політика конфіденційності / Privacy Policy"
---

# Goals — Політика конфіденційності / Privacy Policy

Дата набрання чинності / Effective date: 2026-11-21
Розробник / Developer: Serhii Stetsiuk
Контакт / Contact: stetsyuk9114@gmail.com

## Українською

**Goals зберігає дані профілю на пристрої. Ви можете експортувати копії та вибрати місце їх зберігання.**

1. **Які дані обробляє застосунок.** Цілі, бюджети, активи, надходження доходу, налаштування податків, логін акаунта (пошта або телефон) і PIN. Ці дані вводите ви, і вони зберігаються лише на пристрої: цілі й дохід — у локальній базі даних, акаунти й хеші PIN — у захищеному сховищі системи (iOS Keychain / Android Keystore). PIN у відкритому вигляді не зберігається.
2. **Face ID / біометрія.** Перевірку виконує операційна система; застосунок не отримує й не зберігає біометричні дані.
3. **Мережа.** Без увімкненої хмари застосунок робить лише два види запитів: до офіційного API Національного банку України (bank.gov.ua) — курс USD/EUR на вибрану дату, і раз на день — до stetsyuk9114-ux.github.io, щоб завантажити підписаний файл податкових параметрів року (МЗП, ліміти, ставки). Під час запитів жодні ваші дані не передаються; сервери, як будь-який вебсервер, бачать IP-адресу пристрою.
4. **Резервні копії.** Автобекап і експорт записують файл у теку, яку ви самі вибрали (наприклад, iCloud Drive або Google Drive). Ці файли не шифруються; їх зберігання регулюють умови вибраного вами сервісу. Розробник до них доступу не має.
5. **Аналітика, реклама, трекінг.** Немає. Застосунок не використовує сторонні SDK аналітики чи реклами і не відстежує вас між застосунками.
6. **Видалення даних.** У меню акаунта виберіть «Видалити акаунт» і підтвердьте PIN. Це видалить локальний акаунт та пов’язані з ним дані. Експортовані файли й копії видаляються окремо у вибраному місці зберігання.
7. **Діти.** Застосунок не призначений спеціально для дітей і свідомо не збирає їхніх даних.
8. **Зміни.** Про зміни цієї політики буде повідомлено оновленням цієї сторінки.
9. **Хмара і бухгалтер (необов'язково).** Якщо ви вмикаєте «Хмару» для акаунта, усі дані цього акаунта (цілі, активи, доходи, податкові налаштування й декларації) синхронізуються з Google Firebase (Cloud Firestore, регіон europe-central2, Варшава). Вхід — одноразовим кодом на вашу пошту. Дані шифруються Google на диску й під час передачі; наскрізного шифрування немає, тож адміністратор проєкту Firebase технічно має доступ до хмарних даних. Якщо ви запрошуєте бухгалтера, він бачить або змінює лише розділи, до яких ви дали доступ, і лише після вашого підтвердження; доступ можна змінити чи закрити будь-коли. Вимкнення хмари або видалення акаунта видаляє ваші дані та доступи з сервера; дані на телефоні залишаються (крім видалення акаунта). Листи з кодом і запрошенням надсилаються з адреси розробника.

## English

**Goals stores profile data on your device. You can export backups and choose where they are stored.**

1. **Data the app handles.** Goals, budgets, assets, income entries, tax settings, account login (email or phone) and PIN. You enter this data and it is stored only on your device: goals and income in a local database, accounts and PIN hashes in the system secure storage (iOS Keychain / Android Keystore). The PIN itself is never stored.
2. **Face ID / biometrics.** Verification is done by the operating system; the app never receives or stores biometric data.
3. **Network.** Without Cloud, the app makes only two kinds of requests: to the official National Bank of Ukraine API (bank.gov.ua) for USD/EUR rates on the selected date, and once a day to stetsyuk9114-ux.github.io to download a signed file of yearly tax parameters (minimum wage, limits, rates). No personal data is sent; like any web server, these servers see the device IP address.
4. **Backups.** Auto backup and export write a file to a folder you choose (for example iCloud Drive or Google Drive). These files are not encrypted and are governed by the terms of the service you chose. The developer has no access to them.
5. **Analytics, ads, tracking.** None. The app uses no third-party analytics or advertising SDKs and does not track you across apps.
6. **Deleting data.** Choose Delete account in the account menu and confirm with your PIN. This removes the local account and its associated data. Delete exported files and backups separately from the places where you saved them.
7. **Children.** The app is not directed at children and does not knowingly collect their data.
8. **Changes.** Changes to this policy will be published on this page.
9. **Cloud and accountant (optional).** If you turn on Cloud for an account, all its data (goals, assets, income, tax settings and declarations) is synced with Google Firebase (Cloud Firestore, europe-central2, Warsaw). Sign-in uses a one-time code sent to your email. Google encrypts the data at rest and in transit; there is no end-to-end encryption, so the Firebase project administrator technically has access to cloud data. If you invite an accountant, they can view or edit only the sections you allow, and only after you approve them; you can change or revoke access at any time. Turning Cloud off or deleting the account deletes your data and grants from the server; data on the phone stays (except when the account is deleted). Code and invitation emails are sent from the developer's address.
