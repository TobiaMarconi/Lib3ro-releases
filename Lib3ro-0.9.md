## Nuove feature

- **Supporto cassa professionale EPPI** — se sei iscritto alla cassa dei periti industriali, l'app calcola contributi e scadenze con le sue regole, come già fa per Inarcassa e la Gestione Separata:
  - addebita il contributo integrativo in fattura, e calcola acconti al 35% e saldo con la dichiarazione;
  - mostra scadenzario e pagina Tasse sul calendario di versamento della cassa, così sai quanto accantonare e per quando;
  - dalla card del regime imposti riduzione giovani (anche nella variante potenziata), aliquota soggettiva opzionale, tetto sul contributo soggettivo e minimo ridotto;
  - applica i parametri ufficiali dal 2015 al 2026, quindi anche gli anni già archiviati risultano calcolati con i valori giusti;
  - con un codice ATECO da perito industriale ti propone EPPI invece della Gestione Separata, e puoi cambiarla.
- **Gestione multi-tab con pannelli nativi macOS** — con ⌘T apri un nuovo pannello e tieni più contesti di lavoro aperti nella stessa finestra, ognuno con la propria navigazione; dalla barra in cima vedi cosa contiene ciascuno e ci passi con un click. Chiudendo l'app ritrovi gli stessi pannelli alla riapertura, con l'oggetto che stavi guardando nel drawer.
- **Validazione dei campi ed errori** — l'app ti segnala i dati sbagliati mentre compili invece di farti scoprire il problema all'invio, e ti avvisa quando un'operazione non riesce:
  - su P.IVA, codice fiscale, IBAN, CAP, provincia, codice SDI, ATECO, email e telefono ricevi un messaggio che spiega qual è l'errore e come correggerlo, e solo dopo che hai finito di scrivere il campo;
  - se il campo da correggere è in una sezione chiusa, al salvataggio l'app apre la sezione e ti porta sul campo, senza farti cercare dov'è l'errore;
  - aprendo il Profilo dalla nuova fattura non perdi quello che avevi già compilato: al ritorno ritrovi la bozza;
  - ricevi un avviso quando un backup non riesce, quando il controllo aggiornamenti fallisce (prima l'app rispondeva «Sei aggiornato»), quando l'import CSV scarta delle righe e quando un file FatturaPA non contiene i dati attesi;
  - se un download fallisce durante l'import, l'operazione si ferma e non ti ritrovi duplicate le fatture già importate.
- **Sistema di notifiche** — dopo ogni eliminazione, creazione, cambio di stato, copia o export ricevi una conferma in basso di cosa è appena successo, con il promemoria che puoi annullare con ⌘Z.
- **Drag & drop per importare file** — importi fatture elettroniche, XLSX di sistema, estratti conto e portafoglio investimenti trascinando il file nell'app, senza passare dal pannello di import. Il file viene indirizzato alla sezione giusta in base al contenuto, e se non è utilizzabile ricevi il motivo.

## Miglioramenti

- **Menu contestuali e azioni sugli oggetti** — raggiungi le stesse azioni da tre punti: tasto destro (menu riordinato in tre sezioni con icone, con Duplica su progetti e attività), menu di sistema (Nuovo, Vai, Impostazioni, Vista, Aiuto) e ⌘K, da cui esegui l'azione direttamente sull'oggetto trovato senza doverlo aprire.
- **Creazione fattura da un cliente** — dalla scheda cliente crei la fattura con le sue attività da fatturare già inserite, senza selezionarle una per una.
- **Bottoni che non si spengono** — «Crea», «Aggiungi» e «Genera» restano sempre premibili: premendoli scopri quali campi mancano, invece di dover indovinare perché il bottone è disabilitato.
- **Lavori incompleti salvabili** — puoi creare e salvare un oggetto anche senza avere tutti i dati, tenerlo come bozza e completarlo più avanti: un progetto in trattativa prima di conoscerne il prezzo, una transazione di cui non hai ancora l'importo, un pagamento senza importo atteso, un'attività segnaposto da valorizzare in seguito.
- **Parametri storici Inarcassa completi** — calcoli contributi e accantonamenti anche sugli anni dal 2015 in poi, dove prima l'app copriva solo dal 2024; quattro valori storici sono stati corretti.

## Bug fix

- **Progetti "A corpo"** — ora puoi creare un progetto a corpo: il bottone «Crea» restava disabilitato anche con tutti i campi compilati.
- **Carosello dell'onboarding** — durante l'onboarding scorre solo il pannello, mentre prima si muoveva anche la colonna laterale.
- **Eliminazione da tasto destro** — eliminando da tasto destro ti viene chiesta la stessa conferma del resto dell'app, così non cancelli per sbaglio.

## Note

- **Aggiornamenti incrementali** — aggiornando dalla 0.8 alla 0.9 scarichi solo le differenze rispetto alla versione installata invece dell'app intera: il file differenziale ora viene pubblicato insieme al rilascio.
