# Textmining_Wahlprogramme
🚀 Projektstruktur
    
    01 Datenerfassung
      
      │── 01_scraping_parteiname.ipynb    
      # Extraktion und Gliederung aller Wahlprogramme (Parteiname steht hierbei für den Namen der Partei, dieser variiert innerhalb der Dateinamen)
      
      │── 01_extraction_wahlomat.ipynb    
      # Extraktion der Wahlomat-Thesen aus der bereitgestellten Excel Datei 

    02 Zusammenführung der Daten
      
      │── 02_combine_party_textes.ipynb   
      # Zusammenführen aller Parteitexte

    03 Vorbereitung der Daten und der Klassenzusammenhänge
      
      │── 03_adjazenzmatrix.ipynb                    
      # Definition der Adjazenzmatrix der ManifestoBERTa Klassen
      
      │── 03_preprocessed_texts.ipynb          
      # Vorverarbeitung der Texte


     04 Analyse der Daten

      │── 04_data_understanding         
      # Verständnis der Daten und Vergabe der ManifestoBERTAa Klassen    

    05 Modelle zur Klassifikation und Ähnlichkeitsanalyse
      
      │── 05_classification_manifestoBERTA.ipynb    
      # Modell-Ansatz 2, Labeling anhand der Manifesto Berta Klassen

      │── 05_spacy_similarity_run.ipynb       
      # Modell-Ansatz 1, reine Similarity Analyse

    06 Kombination der Modelle zur Ähnlichkeitsanalyse und Klassifikation 

      │── 06_class_labeled_similarity_run.ipynb                  
      # Modell-Ansatz 3.2, Labeling anhand der Manifesto Berta Klassen mit anschließender Similarity Analyse
      
      │── 06_domain_labeled_similarity_run.ipynb       
      # Modell-Ansatz 3.1, Labeling anhand der Manifesto Berta Haupt-Klassen mit anschließender Similarity Analyse, beinhaltet auch Durchläufe ohne Vorklassifizierung

    07 Auswertung der Ergebnisse
      
      │── 07_model_evaluation.ipynb                
      # Auswertung der Ergebnisse aller Modelle


🛠️ Installation

    1️⃣ Python & virtuelle Umgebung vorbereiten
                
                python -m venv venv
                source venv/bin/activate  # macOS/Linux
                venv\Scripts\activate    # Windows
                
    2️⃣ Abhängigkeiten installieren
    
                pip install -r requirements.txt

🎯 Nutzung

    Der Code muss in der durch die in den Dateinamen vergebenen Zahlen definierten Reihenfolge ausgeführt werden



