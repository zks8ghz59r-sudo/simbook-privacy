# SimBook Privacy Policy

This Privacy Policy explains how SimBook handles information when you use the app on iPhone or iPad. SimBook is a personal income and expense tracking app for iOS and iPadOS, designed to be local-first, privacy-conscious, and usable offline for core recordkeeping.

When this policy says the developer does not "collect" your local financial records, it means the developer does not receive those records on a developer-operated server. Your device still stores and processes the records locally so the app can work. System device backups and files you choose to export are described below.

## 1 Summary

- SimBook does not require an account, login, registration, or social sign-in.
- SimBook does not provide its own cloud synchronization, cloud backup service, or server-side transaction database.
- Your financial records and preferences are stored locally in the app's container on your device.
- Local storage uses the iOS and iPadOS app sandbox. SimBook does not provide a separate database password or independently keyed database encryption.
- Local app data may be included in iCloud Backup or computer backups, depending on your device settings. SimBook does not exclude its local database from system device backups.
- SimBook does not include advertising SDKs, behavioral analytics SDKs, third-party tracking SDKs, or third-party crash reporting SDKs.
- Network access is used for optional online exchange-rate lookup and App Store purchase, verification, and restoration services.
- Apple processes purchases and purchase restoration for the Analytics unlock through the App Store and StoreKit.
- Frankfurter Open API is contacted when you request online exchange-rate lookup.
- CSV export creates a user-controlled file outside the app's local database. SimBook does not encrypt exported CSV files.

## 2 Information Stored Locally on Your Device

SimBook stores the information you enter, import, generate, or configure locally on your device, including:

- Transactions.
- Categories.
- Recurring rules.
- Budgets.
- Exchange-rate cache.
- Preferences.

Financial records are stored in a local SwiftData database, and preferences are stored locally using system settings storage. CloudKit synchronization is disabled. The app relies on iOS and iPadOS storage protections; the security of your device and any backups also depends on your device configuration and how you protect access to them.

## 3 Information Sent Outside Your Device

SimBook does not upload your financial database to a developer-operated server. Information may leave your device in the limited situations below, including through system services or actions you choose.

### 3.1 App Store purchases and StoreKit

If you purchase or restore the Analytics feature, or when the app checks your purchase entitlement, Apple's App Store and StoreKit services process purchase-related information. This may include product identifiers, purchase status, transaction identifiers and dates, and Apple Account and payment information handled by Apple.

Neither SimBook nor the developer receives your full payment card details. The app processes StoreKit transaction information to verify access to Analytics and stores a local entitlement cache containing the product identifier, entitlement status, original transaction identifier, last verification time, and verification source. This does not give the developer access to your financial records entered in SimBook.

Apple handles its purchase and account information under its own [Privacy Policy](https://www.apple.com/legal/privacy/).

### 3.2 Online exchange-rate lookup

Manual exchange-rate entry works offline. If you use online rate lookup, SimBook sends a request to Frankfurter Open API with the source currency, target/base currency, and requested date or date range.

The request does not include your transaction amount, merchant, note, category list, budget details, recurring rules, CSV files, or full transaction history. Like any internet request, the provider may receive technical request information such as your IP address, request time, and network metadata. The provider's handling of this information is subject to its own policies.

### 3.3 CSV import and export

When you export data, SimBook creates a CSV file that you save using the iOS or iPadOS system file picker, including locations available through the Files app. Exported CSV files may include categories, transactions, recurring rules, budgets, notes, merchants, dates, amounts, currencies, exchange rates, timestamps, and local deletion or archive markers.

When you import data, SimBook reads the file you select. If you save, open, back up, or share a CSV file through another app or storage provider, including iCloud Drive, that third party may process the file according to its own policies. Choosing a cloud location for a CSV file does not enable cloud synchronization of SimBook's database.

### 3.4 Support communications

If you contact support, the developer may receive your contact details, message content, and any app version, device information, screenshots, logs, or example data you choose to provide. Do not send sensitive financial records to support unless necessary.

### 3.5 System device backups

iOS or iPadOS may include SimBook's local database and preferences in device backups, including iCloud Backup or backups to a computer, depending on your settings. These backups are separate from SimBook and are managed through Apple's system tools. See Apple's explanation of [iCloud Backup](https://support.apple.com/en-us/108770).

The developer does not receive or control these backup copies. Backup storage, protection, retention, restoration, and deletion depend on your settings and the relevant service or device.

## 4 How Information Is Used

SimBook processes your financial records on your device to provide recordkeeping, summaries, editing, recurring rule generation, budget comparison, currency conversion, CSV import/export, settings, local Analytics, and forecasts. These records are not sent to the developer unless you choose to provide them, such as in a support message. Purchase entitlement information is used to recognize and verify access to paid features.

Support information, if you provide it, is used to respond to your request, troubleshoot issues, improve documentation, maintain support records, comply with legal obligations, resolve disputes, and prevent misuse.

## 5 Sharing Sale and Targeted Advertising

SimBook does not sell personal data or share it for behavioral advertising, targeted advertising, cross-context behavioral advertising, or profiling for advertising.

Limited information may be processed by third parties for app functionality, system services, or your chosen actions:

| Third party | Purpose | Data involved |
|---|---|---|
| Apple App Store and StoreKit | Purchase, restoration, and entitlement verification for Analytics | Product identifiers, purchase status, transaction metadata, and Apple Account/payment information handled by Apple |
| Frankfurter Open API | Optional exchange-rate lookup | Currency pair, requested date/date range, and technical request metadata |
| Apple iCloud Backup or a computer you use for backups | System device backup and restoration, according to your settings | Local app data included in the device backup |
| File providers and other apps you choose | Saving, opening, copying, or sharing CSV files | The files you select and their contents |
| Email or support providers | Delivering and processing support communications | Contact details, messages, and attachments you choose to send |

The developer may also disclose information it holds if required by law, to respond to valid legal process, or to protect rights and safety, with legally appropriate notice where required.

## 6 Retention and Deletion

Local app data remains on your device until it is changed or removed through app controls or by deleting the app.

Some app actions, such as deleting transactions, deleting recurring rules, archiving categories, or deactivating budgets, may keep local inactive or soft-deleted rows in the database for history, relationship integrity, duplicate detection, and CSV backup/restore behavior. These rows are not shown as active records in normal app views.

To remove the local app database and preferences, use **Delete App** for SimBook in **Settings > General > iPhone Storage** or **iPad Storage**. **Offload App** keeps the app's documents and data, and removing its Home Screen icon alone does not delete the app. See Apple's [app storage guidance](https://support.apple.com/en-us/108429).

Deleting SimBook does not automatically remove existing device backups, exported files, or Apple's purchase records. Manage backup copies separately through the relevant system or storage service. Restoring a device backup may restore previously backed-up app data.

Because SimBook has no cloud account or developer-operated server database, the developer generally cannot restore local records after deletion, app removal, device loss, or device failure.

CSV files remain wherever you save, upload, copy, or share them. Deleting data inside SimBook does not automatically delete CSV files previously exported. Exported CSV files are outside the app's local database and are not encrypted by SimBook.

Support messages may be retained for as long as reasonably necessary to respond to your request, maintain support records, comply with legal obligations, resolve disputes, and prevent misuse. Apple may retain purchase and payment records according to its policies and applicable law.

## 7 Regional Privacy Rights

SimBook stores financial records locally, subject to the backup and export situations described above. Unless you choose to send records to the developer, the developer does not possess a copy and cannot remotely access, correct, export, or delete them.

Depending on where you live, including in the European Economic Area, United Kingdom, Switzerland, Brazil, California, and other regions with privacy laws, you may have rights regarding personal information the developer processes, such as support communications or purchase-support records. These rights may include access, correction, deletion, portability, objection, restriction, withdrawal of consent where applicable, appeal, and the right to lodge a complaint with a regulator.

The developer may be located in a country different from yours, and support providers, Apple, and other services you choose may process information in other countries. Those countries may have privacy laws different from your country. Where required, the developer will use appropriate safeguards for international transfers of personal information the developer controls.

To exercise rights related to information the developer may hold, contact support. Requests concerning information held independently by Apple or another provider should be directed to that provider.

## 8 Children

SimBook is not directed to children and is intended as a personal finance utility for adults to manage personal financial records under applicable law. The developer does not collect personal information from children through the app.

If you believe a child has provided personal information to the developer through support communications, contact support so the developer can review and delete it where required.

## 9 Third Party Policies

Third-party services used by or related to the app may have their own terms and privacy policies, including Apple App Store services, iCloud Backup, iCloud Drive, Frankfurter Open API, iOS and iPadOS file providers, storage apps you choose, and your email/support provider. The developer is not responsible for third-party services it does not control.

Apple's handling of information through its platform and services is described in its [Privacy Policy](https://www.apple.com/legal/privacy/).

## 10 Changes to This Privacy Policy

The developer may update this Privacy Policy from time to time. When changes are made, changes will be communicated through the App Store listing or through another appropriate channel.

Your continued use of the app after a policy update means the updated policy applies to your use, where permitted by applicable law. Where applicable law requires consent to a change, the developer will obtain that consent.

## 11 Contact

For privacy questions or requests, contact: [simbooksupport@gmail.com](mailto:simbooksupport@gmail.com).
