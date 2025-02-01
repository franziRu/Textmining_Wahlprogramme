# Textmining_Wahlprogramme
# Textmining_Wahlprogramme

🛠️ Projektstruktur

wahlprogramme-analyse/
│── wahlprogramme_scraper.py  # Web Scraper
│── text_cleaner.py           # Wahlprogramm-Extraktion & Reinigung
│── text_analysis.py          # Wortanalyse & Wordcloud
│── preprocessing.py          # Stopwords, Interpunktion & Lemmatisierung
│── main.py                   # Steuerung der Analyse
│── requirements.txt          # Python-Pakete
│── README.md                 # Projektbeschreibung

🔍 Funktionsübersicht

1️⃣ wahlprogramme_scraper.py

Holt die HTML-Inhalte der Wahlprogramme von verschiedenen Parteiseiten

Extrahiert den sichtbaren Text

2️⃣ text_cleaner.py

Entfernt allgemeine Inhalte wie Impressum & Datenschutz

Begrenzt den Text auf den relevanten Bereich des Wahlprogramms

3️⃣ text_analysis.py

Zählt die Anzahl der Wörter

Ermittelt die häufigsten Wörter

Erstellt eine Wordcloud für eine visuelle Analyse

4️⃣ preprocessing.py

Entfernt Stopwords

Entfernt Interpunktion

Lemmatisiert Wörter zur besseren Analyse

Prüft die Auswirkungen des Entfernens von Zahlen

5️⃣ main.py

Führt alle Module zusammen und koordiniert die Analyse

Zeigt erste Ergebnisse wie Wortanzahl & häufigste Begriffe an

🛠️ Installation

1️⃣ Python & virtuelle Umgebung vorbereiten

python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate    # Windows

2️⃣ Abhängigkeiten installieren

pip install -r requirements.txt

🎯 Nutzung

1️⃣ Projekt starten

python main.py

Nach der Ausführung werden die Wahlprogramme analysiert und relevante Daten ausgegeben.

📅 requirements.txt

beautifulsoup4
requests
nltk
wordcloud
matplotlib

Diese Bibliotheken sind erforderlich für das Web Scraping, die Textverarbeitung und die Visualisierung der Ergebnisse.
