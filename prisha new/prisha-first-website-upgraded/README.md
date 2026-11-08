# Prisha — upgraded website

Open `index.html` in a browser (or upload the whole folder to any static host).
Your original design, 3D heart, falling petals, love letter, YES/NO buttons and WhatsApp links are untouched —
all new features are added around them.

## Where to put your personal content

Everything personal lives in one clearly marked block near the bottom of `index.html`:
**"✎ YOUR CONTENT — edit this block only."**

| Feature | What to do |
|---|---|
| Polaroids | Drop photos in `assets/photos/` named `memory-1.jpg` … `memory-6.jpg`. Edit captions, dates and back-of-photo notes in the config. (Empty frames let you tap "choose photo" to preview a picture.) |
| Music player | Put your song at `assets/music/our-song.mp3`. Until then a soft built-in ambient track plays. |
| Sealed letter | Edit the text inside `<article class="hand-letter">` (search for "EDIT YOUR SEALED LETTER"). Replace the `[ ... ]` line. |
| 3D heart messages, reasons, "things I still want…", quiz, final confession | All editable in the config block. Lines starting with `[ ... ]` are placeholders. |

## Notes
- Hold the wax seal for about a second (or press Enter on a keyboard) to open the letter.
- The final confession's "Reply on WhatsApp" button uses your existing number with a short pre-filled message — edit it in the `cineWa` link.
- Handwriting fonts (Caveat, La Belle Aurore) load from Google Fonts, so they need internet.
