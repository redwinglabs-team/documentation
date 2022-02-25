# Contabilità

## Modifica le tue preferenze contabili

Personalizza l’aspetto dei tuoi conti, scegli un contatore personalizzato per le tue ricevute e molto altro.

 1. Dal Menu principale vai a Impostazioni > Contabilità 
 2. Clicca su Configurazione
 3. Aggiorna tutti i campi rilevanti
 4. Clicca su Salva

#### Dettaglio dei campi di configurazione

 * Opzioni: 
    * Consenti modifica dei conti chiusi: Consente la riassegnazione e la modifica dei conti dopo la loro chiusura
    * Mostra il nome dell’impiegato nel conto: i conti e le fatture mostreranno il nome dell’impiegato che le ha emesse
    * Abilita la chiusura automatica dei conti ribassati: le fatture con degli articoli stornati vengono chiuse automaticamente. Quando si storna un articolo che ha superato il tempo di consumo regolamentato al di fuori della FCCM (vedi sotto), il sistema sposterà automaticamente l’articolo e la corrispondente voce su una nuova fattura aperta, che verrà poi chiusa automaticamente se bilanciata. Quando invece si annulla un articolo su una fattura già saldata, il sistema creerà automaticamente un articolo di sconto e lo inserirà in una nuova fattura aperta; tuttavia il sistema non chiuderà automaticamente questa fattura perchè deve essere prima bilanciata manualmente.
    * Dettagli facoltativi per il pagamento con carta di credito: non richiede i dati identificativi della ricevuta quando si inviano pagamenti con carta da terminale (procedura utilizzata per snellire il processo di check-in e check-out)
    * Tracciamento dei crediti abilitato: consente la tracciabilità dei pagamenti per le fatture in sospeso e le rispettive scadenze
    * Richiedere l’impostazione della categoria di contabilità: richiede che tutti i prodotti e i servizi siano collegati a una categoria contabile al momento della creazione
    * Depositi separati sulla fattura: aggiunge una sezione separata su tutte le fatture dedicata ai depositi effettuati
 * Precisione fiscale: Inserisci il numero di cifre decimali utilizzate per il calcolo delle imposte. A seconda delle tue preferenze contabili, potete anche scegliere un numero più alto per una maggiore precisione nel calcolo delle imposte. Lascia vuoto questo campo per utilizzare la precisione di arrotondamento predefinita, definita dalle monete e dalle banconote disponibili nella vostra valuta contabile. Se cambi la tua precisione fiscale, ne risentiranno solo i calcoli effettuati successivamente alla modifica.
 * Finestra di cronologia contabile modificabile (FCCM): la FCCM è un'impostazione che determina quanto indietro nel tempo è possibile modificare le voci contabili. Questa finestra consente di modificare solo le voci delle fatture non ancora chiuse. Le voci su fatture già chiuse non possono essere modificate in alcun modo, per correggerle infatti, è necessario creare uno storno per quella fattura.
 * Tipi di pagamento esterno: Scegli quali tipi di pagamento esterno vuoi accettare presso la tua struttura
 * Tipi di carta manuale accettate: Scegli quali tipi di carta vuoi accettare tramite il terminale di pagamento
 * Chiusura del conto: 
    * Sempre consentito: consente la chiusura delle fatture in qualsiasi momento, anche se le voci della fattura non sono ancora state consumate (in caso d soggiorni futuri)
    * Solo con articoli consumati: permette la chiusura delle fatture solo quando gli articoli in essa contenuti sono stati consumati. N.B. se selezioni questa opzione, non potrai chiudere un conto con degli articoli acquistati durante il soggiorno fino al giorno della partenza.
    * Solo con articoli consumati a mezza giornata: consente la chiusura dei conti solo fino a 12 ore prima del consume degli articoli in esse contenuti. N.B. se selezioni questa opzione, non potrete chiudere una fattura con gli articoli di soggiorno fino al giorno della partenza. 
 * Intervallo di fatturazione: Inserisci il numero di giorni dopo l’emissione di una fattura entro il quale deve essere saldata.
 * Codici tariffari: Inserite un codice per ogni tariffa per mapparla sul tuo software di contabilità esterna
 * Contatore di fatture predefinito: Scegli il contatore che vuoi applicare automaticamente a ogni fattura. N.B. puoi sempre selezionare un contatore diverso al momento della revisione della fattura se necessario
 * Pagamento contante: Seleziona la categoria contabile per i pagamenti in contante
 * Pagamento fatture: seleziona la categoria contabile per i pagamenti delle fatture 
 * Pagamento con carta non specificato: Seleziona la categoria contabile per qualsiasi pagamento con carta effettuato tramite terminale
 * Spese aggiuntive: Seleziona le categorie contabili per le spese aggiuntive, incluse le spese di cancellazione e la tassa di soggiorno
 * Pagamenti da terminale: Seleziona le categorie contabili per i pagamenti effettuati con determinati tipi di carte tramite terminale
 * Pagamenti dal portale: Seleziona le categorie contabili per i pagamenti effettuati con determinati tipi di carte tramite portale (es. Stripe)
 * Pagamenti esterni: Seleziona le categorie contabili per ogni tipo di pagamento esterno accettato presso la tua struttura
 * Intestazione del conto: Inserisci la tua intestazione personalizzata in html, che apparirà in cima a tutti i conti
 * Piè di pagina del conto: Inserisci il tuo piè di pagina personalizzato in html, che apparirà in fondo a tutti i conti
 * Margine di stampa superiore per i conti: Scegli quanto grande vuoi che sia il margine superiore (in millimetri)
 * Margine di stampa laterale per i conti: Scegli quanto grande vuoi che siano i margini sinistro e destro (in millimetri)
 * Margine di stampa inferiore per i conti: Scegli quanto grande vuoi che sia il margine inferiore (in millimetri)

## Creare una categoria contabile

Imposta le categorie contabili per tenere traccia dei tuoi ricavi

### Se non usi un software di contabilità’ esterno 

Se non si utilizza un software di contabilità esterno, non è necessario impostare alcun codice con la categoria di contabilità

 1. Dal menu principale vai a Impostazioni > Contabilità
 2. Clicca Categorie
 3. Clicca sul bottone +
 4. Inserisci il nome della categoria contabile
 5. Sotto codice, è possibile inserire un identificativo per il tracciamento interno nel channel manager
 6. Clicca Crea

### Se si utilizza un software di contabilità esterno

Se disponi di un software di contabilità esterno, è possibile impostare codici aggiuntivi:

 * Condividi i dati contabili nel channel manager con il tuo software di contabilità esterno (e viceversa)
 * Collega la categoria contabile ad un centro di costo
 * Utilizza la contabilità a partita doppia per tenere traccia degli addebiti e degli accrediti

### Categorie contabili raccomandate

Gli International Financial Reporting Standards (IFRS) raccomandano le seguenti categorie contabili per la rendicontazione dei ricavi del turismo, dell’ospitalità e del tempo libero:

 * Alloggio:
    * Ricavo dalla camera
    * Ricavo dalla cancellazione
    * Deposito
    * Sconto
    * Late check-out
 * Alimenti e bevande:
    * Bar
    * Minibar
    * Negozio
 * Pagamenti:
    * Pagato
    * Contante
    * Visa
    * masterCard
    * American Express
    * Altri CC
    * Bonifico bancario
 * Varie:
    * Servizio lavanderia 
    * Parcheggio
    * Spese del servizio
    * Vari
 * Tasse:
    * Tassa di soggiorno

## Crea o cancella una regola di smistamento


## Crea o cancella una cassa

Le casse registrano tutte le transazioni in contanti nel sistema, comprese le transazioni interne e i pagamenti dei conti

### Creare una cassa

 1. Dal menu principale vai a Impostazioni > Contabilità
 2. Fai clic su Cashiers
 3. Fai clic sul pulsante +
 4. Inserisci i dati della cassa
    * Per abilitare la cassa, è necessario abilitare almeno una valuta
    * Per consentire a un dipendente di utilizzare una cassa, è possibile assegnare il dipendente quando si crea / aggiorna la cassa o nel momento in cui si crea / aggiorna il profilo del dipendente
    * Se hai più di una cassa, puoi inserire un numero nel campo Ordinamento per determinare la posizione in cui appariranno le casse
 5. Fai clic su Salva

### Assegnare le responsabilità delle casse

Ciascun dipendente che svolge una mansione legata all’utilizzo di denaro deve essere assegnato ad almeno una cassa. Se un dipendente non è assegnato ad alcuna cassa, gli eventuali pagamenti in contanti in entrata o gli addebiti sui conti degli ospiti non saranno registrati nello storico. Di conseguenza, la cassa avrà un saldo in disavanzo.

Ci sono due modi per impostare la gestione delle casse presso la tua struttura:

 * Crea una cassa per ogni singolo dipendente (es “Cassa di Emilio”) e assegna solo quel dipendente alla cassa in questione. Così facendo, il denaro registrato dovrebbe essere diviso tra i dipendenti, in modo che ogni singola persona sia responsabile di una specifica somma di denaro, oltre che della rendicontazione del proprio denare e della chiusura di cassa alla fine del turno
 * Crea una cassa specifica per un dipartimento (es. “Cassa ricevimento”) e assegna ogni dipendente di quel reparto alla stessa cassa. Questa opzione è certamente meno sicura della precedente, infatti dovrebbe essere utilizzata solamente nelle strutture con una sola persona presente durante il turno

### Cancellare una cassa 

La cassa deve essere in saldo pari per poter essere cancellata. La cancellazione di una cassa non può essere annullata

 1. Dal Menu principale vai a Impostazioni > Contabilità
 2. Fai clic su Cassa
 3. Clicca sull’icona “” della cassa che vuoi cancellare
 4. Fai clic su Elimina
 5. Conferma cliccando nuovamente su Elimina

## Creare o gestire un contatore

È possibile utilizzare i contatori per assegnare automaticamente i numeri alle fatture, ai proforma e agli ordini di servizio

 * Un contatore di conti può essere assegnato sia ai conti che alle fatture
 * Un contatore proforma può essere assegnato al proforma delle fatture 
 * Un contatore di ordini di servizio può essere assegnato agli ordini di servizio, comprese le prenotazioni e gli ordini di prodotti di servizio. N.B. E’ possibile avere un solo contatore di ordini di servizio, quindi non è possibile crearne uno nuovo, ma solo modificare il contatore di ordini di servizio predefinito

N.B. una volta che il conto o la fattura sono stati chiusi, il valore del contatore non può essere modificato in quanto il conto o la fattura chiusa sono documenti fiscali con valore legale.

### Creare un contatore

Uno per ciascun tipo di contatore viene creato di default al momento della creazione della tua struttura, ma [ possibile comunque personalizzare i contatori per i tuoi conti, fatture e proforma in modo che ognuno abbia il proprio numero univoco

1. Dal Menu principale vai a Impostazioni > Contabilità
2. Clicca su Contatori
3. Fai clic sul pulsante +
4. Scegli il tipo di contatore che si desidera creare
5. Completa i campi
6. Fai clic su Salva

#### Dettaglio dei campi di un contatore

* Nome: inserisci il nome del contatore di banconote
* Valore: inserisci il numero dal quale il contatore di banconote inizierà a contare
* Formato del numero (prefisso): Imposta un numero di prefisso per il tuo contatore di banconote, utilizzando i segnaposto per avvisare il sistema della formattazione. Ad esempio, se si vuole prefissare il numero del contatore con ‘2000’, si deve inserire “2000[0:0000]”
* Titolo: inserisci il titolo del conto per le tue esportazioni contabili
* Codice (del tipo di conto): Inserisci il codice del tipo di conto, se necessario, per le tue esportazioni contabili. N.B. questo campo è visibile solamente quando si crea un contatore di conti

### Gestione dei contatori

Dopo aver creato un contatore, è possibile:

* Rendere il contatore come predefinito per il suo tipo, in modo che venga applicato automaticamente alla creazione di un conto o di una fattura
* Azzerare il valore del contatore
* Aggiornare le impostazioni
* Cancellare il contatore

I contatori possono essere resettati al massimo ad 1, quindi se vuoi che i tuoi contatori partano da un numero diverso devi creare un nuovo contatore e impostarlo come predefinito. Tuttavia, non consigliamo di azzerare i tuoi contatori, in quanto potrebbe causare la duplicazione dei numeri dei conti. 

## Imposta i tuoi tassi di cambio

Puoi impostare la tua struttura assegnandole tutti i tassi di cambio che desideri, ma quando configuri le impostazioni generali della tua struttura, devi scegliere una valuta predefinita.

1. Dal menu principale vai a Impostazioni > Contabilità
2. Clicca su Tassi di cambio
3. Clicca il bottone +
4. Nel campo Valuta seleziona la valuta che ti interessa aggiungere 
5. Clicca su Salva
    * Sarai reindirizzato alla lista dei tuoi tassi di cambio attivi
6. Sotto la colonna A, inserisci il valore della valuta che hai appena aggiunto rispetto alla tua valuta predefinita.
Ad esempio, sela tua valuta attuale è “ABC”, e state aggiungendo un tasso di cambio per “XYZ”, si potrebbe inserire 2 sotto la voce alla colonna ABC
7. Seleziona la casella di controllo nella colonna E’ accettato per abilitare la valuta

Consiglio: Fai clic sui pulsanti freccia per invertire il tasso di cambio tra le due colonne

### Gestione dei tassi di cambio

Dopo aver impostato i tassi di cambio, è necessario tenerli aggiornati per evitare discrepanze. Dovresti quindi, alternativamente: 

* Aggiornare manualmente i tuoi tassi di cambio almeno una volta al mese
* Connetterti all’integrazione del provider del tasso di cambio, che aggiornerà automaticamente i tassi di cambio per te.

Tra il momento in cui una prenotazione viene creata, e il momento in cui viene saldata, i tassi di cambio possono variare. Se il gruppo tariffario della prenotazione ha la liquidazione automatica abilitata, il tasso di cambio sarà ancorato al momento della creazione. In caso contrario, una modifica sarà inviata al conto dell’ospite.
