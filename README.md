# Dashboard Royalties

Questo repository contiene un'applicazione web per visualizzare e analizzare i dati di royalties in modo interattivo.

## Caratteristiche

- **Dashboard interattiva** con statistiche chiave
- **Visualizzazioni grafiche** (grafici a torta e a barre)
- **Tabella dettagliata** con funzionalità di ordinamento e filtro
- **Selezione del periodo** (mese e anno)
- **Funzionalità di ricerca avanzata**
- **Esportazione dati** in formato CSV
- **Confronto con periodi precedenti**
- **Design responsive** per tutti i dispositivi

## Come utilizzare

1. Clona questo repository o scarica i file
2. Apri `index.html` in un browser web
3. Utilizza i selettori di mese e anno per visualizzare i dati del periodo desiderato
4. Esplora le diverse visualizzazioni e funzionalità interattive

## Struttura del progetto

- `index.html` - File principale dell'applicazione
- `css/` - Fogli di stile
  - `styles.css` - Stili personalizzati
- `js/` - Script JavaScript
  - `main.js` - Funzionalità di base e visualizzazione dati
  - `interactive.js` - Funzionalità interattive avanzate
  - `period_selector.js` - Gestione della selezione del periodo
- `royalties_data.json` - Dati di esempio

## Personalizzazione

### Aggiungere nuovi dati

Per utilizzare i tuoi dati di royalties:

1. Sostituisci il file `royalties_data.json` con i tuoi dati
2. Assicurati che il formato sia compatibile:
```json
[
  {
    "descrizione": "Nome elemento",
    "valore": 1000.00
  },
  ...
]
```

### Modificare l'aspetto

Puoi personalizzare l'aspetto modificando il file `css/styles.css`.

## Tecnologie utilizzate

- HTML5
- CSS3 (con Bootstrap 5)
- JavaScript
- Chart.js per i grafici
- DataTables per le tabelle interattive

## Deployment

Puoi ospitare questa applicazione su qualsiasi servizio di hosting statico:

- GitHub Pages
- Netlify
- Vercel
- Amazon S3
- O qualsiasi server web standard

## Licenza

Questo progetto è disponibile con licenza MIT.

## Contribuire

Contributi, segnalazioni di bug e richieste di funzionalità sono benvenuti!
