# Forge / Training OS

Web app personale per seguire il programma palestra, registrare le sessioni e preparare report copiabili in ChatGPT.

## Avvio locale

Non servono dipendenze o build step. Dalla cartella del progetto:

```bash
python3 -m http.server 8000
```

Apri poi `http://localhost:8000`.

I dati demo e i check-in vengono salvati in `localStorage` (`forge-training-v1`). L’export scarica un report Markdown e lo copia negli appunti. L’import Markdown mostra un’anteprima e accoda il nuovo blocco senza modificare lo storico.
