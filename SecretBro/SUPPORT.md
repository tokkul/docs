# SecretBro — Support

SecretBro keeps your passwords, pincodes, and two-factor codes safe behind Face
ID, generates strong passwords, fills logins for you with AutoFill, and shows
your 2FA codes on your Apple Watch — all encrypted on device and synced across
your devices with iCloud.

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

### How do I add a login?
Tap **+**, then enter a title, username, website, and the password or pincode.
You can also add a category and mark favourites. Tap **Save**.

### How do I generate a strong password?
While adding or editing a login, tap **Generate Strong Password**. SecretBro
creates a long, random password (avoiding easily-confused characters).

### How do I copy a password or username?
Open a login and tap the copy button next to the field. For your protection,
SecretBro asks the system to **clear the clipboard automatically** after about 30
seconds.

### How do I set up two-factor (2FA) codes?
When adding or editing a login, paste the **setup key** (a base32 secret) or the
full **otpauth://** URI into the *Authenticator (2FA)* field. The login's detail
screen then shows a live 6-digit code with a countdown.

### How do I see codes on my Apple Watch?
Install the SecretBro watch app from the Watch app on your iPhone. Open SecretBro
on your iPhone at least once so your encryption key can sync via iCloud Keychain,
then your logins with a 2FA key will show live codes on your wrist.

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
Yes. SecretBro syncs through **your own iCloud account**, so logins you add on one
device appear on your others and on your Apple Watch. Your secrets are encrypted
before they leave the device, and the encryption key syncs through iCloud
Keychain. Make sure you're signed in to iCloud and that iCloud is enabled for
SecretBro.

### Can I import or export my logins?
Yes. You can **export to a CSV file** and **import from a CSV file** you choose.
Note that an exported CSV contains your passwords **in plain text**, so SecretBro
warns you first — store the file safely and delete it when you're done.

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
