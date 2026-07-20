## Nuove feature

- Gestione dei regimi contributivi Artigiani e Commercianti, oltre alla Gestione Separata: calcolo acconti e scadenzario si adattano automaticamente al regime scelto.
- Aggiornamento automatico dell'app: nuovo tab Aggiornamenti con changelog integrato e controllo in background.
- Import di fatture elettroniche firmate digitalmente (formato .p7m), con archiviazione della firma.
- Creando una fattura, il cliente collegato viene creato o aggiornato automaticamente con i suoi dati.
- Nuovo step di onboarding per l'import delle fatture, coerente con i moduli attivati.

## Miglioramenti

- Nuovo flag "Importo manuale" sui progetti: se attivato, gli importi della rendicontazione non vengono più ricalcolati automaticamente e restano quelli inseriti o importati.
- Il tipo di soggetto del cliente (persona fisica/giuridica) non viene più indovinato dal nome, ma salvato esplicitamente.
- Import/export dei clienti include ora anche i dati di fatturazione.
- Aggiunte le aree di interazione sotto ai bottoni a icona, per migliorare l'usabilità e la precisione del tocco/click.
- L'invio di feedback viene inviato direttamente dalla piattaforma invece di aprire l'app Mail dell'utente.

## Bug fix

- Corretto l'import/export dei progetti da xlsx: gli header con l'unità di misura (es. "Tariffa riferimento (€/h)") non venivano riconosciuti e il progetto restava segnalato come "da completare" anche a dati corretti.
- Risolto un bug per cui i pulsanti "Importa xlsx" nelle liste vuote di Progetti e Spese non funzionavano nel modo corretto.
- Risolto un blocco dell'interfaccia quando si aprivano allegati di grandi dimensioni.
- La card "Incassato" della dashboard considera ora la data di incasso, non quella di emissione della fattura.
- I dati di fatturazione inseriti nella scheda cliente vengono ora salvati correttamente.
- Dopo il ripristino di un backup, l'app si riavvia automaticamente invece di richiedere un riavvio manuale.
- Corretti diversi calcoli fiscali: acconti su imposta e contributi, coefficienti ATECO, testi e limiti del selettore anno.

## Note

- Il database ora vive in un percorso stabile fuori dalla sandbox dell'app; chi aggiorna da una versione precedente viene migrato automaticamente al primo avvio, senza perdita di dati.
