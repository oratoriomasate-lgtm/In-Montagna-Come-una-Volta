# In Montagna Come una Volta

Sito del gruppo — nessun account Claude richiesto per chi lo visita, una volta pubblicato.

## Contenuto della cartella

- `index.html` — l'intero sito (una pagina sola: testo, grafica e codice)
- `photos/` — le foto delle gite, referenziate dal sito

Tenete questi due insieme: `index.html` cerca le immagini dentro `photos/`.

## Come pubblicarlo gratis (GitHub Pages)

Serve solo **a te** (chi pubblica) un account GitHub gratuito — su [github.com](https://github.com), due minuti. Chi visita il sito dopo non ha bisogno di nulla.

1. Vai su [github.com/new](https://github.com/new) e crea un repository.
   - Nome: quello che vuoi, es. `in-montagna-come-una-volta`
   - Deve essere **Public**
   - Non serve spuntare "Add a README" — ce l'hai già in questa cartella
2. Nella pagina del repository appena creato, clicca **"uploading an existing file"** (o "Add file → Upload files")
3. Trascina dentro **tutta** questa cartella (o tutti i file, mantenendo `photos/` come sottocartella) e clicca **Commit changes**
4. Vai su **Settings → Pages** (menu a sinistra)
5. Sotto "Build and deployment", in **Branch** seleziona `main` (o `master`) e cartella `/root`, poi **Save**
6. Dopo un paio di minuti, GitHub mostra il link del sito in cima alla stessa pagina — qualcosa come:
   `https://<tuo-username>.github.io/in-montagna-come-una-volta/`

Quel link è quello da mandare nel gruppo WhatsApp. Funziona per chiunque, senza login.

## Come aggiornarlo con nuove gite

Il modo più semplice: torna qui in chat con Claude, mandami i dettagli della nuova gita (data, percorso, chi c'era, foto), aggiorno `index.html` (e `photos/` se ci sono nuove immagini) e ti riconsegno la cartella aggiornata da ricaricare su GitHub (stesso repository, sovrascrivendo i file).

Se preferisci farlo da solo: apri `index.html` con un editor di testo, cerca `var trips = [` verso la fine del file, e aggiungi un nuovo blocco `{ ... }` copiando la struttura di quello esistente.
