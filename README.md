# 🏠 Vademecum di casa

App web semplice e interattiva con guide, checklist e calcolatori per la vita domestica: casa, colf, rifiuti, lavatrice, stiro, cibo, forma fisica, auto, numeri utili, spese, agevolazioni over 65 e consigli.

È un unico file `index.html`, senza dipendenze: funziona anche offline e salva checklist, scadenze e numeri **solo sul dispositivo** di chi la usa (localStorage), senza inviare nulla a server.

## Pubblicarla su GitHub Pages

1. Crea un account su [github.com](https://github.com) e un nuovo repository, ad esempio `vademecum-casa` (pubblico).
2. Carica in questo repository i file della cartella: `index.html`, `README.md` e `.nojekyll`.
3. Vai su **Settings → Pages**.
4. In *Build and deployment* scegli **Deploy from a branch**, branch **main**, cartella **/ (root)**, poi **Save**.
5. Dopo 1-2 minuti l'app sarà online su:
   `https://TUO-UTENTE.github.io/vademecum-casa/`

## Note

- Le schede **Numeri**, **Spese** e **Auto** contengono dati personali, ma restano nel browser di chi apre la pagina: non vengono pubblicati.
- Importi, soglie ISEE e minimi contrattuali sono indicativi (2026) e vanno verificati ogni anno sui siti ufficiali.
- I link ai video portano a ricerche su YouTube.
- Per aggiornare l'app basta sostituire `index.html` nel repository.
