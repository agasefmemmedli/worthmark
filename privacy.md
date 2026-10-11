---
title: Worthmark — Privacy Policy / Политика конфиденциальности
permalink: /privacy/
---

# Worthmark — политика конфиденциальности / Privacy Policy

[English version below](#english)

## Русский

**Политика конфиденциальности Worthmark**
Последнее обновление: 11 октября 2026. Разработчик: Agasef Memmedli. Связь: agasef.memmedli@gmail.com.

Worthmark — приложение для учёта личного капитала: активы, кредиты, страховки, долги людям и вам.
У приложения нет своего сервера и нет своей учётной записи. Мы не продаём данные и не показываем
рекламу.

**1. Данные хранятся на вашем телефоне.** Всё, что вы вводите (активы, кредиты, платежи,
страховки, долги и имена людей в них, заметки, история, настройки), хранится в памяти приложения на
устройстве. Копии этих данных покидают телефон только так, как описано в разделе 3 (копия в Google
Drive, автокопия Android, файл копии). Разработчик этих данных не получает.

**2. Блокировка.** По желанию можно включить PIN-код и вход по отпечатку или лицу (биометрия
Android класса «сильная», BIOMETRIC_STRONG). PIN хранится только в виде хэша (PBKDF2); биометрию
обрабатывает Android, приложение её не получает. «Забыли PIN?» — вход блокировкой экрана телефона
и новый PIN; если на телефоне нет блокировки экрана, остаётся только «Сбросить приложение» (раздел 5).
Пока блокировка включена, экран приложения скрыт в списке недавних приложений и не попадает на
снимки экрана.

**3. Что уходит с телефона и куда.**

- **Курсы валют.** Чтобы пересчитать суммы, приложение запрашивает курс у Центрального банка
  Азербайджана (www.cbar.az) или у сервиса Frankfurter (api.frankfurter.dev). В запросе — код валюты
  и дата записи, на которую нужен курс; эти сервисы также видят IP-адрес устройства. Сумм, названий
  и имён в запросе нет.
- **Отчёты об ошибках и статистика использования (только с вашего согласия).** При первом запуске
  приложение спрашивает, отправлять ли отчёты об ошибках и статистику (переключатель на первом
  экране); пока вы не выбрали, ничего не отправляется. Выбор можно изменить в «Настройки ›
  Безопасность и данные». Ответ хранится только на этом телефоне и не попадает в копии (на новом
  телефоне приложение спросит снова). Если отправка включена, приложение отправляет в Google Firebase Crashlytics и Google Analytics for Firebase:
  - сведения о сбоях: технический отчёт об ошибке (стек вызовов; в нём может быть текст сообщения
    об ошибке), модель устройства, версии Android и приложения, свободная память и место на диске,
    время;
  - статистику использования: какие экраны открываются и какими функциями пользуются (например,
    «добавлен кредит, вид — ипотека»), автоматические события Analytics (например, первый запуск,
    начало сеанса, время в приложении, удаление приложения, покупка в приложении — с товаром, ценой
    и валютой) и
    параметры устройства (модель, версия ОС, язык, страна);
  - идентификатор установки Firebase. Это псевдоним: по нему не узнать, кто вы, но события одной
    установки связаны между собой.

  По IP-адресу Google определяет приблизительное местоположение (страну, а при соответствующих
  настройках Firebase — регион или город). Суммы,
  курсы и валюты ваших записей, названия, имена, даты записей, PIN и содержимое копий приложение в эти сервисы не передаёт.
  Рекламный идентификатор не используется, данные не используются для рекламы. Выключение
  переключателя сразу прекращает отправку и удаляет ещё не отправленные отчёты. Хранение: данные
  Analytics на уровне пользователя и событий Google хранит не дольше срока, заданного в настройках
  проекта (не более 14 месяцев); отправленные отчёты о сбоях Crashlytics хранит ограниченный срок по
  правилам Firebase.
  Данные обрабатывает Google LLC: https://firebase.google.com/support/privacy.
- **Резервная копия в Google Drive (по желанию).** Если вы входите через Google, приложение сохраняет
  копию ваших данных (всё из раздела 1, включая настройки и хэш PIN) в скрытой папке приложения в
  вашем собственном Google Drive и восстанавливает её после входа на другом телефоне. Копия передаётся
  по зашифрованному соединению напрямую в ваш Google Drive; у разработчика нет к ней доступа.
  Приложение видит только свою скрытую папку, а не ваши файлы. Копия не защищена отдельным паролем:
  её может прочитать тот, у кого есть доступ к вашему аккаунту Google, — включите двухэтапную
  проверку. Адрес аккаунта Google хранится только на телефоне.
- **Автокопия Android.** Если на телефоне включено резервное копирование, Android сам сохраняет
  копию данных приложения (включая настройки и хэш PIN) в вашем аккаунте Google — только
  зашифрованную, поэтому нужна блокировка экрана — и переносит данные при переносе «телефон →
  телефон» (для переноса блокировка экрана не нужна). На Android 8.x автокопия выключена. Это делает
  система, а не приложение; выключить — в настройках Android.
- **Файл копии.** По вашей команде приложение сохраняет копию в файл, зашифрованный вашим паролем
  (AES-256), туда, куда вы выберете.
- **Покупка Premium.** Оплату проводит Google Play. Приложение получает от Google Play только
  сведения о том, куплен ли Premium; платёжные данные приложению не передаются.
- **Обновления.** При запуске и при возврате в приложение оно спрашивает у Google Play, есть ли
  новая версия и насколько важно обновление; без сети или без Google Play проверка не выполняется.

Данные, которые обрабатывает Google (Firebase, Drive, Play), подчиняются политике
конфиденциальности Google: https://policies.google.com/privacy. Google LLC находится в США, поэтому
эти данные могут передаваться и обрабатываться в США и других странах.

**4. Разрешения.**
- Интернет и состояние сети — для перечисленного в разделе 3.
- Уведомления — для напоминаний о платежах; напоминания создаются на телефоне.
- Биометрия (отпечаток/лицо) — для входа при включённой блокировке.
- Оплата через Google Play (BILLING) — для покупки Premium.
- Запуск после перезагрузки, фоновая работа, удержание процессора (WorkManager) — чтобы
  напоминания и фоновая копия в Drive срабатывали вовремя.
- Play Install Referrer — его добавляет Firebase Analytics, чтобы узнать, откуда установлено
  приложение (только при включённом переключателе).

**5. Как удалить данные.**
- Отдельную запись — отправить в архив, затем в «Архиве» — «Удалить навсегда».
- Все данные на телефоне — удалить приложение или очистить его данные в настройках Android; с
  экрана PIN («Забыли PIN?») — «Сбросить приложение».
- Копию в Google Drive: сначала «Настройки › Резервная копия › Выйти», затем удалить копию в
  настройках Google Drive (Управление приложениями › Worthmark › Удалить скрытые данные). Пока вы
  вошли, «Удалить копию из Drive» удаляет копию, но после следующего изменения сохраняется новая.
  «Выйти» отзывает доступ приложения к Drive, если есть сеть; если отозвать не удалось, войдите и
  выйдите снова или удалите доступ в аккаунте Google (Безопасность › Сторонние приложения и сервисы).
- Отчёты и статистику — выключить переключатель (неотправленное удаляется; отправленное Google
  удаляет по истечении срока хранения из раздела 3).
- Файлы копий вы удаляете сами.

**6. Основания и ваши права.** Отчёты и статистика отправляются только с вашего согласия — его вы
даёте переключателем на первом экране и можете отозвать в любой момент в «Настройки › Безопасность и
данные»: отправка сразу прекращается, неотправленные отчёты удаляются.
Копия в Google Drive — по вашему выбору (вход через Google). Вы можете запросить доступ к данным
или их удаление, возразить против обработки (выключив переключатель или написав на agasef.memmedli@gmail.com) и
подать жалобу в надзорный орган по защите данных вашей страны. Учтите: у разработчика нет данных,
по которым можно найти вас, — ваши записи хранятся у вас, а копия — в вашем Google Drive.

**7. Дети.** Приложение предназначено для взрослых и не рассчитано на детей.

**8. Изменения.** Новая версия политики публикуется по этой же ссылке с новой датой.

**9. Связь.** Вопросы и запросы — agasef.memmedli@gmail.com.

---

## English

**Worthmark Privacy Policy**
Last updated: October 11, 2026. Developer: Agasef Memmedli. Contact: agasef.memmedli@gmail.com.

Worthmark is a personal net worth app: assets, loans, insurance, and money lent and borrowed. The
app has no server of its own and no account of its own. We do not sell data and show no ads.

**1. Your data is stored on your phone.** Everything you enter (assets, loans, payments,
insurance, debts and the names of people in them, notes, history, settings) is stored in the app's
storage on the device. Copies leave the phone only as described in section 3 (Google Drive backup,
Android backup, backup file). The developer does not receive this data.

**2. Lock.** You can turn on a PIN and fingerprint or face unlock (Android strong biometrics,
BIOMETRIC_STRONG). The PIN is stored only as a hash (PBKDF2); biometrics are handled by Android and
never reach the app. "Forgot PIN?" lets you in with the phone's screen lock and set a new PIN; if
the phone has no screen lock, the only way left is "Reset the app" (section 5). While the lock is
on, the app's screen is hidden in recent apps and cannot be captured in screenshots.

**3. What leaves the phone, and where it goes.**

- **Exchange rates.** To convert amounts, the app asks the Central Bank of Azerbaijan
  (www.cbar.az) or the Frankfurter service (api.frankfurter.dev) for a rate. The request contains a
  currency code and the record date the rate is needed for; these services also see the device's IP
  address. No amounts, titles or names are in the request.
- **Crash reports and usage statistics (only with your consent).** On first launch the app asks
  whether to send crash reports and statistics (a switch on the welcome screen); nothing is sent
  until you choose. You can change the choice later in Settings › Security and data. Your answer is
  stored only on this phone and is not included in backups (on a new phone the app asks again). If sending is
  on, the app sends to Google Firebase
  Crashlytics and Google Analytics for Firebase:
  - crash information: a technical error report (stack trace; it may include the text of the error
    message), device model, Android and app versions, free memory and disk space, time;
  - usage statistics: which screens are opened and which features are used (for example, "loan
    added, type — mortgage"), automatic Analytics events (for example, first open, session start,
    engagement time, app removal, in-app purchase — with product, price and currency) and device parameters (model, OS version,
    language, country);
  - a Firebase installation ID. It is a pseudonym: it does not tell who you are, but links the
    events of one installation together.

  Google derives an approximate location from the IP address (the country and, depending on Firebase
  settings, the region or city).
  The app does not pass the amounts, rates and currencies of your records, titles, names, record dates, the PIN or backup contents to
  these services. No advertising ID is used; the data is not used for advertising. Turning the switch
  off stops sending at once and deletes reports not yet sent. Retention: Analytics user- and
  event-level data is kept no longer than the period set in the project settings (at most 14 months);
  Crashlytics keeps sent crash reports for a limited time under Firebase rules. The data is processed by Google LLC:
  https://firebase.google.com/support/privacy.
- **Google Drive backup (optional).** If you sign in with Google, the app saves a copy of your data
  (everything in section 1, including settings and the PIN hash) in the app's hidden folder in your
  own Google Drive and restores it when you sign in on another phone. The copy goes over an
  encrypted connection straight to your Google Drive; the developer has no access to it. The app can
  see only its own hidden folder, not your files. The copy is not protected by a separate password:
  anyone with access to your Google account can read it — turn on 2-Step Verification. Your Google
  account address is kept only on the phone.
- **Android backup.** If backup is on, Android itself saves a copy of the app's data (including
  settings and the PIN hash) to your Google account — only encrypted, so a screen lock is needed —
  and moves the data in a phone-to-phone transfer (no screen lock needed for the transfer). On
  Android 8.x this backup is off. This is done by the system, not the app; you can turn it off in
  Android settings.
- **Backup file.** When you ask, the app saves a copy to a file encrypted with your password
  (AES-256), in a place you choose.
- **Premium purchase.** Payment is handled by Google Play. The app receives from Google Play only
  whether Premium has been bought; payment details are not shared with the app.
- **Updates.** On start and when you return to the app, it asks Google Play whether a new version is
  available and how important the update is; without a network or Google Play no check is made.

Data processed by Google (Firebase, Drive, Play) is subject to Google's Privacy Policy:
https://policies.google.com/privacy. Google LLC is based in the USA, so this data may be transferred
to and processed in the USA and other countries.

**4. Permissions.**
- Internet and network state — for what is listed in section 3.
- Notifications — for payment reminders; reminders are created on the phone.
- Biometrics (fingerprint/face) — to unlock when the lock is on.
- Google Play billing (BILLING) — to buy Premium.
- Run at startup, background work, keep awake (WorkManager) — so reminders and the background Drive
  backup run on time.
- Play Install Referrer — added by Firebase Analytics to learn where the app was installed from
  (only while the switch is on).

**5. Deleting your data.**
- A single record — archive it, then in the Archive choose "Delete forever".
- All data on the phone — uninstall the app or clear its storage in Android settings; from the PIN
  screen ("Forgot PIN?") — "Reset the app".
- The Google Drive copy: first Settings › Backup › Sign out, then delete the copy in Google Drive
  settings (Manage apps › Worthmark › Delete hidden app data). While you are signed in, "Delete the
  copy from Drive" deletes it, but a new copy is saved after the next change. "Sign out" revokes the
  app's access to Drive when online; if that fails, sign in and out again or remove access in your
  Google Account (Security › Third-party apps & services).
- Reports and statistics — turn the switch off (unsent data is deleted; Google deletes sent data
  after the retention period in section 3).
- Backup files are yours to delete.

**6. Legal basis and your rights.** Reports and statistics are sent only with your consent — you give it
with the switch on the welcome screen and can withdraw it at any time in Settings › Security and
data: sending stops at once and unsent reports are deleted. The Google Drive
copy is your choice (signing in with Google). You can request access to or deletion of data, object
to processing (by turning the switch off or writing to agasef.memmedli@gmail.com) and complain to the data protection
authority of your country. Note: the developer holds no data that identifies you — your records are
kept by you, and the copy is in your Google Drive.

**7. Children.** The app is meant for adults and is not directed at children.

**8. Changes.** A new version of this policy is published at the same link with a new date.

**9. Contact.** Questions and requests — agasef.memmedli@gmail.com.
