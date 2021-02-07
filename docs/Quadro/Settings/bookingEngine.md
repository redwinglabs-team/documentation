# Booking engine

## Configurare il Booking Engine

Configura il booking engine dal sistema e aggiungilo al tuo sito web, in modo che i clienti possano effettuare la loro prenotazione direttamente con te.

### Step 1: Termini e Condizioni

Prima di iniziare a utilizzare il booking engine,  bisogna determinare quali sono i termini e le condizioni della tua struttura, in conformità agli standard del tuo fornitore del portale di pagamento (es. Stripe).
1. Dal Menu principale vai a Impostazioni > Stay
2. Clicca sul servizio di Stay
3. In Opzioni, inserisci un indirizzo o HTML per i Termini e Condizioni. E’ necessario compilare solamente uno di questi due campi.
4. Clicca su Salva

### Step 2: Configura il tuo booking engine

Puoi creare molteplici configurazioni del tuo booking engine

1. Dal Menu principale vai a Impostazioni > Booking Engine
2. Clicca sul bottone +
3. Inserisci il nome della configurazione e clicca su Crea
4. Completa tutti i campi rilevanti
5. Clicca su Salva

#### Dettaglio dei campi di una configurazione del Booking Engine

* Nome: se desideri modificare il nome inserito precedentemente, inseriscilo qui (uso esclusivamente interno)
* Inserimento del pagamento con Carta: scegli come verranno gestite le carte di pagamento nel booking engine. 
* Non richiesto: non richiede le informazioni sulla carta per il pagamento (non ci sarà alcun campo per poter inserire la carta di pagamento)
* Richiesto: include un campo per consentire ai clienti di inserire i dati della loro carta, ma non si desidera che i dati della carta siano convalidati (se i dati inseriti non sono corretti, la prenotazione verrà creata comunque)
* Obbligatorio: include un campo per consentire ai clienti di inserire i dati della loro carta, convalidandola prima che la prenotazione possa essere confermata
* Lingua: scegli la lingua predefinita per il booking engine
* Valuta: scegli la valuta nel quale il pagamento verrà addebitato al cliente (se non viene selezionata alcuna valuta, verrà utilizzata quella predefinita)
* Inizio compensazione: scegli un numero di giorni dopo il giorno in cui il cliente sta prenotando che sarà selezionato come data di inizio predefinita. Se si lascia il campo vuoto, il valore predefinito sarà 0.
* Fine compensazione: scegli un numero di giorni dopo il giorno in cui il cliente sta prenotando che sarà selezionato come data di fine predefinita. Se si lascia il campo vuoto, il valore predefinito sarà 2
* Numero di adulti: scegli il numero di adulti che deve essere selezionato come predefinito
* Numero bambini: scegliere il numero di bambini che deve essere selezionato come predefinito
* Codice Voucher: inserisci uno dei tuoi codici voucher utilizzare nel campo Promozioni come predefinito
* Mostra codice Voucher: scegli se i tuoi codici voucher devono essere elencati nel booking engine
* Mostra richieste speciali: scegli se includere o meno un campo che permetta agli ospiti di aggiungere richieste speciali alla loro prenotazione
* Una volta compilato, questa informazione sarà elencata nelle note di prenotazione (il campo di richiesta speciale è incluso come predefinito)
* Mostra il confronto delle tariffe: scegli se mostrare un banner di confronto delle tariffe sotto le vostre categorie di spazio. Il banner mostrerà la tua tariffa, l’URL di ogni agenzia di viaggio che inserisci nell’apposito campo  apposito, e la tariffa di quell’agenzia di viaggio. Il banner di confronto delle tariffe non sarà incluso come valore predefinito
* Mostra disponibilità: scegli se mostrare la disponibilità della tua struttura accanto alla massima occupazione in ogni categoria di spazio 
* Selezione del bambino abilitata: scegli se includere l’opzione di aggiungere bambini alle prenotazioni (i bambini sono accettati nelle prenotazioni come valore predefinito)
* Agenzie di viaggio online: se hai selezionato Sì nel campo Visualizza confronto tariffe, inserisci l’URL delle agenzie di viaggio che vuoi mostrare nel banner di confronto tariffe
* Descrizione della tariffa del concorrente: Inserisci le caratteristiche che differenziano la tua prenotazione online della concorrenza (es. Colazione inclusa). Assicurati di creare una nuova linea per ogni funzione
* Modifica relativa del prezzo concorrente: inserisci la percentuale con il quale mostrare i prezzi del tuo concorrente (elencati nel banner di confronto delle tariffe se hai selezionato Si nel campo “mostra confronto tariffe”) rispetto al tuo BAR.
* URL del video introduttivo: Inserisci l’URL di un video che deve essere mostrato quando un cliente apre il booking engine (questo deve collegarsi a un video in formato MP$ su una pagina web basata su cloud, e non può collegarsi a video provenienti da YouTube, Vimeo o altre piattaforme di condivisione video)
* Id di Google Tag Manager: inserisci il GTM container ID al quale vuoi che vengano inviati tutti gli eventi del booking engine. GTM consente di collegare il motore di prenotazione del booking engine a un sistema di tracciamento, come Google Analytics. Una volta impostato, è possibile utilizzare la modalità anteprima per aiutare a visualizzare i dati raccolti sull’attività dell’utente durante il processo di prenotazione
* Tema: Scegli la combinazione di colori che desideri nel Distributor
* Campi richiesti: scegli se il campo telefono sia obbligatorio o opzionale
* Colore primario: scegli il colore principale che verrà mostrato nel booking engine (questo deve essere formattato in un codice esadecimale)

### Step 3: Mappa le tue categorie dello spazio

Tutte le categorie di spazio sono elencate con valore predefinito nel booking engine, quindi è necessario mappare le categorie di spazio solo se ce ne sono alcune che non vuoi elencare

N.B. quando crei nuove categorie di spazio nel channel manager, non dimenticare di mapparle. In caso contrario non saranno elencate nel tuo booking engine)

1. Nella configurazione del booking engine, clicca su Mappature della categoria
2. Clicca sul bottone +
3. Sotto Categoria, seleziona la categoria di spazio che vuoi mappare nel booking engine
4. Nel campo Ordine, scegli l’Ordine in cui desideri che le tue categorie di spazio siano elencate nel booking engine
5. Clicca su Salva

### Ottimizzare il tuo booking engine

Tutte le informazioni elencate nel Booking engine sono tratte dal channel manager, quindi è importante che ogni aspetto del tuo servizio di Stay sia completamente configurato con i dettagli rivolti al cliente, in particolare:

#### Categorie di spazio

Assicurati che i seguenti campi siano compilati per ogni categoria di spazioelencata nel booking engine:

* Conteggio dei letti ordinario
* Capienza extra
* Descrizione
* Immagine
* Ordina modello di e-mail

#### Tariffe 

Assicurati che i seguenti campi siano pubblicati per ogni tariffa pubblica:

* Nome 
* Descrizione
* Nome esterno

N.B. Solo le tariffe più economiche di ogni gruppo tariffario sono elencate nel booking engine

#### Prodotti

Solo i prodotti collegati al tuo servizio di Stay sono elencati nel booking engine. Assicurati che i seguenti campi siano compilati per ogni prodotto allegato al tuo servizio di Stay:

* Nome
* Descrizione
* Nome esterno
