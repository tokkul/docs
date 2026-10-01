# Privacy Policy

**App:** SecretBro
**Last updated:** 2026-10-01

SecretBro is a password manager designed to keep your secrets yours. Your
privacy is respected by design: **SecretBro does not collect, transmit, sell, or
share your personal data with us or any third party.** SecretBro has no accounts
of its own, no analytics, and no advertising. The only place your data travels
is your own Apple iCloud account, and only if you keep iCloud enabled.

## What data SecretBro uses

Everything you create in SecretBro is your content:

- **Entries** — titles, usernames, websites, categories, and notes.
- **Category details** — depending on the category you choose, an entry can hold
  extra fields such as card number, expiry, security code (CVV) and PIN for
  cards; account, routing, IBAN and SWIFT for banks; Wi-Fi network details; and
  passport details.
- **Secrets** — passwords, pincodes, card numbers, security codes, and PINs.

**Everything you store is encrypted on your device** with AES-256-GCM before it
is ever written to storage or iCloud — not just passwords, but the title,
username, website, category and notes too. The encryption key is generated on
your device and kept in the Apple **Keychain**; it never leaves your devices
except through your own iCloud Keychain, and SecretBro never sends it to us. When
you open the app and unlock it, SecretBro decrypts your entries in memory so you
can browse and search them; nothing searchable is stored in the clear.

Data is stored **on your device** using Apple's standard local storage
(SwiftData in a shared App Group, so the SecretBro app and its AutoFill
extension can read the same vault).

## Face ID

SecretBro uses **Face ID** (or Touch ID, falling back to your device passcode)
to unlock the app. Biometric authentication is performed by iOS; SecretBro never
sees your face or fingerprint data. The app also locks automatically when it
goes to the background and hides its contents in the app switcher.

## iCloud sync

SecretBro uses **Apple's iCloud (CloudKit)** to sync your encrypted vault across
your own devices, including your Apple Watch.

- Your data syncs through **your own iCloud account**. SecretBro does not run its
  own servers and never receives a copy of your logins. Data stored in iCloud is
  handled by Apple under [Apple's Privacy Policy](https://www.apple.com/legal/privacy/)
  and iCloud terms.
- Because secrets are encrypted before they leave the device, what is stored in
  iCloud is ciphertext. The encryption key syncs separately through **iCloud
  Keychain**, which is protected by Apple.
- If you turn iCloud off (or sign out of iCloud), SecretBro keeps working with
  the vault stored locally on that device; it simply won't sync.

## AutoFill

If you enable SecretBro in **Settings → General → AutoFill & Passwords**, iOS can
suggest your saved logins when you sign in to apps and websites. To make this
work, SecretBro registers your logins' **website and username** (not passwords)
with the system so iOS knows which entry matches a site. Passwords are decrypted
only at the moment you choose to fill one.

## Optional breach check (Have I Been Pwned)

SecretBro includes an optional **Security Audit** that can tell you if a password
has appeared in a known data breach. This is the only feature that contacts the
internet, and it is designed to protect your privacy using **k-anonymity**:

- SecretBro computes a SHA-1 hash of the password **on your device** and sends
  only the **first five characters** of that hash to the
  [Have I Been Pwned](https://haveibeenpwned.com/) Pwned Passwords API.
- Your actual password, username, and the full hash are **never** sent.
- The audit runs only when you open it. If you never use it, SecretBro makes no
  network requests at all.

## Importing and exporting

SecretBro can export your entries to a CSV file and import entries from a CSV
file or a **1Password Interchange File (.1pif)** you choose, using the system
file picker. **An exported CSV contains your passwords, card numbers, PINs and
other secrets in plain text**, so the app warns you before exporting; store the
file safely and delete it when you're done. These files are read from or written
to the location **you** pick, and SecretBro does not upload them anywhere.

## What SecretBro does NOT do

- No SecretBro accounts, sign-in, or registration (sync uses your own iCloud).
- No analytics, usage tracking, advertising, or profiling.
- No third-party advertising or tracking SDKs.
- No developer-operated servers — SecretBro does not send your data to us.
- No location, microphone, contacts, or health data access.

## Your control over your data

- Edit or delete any login in the app to remove that content; the change syncs to
  your other devices.
- Use **Settings → Erase Vault** in the app to permanently delete every login and
  the encryption key from your devices.
- Manage what SecretBro keeps in iCloud from **Settings → [your name] → iCloud**
  on your device.
- Deleting the SecretBro app removes its local data from that device. Content in
  iCloud is removed according to Apple's iCloud behaviour and your iCloud
  settings.

## Children

SecretBro does not knowingly collect any data from anyone, including children.

## Changes to this policy

If this policy changes, the updated version will be published here with a new
"Last updated" date.

## Contact

Questions about privacy in SecretBro can be sent to: **tokkul@gmail.com**
