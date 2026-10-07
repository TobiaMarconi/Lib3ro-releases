### Nuove Feature

**Simulazione delle tasse del prossimo anno:**

- nella pagina Tasse ora puoi selezionare l'anno prossimo e vedere una proiezione simulata del prossimo anno di pagamenti in base al tuo regime fiscale.
  - l'app stima il lordo dell'anno in corso dal ritmo dei tuoi incassi, oppure, finché i dati sono pochi, da quanto hai incassato l'anno prima, e ti dice sempre su quale base ha fatto il calcolo;
  - se preferisci, inserisci tu un importo con «Modifica importo» e torni alla stima con «Ripristina»;
  - se il lordo stimato supera 85.000 o 100.000 €, l'app ti avvisa che le regole del forfettario non varrebbero più.

**Confronto delle entrate fra diversi anni:**

- Nuova scheda “Confronto” nella pagina Entrate. Scegli fino a 4 anni che vuoi mettere a confronto, anche lontani tra loro, dove prima avevi solo il confronto con l'anno precedente;
  - per mese: un grafico a barre raggruppate e una tabella con un anno per colonna e la differenza tra due anni;
  - per cliente: i clienti principali a confronto, con la quota di ciascuno. Con un clic apri le fatture del cliente in quel periodo, con un doppio clic la sua pagina;
  - passando il mouse su una differenza ne vedi subito il valore in euro.

**Entrate attese dalle fatture emesse e non incassate:**

- con l'interruttore «Includi attese» nella scheda Mesi di Entrate vedi come si distribuiranno le entrate dei prossimi mesi contando anche le fatture emesse e non ancora incassate, ciascuna nel mese della sua scadenza. Prima, per avere questa previsione, dovevi segnare le fatture come saldate in anticipo; ora lo stato della fattura resta quello reale.

**Andamento del valore di un cliente nel tempo:**

- nella pagina di un cliente, la nuova scheda Andamento mostra anno per anno, e poi mese per mese, ore, rendicontato e incassato. Selezionando un periodo vedi da dove vengono quei numeri: i progetti con le loro ore, le fatture incassate e il collegamento a Rendicontazione già filtrata.

### Miglioramenti

**Data d'incasso durante l’import delle fatture:**

- dopo aver importato le fatture, l'app ti propone di segnare come incassate quelle ancora aperte, dalla schermata di onboarding o con un banner in Fatturazione. Prima dovevi cercare da solo le azioni multiple;
- quando segni una fattura come saldata, l'app ti dice con un piccolo avviso quale data d'incasso ha usato e perché (per esempio «alla scadenza»), e non ti propone mai una data nel futuro.

**Soglie del forfettario più chiare:**

- in Dashboard la barra «Soglia forfettario» cambia colore oltre 80.000 € e oltre 85.000 €, e vedi un solo avviso alla volta, il più importante. Prima la stessa soglia aveva due valori diversi e la barra e l'avviso riportavano percentuali diverse;
- se superi 100.000 € incassati sfondando il tetto del forfettario, l'app te lo segnala con un avviso bloccante che compare in qualunque pagina, una volta all'anno;
- la proiezione di fatturato tiene conto anche della stagionalità del tuo anno precedente: se di solito incassi molto a fine anno, a giugno la proiezione non ti dà più un valore troppo basso.

**Confronto con l'anno prima allo stesso giorno:**

- nelle card di Entrate e in Dashboard l'anno in corso si confronta con l'anno precedente fino alla stessa data («vs 2025 al 26/9»), e non più con l'anno intero. Prima, fino a dicembre, la differenza risultava quasi sempre negativa.

**Miglior coerenza nelle etichette dei numeri:**

- ogni numero ha lo stesso nome in tutte le pagine: «Rendicontato» per il lavoro svolto sui progetti, «Da incassare», «Residuo» dopo una nota di credito, «Pianificato» per le rate del piano;
- ogni netto ti dice su cosa è calcolato, e quando un numero non è calcolabile l'app ti spiega il motivo invece di mostrare solo un trattino;
- in Dashboard il netto dell'anno è lo stesso della pagina Tasse, anche quando è negativo;
- nel pannello laterale di un cliente le card dei progetti mostrano il rendicontato, insieme al tipo e alla tariffa con l'unità di misura. Prima c'erano due cifre senza spiegazione.
- tante altre modifiche in tutta l’interfaccia.

**Velocità delle query con molti dati:**

- i fogli «Collega attività» e «Collega pagamento» delle fatture si aprono subito anche con centinaia di voci (prima servivano fino a 15 secondi), e la ricerca ignora gli accenti;
- nelle tabelle Rendicontazione, Fatturazione, Clienti e Progetti i filtri e la ricerca rispondono più velocemente anche con migliaia di righe.

**Nuova regolamentazione dal 2027:**

- per le fatture emesse dal 1° gennaio 2027 l'app indica, nell'XML e nel PDF, il nuovo riferimento normativo del regime forfettario (D.Lgs. 117/2026), insieme a quello precedente che il cliente già conosce.

**Rifiniture delle tabelle:**

- nelle colonne numeriche anche l'intestazione è allineata a destra;
- eventuali tooltip compaiono dopo mezzo secondo di hover invece che dopo il lungo ritardo di default di sistema;
- il separatore delle migliaia compare anche nei numeri a quattro cifre;
- nel pannello del mese di Entrate i nomi lunghi dei clienti non vengono più troncati.

### Bug fix

**Stati di clienti, progetti e attività si disallineavano:**

- ora lo stato di un progetto segue i suoi periodi di attività: badge, selettore e filtri riportano sempre lo stesso stato, mentre prima potevano essere in disaccordo;
- ora quando metti in pausa, chiudi o riattivi un cliente, l'app ti chiede se applicare la scelta anche ai suoi progetti, e quando lo riattivi puoi lasciare i progetti in pausa;
- ora lo stato di un'attività collegata a una fattura lo decide sempre la fattura: non rischi più di trovarlo diverso a seconda della pagina in cui lo guardi.

**Aliquota dell'imposta sostitutiva:**

- l'app applicava a tutti gli anni l'aliquota valida oggi: chi aveva aperto la partita IVA da più di cinque anni vedeva gli anni agevolati calcolati al 15% invece che al 5%. Ora ogni anno usa l'aliquota che gli spetta.

**Scadenze fiscali nei giorni festivi:**

- le scadenze che cadono in un giorno festivo slittano al primo giorno lavorativo, come già succedeva per sabato e domenica, per tutti gli enti. Nel calendario c'è anche il 4 ottobre, festivo dal 2026.

**Incassato dei progetti:**

- nei progetti a ore l'incassato non teneva conto delle fatture collegate alle attività, e le note di credito entravano nel dovuto con il segno sbagliato. Ora l'incassato è corretto e coincide tra lista, pagina e pannello laterale del progetto, mentre prima il pannello ne mostrava uno diverso;
- nei progetti a corpo le quote delle attività sono arrotondate al centesimo, così le somme tornano anche a video.

**Importi delle attività:**

- se davi il prezzo a un progetto a ore dopo aver importato le attività, queste restavano a 0 €. Ora l'importo segue sempre ore e tariffa, comunque modifichi il progetto o l'attività;
- il costo di riferimento di un'attività nuova compare subito, mentre prima restava vuoto fino al riavvio dell'app.

**Fatture scadute e da incassare:**

- una fattura senza scadenza, o già stornata per intero, non risulta più scaduta, e il giorno della scadenza non conta ancora come ritardo;
- una nota di credito non compare più tra le fatture in attesa di incasso.

**PDF (copia di cortesia) delle fatture con bollo:**

- il PDF riportava un imponibile di 2 € più basso della somma delle voci. Ora l'imponibile è corretto, e il bollo non compreso nel totale compare come nota sotto il Totale, così i conti tornano anche a colpo d'occhio.

**Anni vuoti in Rendicontazione e Fatture:**

- il selettore mostra solo gli anni che contengono voci. Prima, su un anno vuoto, la pagina ti invitava ad aggiungere la prima attività anche se ne avevi centinaia negli anni precedenti. Quando crei una voce o la raggiungi da un link, l'app ti porta all'anno giusto e te la mostra selezionata.

**Coefficiente di redditività:**

- quando togli la modifica manuale, l'app torna al coefficiente del tuo codice ATECO invece di continuare a usare il valore manuale.

**Investimenti da ribilanciare:**

- la Dashboard segnala gli stessi investimenti da ribilanciare della pagina Portafoglio, con la stessa soglia che hai impostato.

**Import da CSV:**

- un valore che non è un numero non diventa più 0 in silenzio: l'app scarta la riga e te la segnala. Le istruzioni sulle percentuali ora coincidono con l'esempio.

**Distribuzione:**

- la configurazione della Distribuzione delle entrate è una sola, impostata di partenza con le tasse al 24,9%. Prima Parametri, Conti ed Entrate potevano usarne di diverse, e il profilo rischiava di duplicarsi.
