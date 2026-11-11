# Kundennachrichten automatisch sortieren

Ein kleines Python-Projekt, das Kundennachrichten mit der Claude-API
automatisch einer Kategorie zuordnet: Lob, Beschwerde, Frage oder Sonstiges.

## Was es macht
- Liest Nachrichten aus `eingang.csv`
- Lässt Claude jede Nachricht einordnen (inklusive Sarkasmus und gemischter Nachrichten)
- Speichert das Ergebnis in `ausgang.csv`

## Technik
Python, Pandas, Anthropic API, Google Colab

## So nutzt du es
1. Notebook in Google Colab öffnen (Button im Notebook: "Open in Colab")
2. Eigenen API-Key als Secret `ANTHROPIC_API_KEY` in Colab speichern
3. Zelle ausführen. Das Notebook erstellt `eingang.csv` mit Beispielnachrichten und schreibt das Ergebnis in `ausgang.csv`

## Beispiel
| Nachricht | Kategorie |
|---|---|
| Das Produkt ist super, danke! | Lob |
| Na toll, schon wieder kaputt. | Beschwerde |
| Wie kann ich meine Adresse ändern? | Frage |
| Ich wollte nur sagen, dass ich umgezogen bin. | Sonstiges |

## Was ich dabei gelernt habe
Prompts mit klaren Regeln, System-Prompt, API-Kosten (Tokens), CSV-Verarbeitung.

## Hinweis
Der API-Key liegt als Secret in Colab und steht nicht im Code.
