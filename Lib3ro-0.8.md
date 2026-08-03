## Nuove feature

- Introdotta la gestione fiscale per Inarcassa: se sei iscritto alla cassa, l'app gestisce fatture, scadenze e accantonamenti con le regole giuste. In concreto:
  - contributo integrativo del 4% addebitato in fattura, nel PDF e nell'XML per lo SdI, e tenuto fuori dal reddito imponibile dove non deve stare;
  - card del regime con cassa, anno di prima iscrizione, agevolazione giovani, deroga dai minimi e rateizzazione in 6 rate;
  - scadenzario e pagina Tasse sul calendario vero della cassa: rate dei minimi (2 o 6) e conguagli dell'anno successivo;
  - data di nascita in anagrafica, così il limite dei 35 anni per l'agevolazione giovani lo verifica l'app invece di lasciartelo controllare a mano;
  - toggle "committente estero" in fattura: verso UE ed extra-UE il contributo non è dovuto e non viene addebitato;
  - il codice ATECO 71 (ingegneria e architettura) preseleziona Inarcassa al posto della Gestione Separata, e resta modificabile;
  - le fatture già importate recuperano da sole il contributo dal proprio XML, che altrimenti resterebbe contato come reddito negli anni archiviati.
- Aggiunto un campo "Ore da fatturare" alla rendicontazione delle attività, per quando serve tracciare ore divergenti tra effort effettivo ed effort fatturabile al cliente.

## Miglioramenti

- Stati e modifica delle fatture: la modifica è raggiungibile da drawer, doppio click e menu contestuale, una fattura "Emessa" ma non ancora trasmessa si può sbloccare per correggerla e ritrasmetterla con stesso numero e data, e ovunque vengono offerti solo i cambi di stato davvero permessi.
- Corretto il layout delle card della pagina "Importa dati" nelle impostazioni: ora hanno tutte la stessa altezza e gli hint dicono quali valori sono ammessi in ogni colonna; il foglio Istruzioni è presente anche nei template xlsx degli import singoli, oltre a quello dell'intero sistema.
- Pagina Backup riordinata: il "Punto di ripristino" pre-avvio è in cima, il backup automatico si attiva con uno switch, i testi non usano più gergo tecnico. Ora la gestione dei backup e il loro utilizzo dovrebbero risultare più chiari.
- Riconciliati tutti i componenti "card" in un singolo componente. Nessuna differenza percepibile, solo un miglioramento tecnico e riduzione di codice.

## Bug fix

- L'extra budget di un progetto si somma al budget invece di sostituirlo, ed entra nel budget mostrato, nella soglia di consumo e nel budget ripartito tra le attività.
- In Entrate, i giorni lavorativi personalizzati di un mese non vengono più sovrascritti dal valore da calendario quando riapri il drawer.
- Il selettore degli anni in Entrate elenca gli anni delle fatture: chi importa fatture senza registrare ore non trova più il menu quasi vuoto.

## Note

- I parametri Inarcassa coprono dal 2024 in avanti. Per gli anni precedenti le fonti si contraddicono, quindi l'app dichiara "parametri non disponibili" invece di calcolare su numeri non verificati.
