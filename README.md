# ML-KEM-Grundlagen

Dieses Repository enthält ein interaktives Jupyter Notebook, welches im Rahmen der Bachelorarbeit entstanden ist.

## Beschreibung

Das Jupyter Notebook befasst sich mit den Grundlagen des Post-Quanten-Kryptografie Standards ML-KEM und zielt darauf ab, die Inhalte des Verfahrens didaktisch aufzubereiten. 
Diese Aufbereitung erfolgt mithilfe erklärender Texte, welche durch interaktive Visualisierungen und verschiedene Beispiele unterstützt werden. 

## Wichtiger Hinweis zur Ausführung

Für eine korrekte Darstellung sowie volle Funktionalität wird zwingend empfohlen das Notebook lokal auszuführen. Beim JupyterHub der HTWK traten leider Einschränkungen und Layout- bzw. Formatierungsfehler auf. Es konnten z.B. einige Zellen nicht fehlerfrei ausgeführt werden, Output-Fenster hatten platztechnisch Probleme und wurden abgeschnitten, alle Quellcodes ließen sich nicht einklappen, HTML/CSS hat nur bedingt funktioniert. Daher musste leider auf die zusätzliche Bitte mit der Bereitstellung im JupyterHub verzichtet werden. Eine einfache Anleitung zur Einrichtung kann weiter unten vorgefunden werden.

## Lernsektionen des Notebooks

* ### 1. Motivation und Einführung
* ### 2. Theoretische Grundlagen
* ### 3. Architektur und Gesamtablauf von ML-KEM
* ### 4. Effizienzsteigerung durch die Number Theoretic Transform (NTT)
* ### 5. Zusammenfassung

## Projektstruktur
```
./
├── ml_kem_grundlagen.ipynb
├── requirements.txt
└── bilder/
    ├── ...
    └── ...
```

## Einrichtung des Projektes

1.  **Projekt klonen**
2.  **Projekt in einer IDE (z.B. VSCode) öffnen**

3.  **Virtuelle Umgebung erstellen und aktivieren :**
    ```bash
    # Erstellen
    python -m venv .venv

    # Aktivieren (Windows)
    .\.venv\Scripts\activate

    # Aktivieren (macOS/Linux)
    source .venv/bin/activate
    ```

4.  **Abhängigkeiten installieren:**
    ```bash
    pip install -r requirements.txt
    ```

5.  **Notebook-Datei öffnen und Codezellen ausführen**
    Datei ```ml_kem_grundlagen.ipynb``` öffnen und sicherstellen, dass oben rechts als Kernel die richtige ```.venv``` ausgewählt ist.

## Autor
- Thanh Pham
