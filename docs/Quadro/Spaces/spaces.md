# Spaces

## Report delle camere

Per vedere la sezione vai a Menu Principale > Spaces.

La sezione Spaces può essere usata dal reparto housekeeping e dai manager per avere sempre sotto controllo lo stato della pulizia delle camera nella tua struttura. Un riassunto schematico dei dati presenti in questa sezione è presente anche nella Dashboard di Quadro

Di seguito trovi una descrizione dettagliata di tutte le funzioni e i filtri disponibili in questa sezione

### Assegnazione housekeeping

All’interno della parte superiore della pagina, a destra, è situato il bottone di assegnazione, che rappresenta una delle caratteristiche più importanti di questa sezione:

* Assegnazione dipendenti: questo bottone ti permette di assegnare in maniera uniforme le camere ai dipendenti del reparto housekeeping in servizio presso la tua proprietà

Una volta cliccato il bottone, si aprirà il form di assegnazione, dove dovrai compilare i seguenti campi:

* Impiegati: seleziona quali impiegati assegnare a determinate camere. Se vengono selezionati diversi dipendenti, le camere verranno distribuite tra loro in modo uniforme. Nota che ogni spazio può essere assegnato ad un dipendente
* Tipologia di spazio: seleziona quale tipologia di spazio assegnare ai dipendenti. 

N.B. Mettere una camera Fuori servizio non limiterà la sua disponibilità all’interno del precedente form, ma metterla Guasto lo farà.

Clicca il bottone Assegna una volta aver controllato tutti i campi inseriti e aspetta la notifica di successo dell’operazione

Fatto ciò, verrai indirizzato nuovamente nella sezione di gestione delle camere, dove vedrai i dettagli appena inseriti. 

### Filtri

In cima alla pagina sono presenti diverse opzioni che puoi selezionare al fine di gestire al meglio la visione del report: 

* Date: seleziona una data per restringere la ricerca al giorno selezionato. Il filtro data sarà automaticamente compilato con la data odierna
* Assignee: seleziona il dipendente dal menu a tendina per restringere i risultati alle sole camere assegnate a quel dipendente
* Status: restringe la ricerca delle camere al loro stato di pulizia
    * Pulita
    * Sporca
    * Ispezionata
    * Guasta
    * Fuori servizio
* Categoria di spazio: restringe la ricerca alle sole camere appartenenti a quella categoria di spazio

### Funzionalità

Il report delle camere è organizzato, di norma, come una lista di tutti gli spazi ordinati per piano. Utilizza i filtri a disposizione per modificare la vista della pagina e l’ordine degli spazi.
Ogni camera è seguita da un menù a tendina dal quale è possibile modificarne lo stato.
La funzione primaria è la rappresentazione in tempo reale delle prenotazioni attuali e future, con la linea verticale tratteggiata posta a indicare l’ora attuale.
Ogni prenotazione mostra le seguenti informazioni:

* Data o ora di arrivo: se l’arrivo è previsto nello stesso giorno, verrà mostrato anche l’orario, in caso contrario verrà mostrata solo la data
* Numero pax: numero degli ospiti previsti per la prenotazione
* Nome dell’ospite: clicca sul nome dell’ospite per collegarti direttamente al suo profilo utente
* Data o ora della partenza: se la partenza è prevista nello stesso giorno, verrà mostrato anche l’orario, in caso contrario verrà mostrata esclusivamente la data

Le prenotazioni per Uso Interno o le camere bloccate per Guasto verranno mostrate con i seguenti dettagli:

* Data o ora di inizio: se l’inizio è previsto nello stesso giorno, verrà mostrato anche l’orario, in caso contrario verrà mostrata solo la data
* Nome: nome inserito al momento della creazione. Esso può essere una breve descrizione del problema o la ragione della prenotazione
* Data o ora di fine: se la fine è prevista nello stesso giorno, verrà mostrato anche l’orario, in caso contrario verrà mostrata solo la data

Inoltre, i prossimi eventi verranno visualizzati con un'icona a forma di fulmine, a indicare che gli ospiti arriveranno presto e che tutti gli accordi finali dovrebbero essere completati con urgenza.

### Guasto

Mettere una camera in Guasto è una decisione importante che dovrebbe essere presa almeno da un supervisor.  Una camera in Guasto sarà esclusa dall’inventario e non potrà essere prenotata per tutta la durata del periodo selezionato. Lo staff dovrebbe utilizzare questo stato solamente nel caso non ci siano altre opzioni.

### Impostare lo stato in Guasto

Clicca sul numero della camera che vuoi mettere in Guasto, dopodichè clicca sul Bottone Guasto. Apparirà una schermata con i seguenti campi da compilare:

* Nome del blocco: inserisci una breve descrizione del problema
* Assegnazione spazio: questo campo verrà automaticamente compilato con il numero di camera su cui hai cliccato in precedenza. Puoi comunque selezionare una diversa opzione dal menu a tendina
* Inizio: seleziona l’ora e la data di inizio del blocco
* Fine: seleziona la data e l’ora di fine del blocco e l’automatica rinnovata disponibilità della camera. Ricorda che lo stato della camera verrà cambiato automaticamente in Sporca alla fine del blocco
* Note: è importante includere la ragione per il quale si sta ponendo il blocco alla camera in questione così da poter informare tutto lo staff. Puoi anche includere qualsiasi altra informazione riguardante il problema

Clicca sul bottone Crea. i dettagli relativi al blocco verranno elencati nel tableau delle camere. Puoi modificare in qualsiasi momento le informazioni in esso contenute cliccando sul nome del blocco.
Nota bene che se uno spazio padre viene segnato come guasto, automaticamente anche tutti gli spazi in esso contenuti verranno bloccati allo stesso tempo.

### Cambiamenti automatici

#### Utilizzo interno e Guasto

Quando una camera è prenotata per uso interno o Guasto, l’utente deve specificare sia la data di inzio che quella di fine, informazioni che saranno visibile nella Timeline. Una volta giunta la data e l’ora di fine del blocco, lo stato della camera passerà automaticamente su Sporca.

#### Vacante

Se una camera non risulta occupata per più di sette giorni consecutivi, il suo stato passerà automaticamente in Sporca per ricordare ai dipendenti dell’housekeeping che è necessario pulire le zone bagno.

#### Occupato

Ogni notte, il sistema cambierà automaticamente lo stato di tutte le camere occupate in Sporca

#### Cambio camera

Quando sposti una prenotazione che ha già effettuato il check-in da una camera ad un’altra, lo stato di entrambe le camere verrà cambiato in Sporca, includendo una nota che cita “Cambio camera”. 

#### No show

In caso di no show di una prenotazione, lo stato della camera non passerà più a Sporca durante la notte. Ciò si basa sul presupposto che nessuno abbia preso possesso di quella camera e quindi non c’è alcun motivo per cambiare il suo stato in sporca.
