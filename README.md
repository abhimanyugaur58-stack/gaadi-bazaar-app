# गाड़ी बाज़ार · Gaadi Bazaar — downloads

**डाउनलोड पेज / Download page:** https://abhimanyugaur58-stack.github.io/gaadi-bazaar-app/

यह रिपो सिर्फ़ गाड़ी बाज़ार गेम की Android APK फ़ाइलें और नए वर्शन की जानकारी (`version.json`) रखता है। गेम का कोड यहाँ नहीं है।
This repository only holds the Android APK files of the Gaadi Bazaar game and the latest-version info (`version.json`). The game's code is not here.

- `apk/` — हर जारी वर्शन की APK, कभी बदली नहीं जाती / every released APK, never replaced
- `version.json` — सबसे नए वर्शन का नंबर, फ़ाइल, साइज़, SHA-256 और "क्या नया है" / latest version number, file, size, SHA-256 and notes
- `index.html` — डाउनलोड पेज / the download page

दूसरा रास्ता (jsDelivr) हर APK को उसी commit से देता है जिसमें वह जुड़ी थी (`…@<commit>/apk/…`), इसलिए वह पता कभी नहीं बदलता।
The second link (jsDelivr) serves every APK from the commit that added it (`…@<commit>/apk/…`), so that address never changes.
