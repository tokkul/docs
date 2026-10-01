# SecretBro — Support

SecretBro keeps your passwords, pincodes, cards, and other secrets safe behind
Face ID, generates strong passwords, and fills logins for you with AutoFill —
everything encrypted on device and synced across your devices with iCloud.

## Contact

Questions, feedback, or trouble? Email **tokkul@gmail.com** and we'll help.
Please include your device model and iOS version.

## Frequently asked questions

### How do I unlock the app?
SecretBro is protected by **Face ID** (or Touch ID, falling back to your device
passcode). It unlocks when you open it, locks again when it goes to the
background, and hides its contents in the app switcher. You can choose how long
it may stay in the background before requiring Face ID again in **Settings →
Auto-Lock**.

### How do I add an entry?
Tap **+**, enter a title, and pick a **category** (Website, Bank, Card, Email,
Note, Work, WiFi, Passport, or your own). The form then shows the fields that fit
that category — for example a Card shows card number, cardholder, expiry,
security code and PIN, while a Website shows username, website and password. Tap
**Save**. Only a title is required.

To mark a favourite, **swipe an entry to the right** in the list. Favourites are
pinned to the top, and the list is grouped into collapsible category sections.

### How do I generate a strong password?
While adding or editing a login, tap **Generate Strong Password**. SecretBro
creates a long, random password (avoiding easily-confused characters).

### How do I copy a password or username?
Open a login and tap the copy button next to the field. For your protection,
SecretBro asks the system to **clear the clipboard automatically** after about 30
seconds.

### Can I hide passwords and card numbers until I tap to reveal?
Yes. Turn on **Settings → Hide Secrets**. Passwords, card numbers, security codes
and PINs are then masked until you tap the reveal (eye) button. It's off by
default, so values show in clear text.

### How do I turn on AutoFill?
Go to **Settings → General → AutoFill & Passwords**, enable **SecretBro**, and
make sure it's allowed to fill passwords. Give each login a **website** so iOS
can match it to the right site. iOS will then suggest your SecretBro logins when
you sign in to apps and websites.

### How do I check for weak, reused, or breached passwords?
Open the menu and choose **Security Audit**. SecretBro flags passwords that are
too short, used on more than one login, or found in a known data breach. The
breach check uses Have I Been Pwned's k-anonymity API and never sends your actual
password — see the [Privacy Policy](PRIVACY.md).

### Does SecretBro sync across my devices?
Yes. SecretBro syncs through **your own iCloud account**, so entries you add on
one device appear on your others. Everything is encrypted before it leaves the
device, and the encryption key syncs through iCloud Keychain. Make sure you're
signed in to iCloud and that iCloud is enabled for SecretBro.

### Can I import or export my logins?
Yes. You can **export to a CSV file** and **import from a CSV file** or a
**1Password Interchange File (.1pif)** you choose. On import, SecretBro maps
1Password logins, cards, bank accounts, Wi-Fi routers, passports, identities and
memberships to the matching categories; anything it can't map to a field is kept
in the entry's Notes so nothing is lost. The exported CSV preserves
category-specific fields so it can be imported back.

Note that an exported CSV contains your passwords, card numbers, PINs and other
secrets **in plain text**, so SecretBro warns you first — store the file safely
and delete it when you're done.

### What happens if I choose "Erase Vault"?
**Settings → Erase Vault** permanently deletes every login and the encryption
key. This cannot be undone, and any exported CSV is the only way to recover data
afterwards.

### I opened the app and my older test entries won't show a password. Why?
If your encryption key changed (for example after enabling iCloud sync), older
entries created with a previous key can no longer be decrypted. Erase the vault
and re-add them, or restore from a CSV export.

### Which languages are supported?
English. SecretBro follows your device language where possible.

### What about privacy?
SecretBro keeps your secrets encrypted on your device and syncs them through
**your own iCloud** — it doesn't collect or transmit your data to us. See the
[Privacy Policy](PRIVACY.md).

## Version

This page applies to SecretBro 1.0 and later.
