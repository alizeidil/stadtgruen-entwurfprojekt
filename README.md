# stadtgruen-entwurfprojekt

# Stadtgrün Entwurfprojekt 

Dieses Repository enthält einen ersten Prototypen und Machbarkeitsnachweis (Proof of Concept) für die Anforderungen der Stadtgrün-App und des SGR-Wikis.

### Inhalt & Fokus:
- **RAG-Grundlagen:** Erste Experimente zur Verknüpfung von Textdaten mit intelligenten Sprachmodellen.
- **Trustworthy AI:** Fokus auf die präzise Steuerung der LLM-Ausgaben zur Vermeidung von Halluzinationen.
- **Faktenbasierte Parameter:** Eine niedrige Temperature (`0.1`) sorgt für deterministische und reproduzierbare Antworten, die für den Baustellenalltag essenziell sind.
### 🛠️ Tech-Stack
* **Sprache:** Python 3
* **Infrastruktur:** Google Colab
* **LLM Engine:** Groq SDK mit dem Modell `llama-3.1-8b-instant` (für extrem schnelle Antwortzeiten auf Mobilgeräten)

### 🔧 Installation & Nutzung

1. Das Repository klonen oder das Notebook `satdtgruen_entwurfprojekt.ipynb` direkt in Google Colab öffnen.
2. Das Groq SDK installieren:
```bash
   pip install groq
```
3. Den eigenen groq_api_key im Skript hinterlegen und die Zellen ausführen.
