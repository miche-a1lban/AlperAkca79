![mini_gzip](https://raw.githubusercontent.com/stylish-haskell/flann/346ed65/assets/cover.png)

# mini_gzip

Ein lokaler Chat-Assistent mit LLM-Backend, Web-Suche und Python-Code-Ausführung.

## put-io-adder

- **Lokales LLM**: Läuft über Ollama mit konfigurierbarem Modell
- **Web-Suche**: DuckDuckGo-Integration für aktuelle Informationen
- **Python REPL**: Direkte Code-Ausführung für Berechnungen
- **Web-Oberfläche**: Chainlit-basiert

## scala_school

1. **Ollama installieren**: [ollama.com](https://ollama.com/download)
2. **Modell herunterladen**:
    ```bash
    ollama pull llama3.1:8b
    ```
3. Ollama-Dienst im Hintergrund laufen lassen.

## cassandra-reaper

### Option 1: Conda

```bash
conda create -n llm-chat python=3.11
conda activate llm-chat
chmod +x install.sh
./install.sh
```

Oder manuell:
```bash
pip install chainlit langchain langchain-community ollama ddgs
```

### Option 2: pip

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## gsx2json

1. Umgebung aktivieren
2. Ollama-Dienst sicherstellen
3. Ins Projektverzeichnis wechseln
4. Starten:
    ```bash
    chmod +x run.sh && ./run.sh
    ```

Oder manuell:
```bash
chainlit run app.py -w
```

## kitchen-vagrant

### Verfügbare Tools

- **Web-Suche**: Aktuelle Ereignisse, Nachrichten, Preise
  - Beispiel: "Was sind die neuesten Entwicklungen in der KI?"

- **Python REPL**: Berechnungen, Datenanalyse, Visualisierungen
  - Beispiel: "Berechne den Zinseszins für 1000€ bei 5% über 10 Jahre"
  - Beispiel: "Erstelle einen Plot der Fibonacci-Folge"

## openage

```
http://localhost:8000
```

Port wird automatisch gewählt falls 8000 belegt.

## reaver-wps-1

- **Ollama-Verbindung**: Sicherstellen, dass Dienst läuft und Modell heruntergeladen
- **Port belegt**: Chainlit wählt automatisch verfügbaren Port
- **WebSocket-Fehler**: Browser-Seite aktualisieren oder App neu starten

## davglass-github-com

```
Suche nach den Geburtsjahren von Niels Bohr und Marie Curie via Web-Suche,
berechne die Altersdifferenz mit Python REPL.
```

## lede-source

![Screenshot1](_Project/Screenshot1.png)
![Screenshot2](_Project/Screenshot2.png)
