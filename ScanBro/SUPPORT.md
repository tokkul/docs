# ScanBro — Support

ScanBro logs boxes as they come in and go out. Scan the QR code or barcode on a
box with the camera, or type it, and every scan is saved as a row in a CSV file
that you can export, open in the Files app, or keep adding to.

## Contact

Questions, feedback, or trouble? Email **tokkul@gmail.com** and we'll help.
Please include your device model and iOS version, and a photo of the label if a
code won't scan.

## Frequently asked questions

### How do I scan a box?
Tap **Incoming** or **Outgoing** on the main screen. The camera opens and
highlights the codes it sees. When only one code is in view, ScanBro captures
it automatically after a short moment. The new scan glows briefly at the top
of the log and your phone gives a short vibration so you know it worked.

### The label has several codes. How do I pick the right one?
When more than one code is in view, ScanBro doesn't scan automatically. A list
of the codes appears at the bottom of the screen with each code's value and
type. Tap the one you want in the list, or tap the highlighted code directly in
the camera picture.

### A code won't scan. What can I do?
- Move a little closer, or pinch to zoom in on small codes.
- Make sure the code is well lit and not covered by glare from plastic wrap.
- Some labels are damaged or printed so that part of the code is missing (for
  example a QR code that runs off the edge of its label). No scanner can read
  those. Tap **Type** and enter the number printed next to the code instead.

### Can I use a Bluetooth or USB barcode scanner?
Yes. Tap **Type** in the scan screen; scanners that work like a keyboard type
the code into the field and save it.

### Which kinds of codes are supported?
Common 2D codes such as QR, Data Matrix, Aztec, and PDF417, and 1D barcodes
such as EAN-13, EAN-8, UPC, Code 128, Code 39, Code 93, ITF, and Codabar.

### How do I add a note to a scan?
Tap the scan in the log, type your note, and tap **Save**. The note appears
under the code and is saved in the CSV file's **Note** column. Tap the scan
again to change or remove the note.

### How do I delete a scan?
Swipe left on the scan in the log and tap **Delete**. It's removed from the
CSV file as well.

### How do I export my scans?
Tap the **Export** button (square with an arrow) at the top of the main screen
and choose where to send or save the CSV file: Mail, Messages, AirDrop, Files,
and so on.

### Where is the CSV file stored?
In ScanBro's own folder on your device. You can open it in the **Files** app
under **On My iPhone** (or **On My iPad**) **→ ScanBro**.

### What does the CSV file contain?
One row per scan with these columns: **Timestamp**, **Direction** (Incoming or
Outgoing), **Type** (for example QR, EAN13, or Manual), **Value**, and **Note**.
In **Settings** you can choose:

- **File name** — the file scans are saved to.
- **Delimiter** — semicolon (default), comma, or tab. Semicolon works well with
  spreadsheet apps that use a comma for decimals.
- **Timestamp** — ISO 8601 (UTC), local time, or Unix seconds.
- **Header row** — whether the first row lists the column names.

Changes to the format are applied to the whole file when you close Settings, so
a file always uses one delimiter and one timestamp format.

### Can I keep adding to a file I already have?
Yes. Open **Settings**. Under **Existing files**, tap any CSV file in ScanBro's
folder to switch to it; its scans appear in the log. To use a file from
somewhere else, tap **Import File…** and pick it. ScanBro copies it into its
folder. Files created by earlier versions of ScanBro work too.

### What happens when I change the file name?
ScanBro switches to the file with the new name, or starts a new one if it
doesn't exist yet. The old file is kept, and you can switch back to it under
**Existing files**.

### How do I start over?
In **Settings**, tap **Delete** to remove the current file. The log is cleared
when you close Settings. This can't be undone, so export the file first if you
might need it.

### Why can't I use the camera?
ScanBro needs permission to use the camera. Turn it on in **Settings → ScanBro
→ Camera**. Camera scanning also needs an iPhone XS / XR or newer, or a
comparable iPad. On other devices you can still type codes or use a hardware
scanner.

### Which languages are supported?
English.

### What about privacy?
Your scans stay on your device. ScanBro doesn't collect or send any data, and
camera images are never saved. See the [Privacy Policy](PRIVACY.md).

## Version

This page applies to ScanBro 1.0 and later.
