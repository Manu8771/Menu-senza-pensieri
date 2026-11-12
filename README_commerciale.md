# Menù senza pensieri – Versione PWA di prova

Contenuto:
- `index.html`: applicazione originale con il nuovo nome; logica e dati locali mantenuti.
- `manifest.webmanifest`: impostazioni per l'installazione sul telefono.
- `service-worker.js`: cache offline della PWA.
- `icons/`: icone ricavate dall'immagine scelta dall'utente.
- `Licenza_uso_personale.md`: bozza di licenza da completare prima di vendere.
- `Registro_licenze.csv`: modello di registro acquisti.

## Come provarla
Questa cartella va pubblicata su un hosting HTTPS che supporti file statici. Dopo la pubblicazione, aprire il link con Chrome su Android e scegliere "Installa app" o "Aggiungi a schermata Home".

## Importante
- La PWA richiede HTTPS per installazione e service worker.
- I dati restano locali nel browser/dispositivo e non si sincronizzano tra dispositivi.
- La cache offline viene attivata dopo la prima apertura online.
- Il link pubblico può essere inoltrato: questa versione non include autenticazione o blocco tecnico delle copie.
- Prima di mettere in vendita il prodotto, verificare backup/esportazione dei dati, compatibilità sui dispositivi e condizioni legali/fiscali.
