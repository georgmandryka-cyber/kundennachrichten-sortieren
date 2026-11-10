# Kundennachrichten automatisch sortieren

Ein kleines Python-Projekt, das Kundennachrichten mit der Claude-API
automatisch einer Kategorie zuordnet: Lob, Beschwerde, Frage oder Sonstiges.

## Was es macht
- Liest Nachrichten aus `eingang.csv`
- Lässt Claude jede Nachricht einordnen (inklusive Sarkasmus und gemischter Nachrichten)
- Speichert das Ergebnis in `ausgang.csv`

## Technik
Python, Pandas, Anthropic API, Google Colab

## Was ich dabei gelernt habe
Prompts mit klaren Regeln, System-Prompt, API-Kosten (Tokens), CSV-Verarbeitung.

## Hinweis
Der API-Key liegt als Secret in Colab und steht nicht im Code.
