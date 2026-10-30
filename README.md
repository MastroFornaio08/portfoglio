# PLAYER ONE — Portfolio

Portfolio creativo interattivo a tema videogioco e sistema solare. La scena 3D usa Three.js da jsDelivr; il sito è una pagina statica HTML, quindi non richiede un server Next.js per essere pubblicato.

## Avvio locale

Apri `index.html` nel browser oppure avvia un server statico dalla cartella del repository:

```bash
python3 -m http.server 8000
```

Poi visita http://localhost:8000.

## Pubblicazione con GitHub Pages

Il workflow `.github/workflows/deploy-pages.yml` pubblica automaticamente il sito quando viene inviato un commit al branch `main`. Per la prima pubblicazione, in GitHub apri **Settings → Pages** e scegli **GitHub Actions** come sorgente di build e deployment. Dopo il completamento del workflow, il sito sarà disponibile su:

https://mastrofornaio08.github.io/portfoglio/

## Personalizzazione

Modifica `index.html` per aggiornare nome, progetti, descrizione, competenze e indirizzo email. I progetti attuali sono contenuti dimostrativi da sostituire con i lavori reali.
