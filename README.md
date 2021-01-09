# Lithium Text Extractor
Simple web interface to extract highlighted text from exported ebook data from Lithium.

Available here: https://and96.github.io/Lithium-Text-Extractor/

### What is Lithium?
"Lithium: EPUB Reader" is an Ebook Reader for Android devices.

It's available on [PlayStore](https://play.google.com/store/apps/details?id=com.faultexception.reader)

### How to export data from Lithium?
1. Open Lithium app on Android
2. Long press on ebook title
3. Tap on "options" icon in the corner then "Export data"
4. Select "Highlights & notes" and "HTML file"
5. Export and save the file in a directory

### How to extract highlighted text?
1. Go to https://and96.github.io/Lithium-Text-Extractor/
2. Select file
3. Select a color (OPTIONAL)
4. Press "Process"

### Development
It's written in Javascript and uses Bootstrap v5 components as Frontend. 

Extraction is made with Regular Expressions.

Everything is parsed in the Browser (Client side, no backend or other software required).

