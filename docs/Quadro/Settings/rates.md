# Tariffe

## Creare o modificare un gruppo tariffario

<iframe width="560" height="315" src="https://www.youtube.com/embed/MY7SZ40yVQw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

E’ consigliato raggruppare le tariffe quando possiedono la medesima politica di cancellazione. Dopo aver creato un gruppo di tariffe, è possibile creare la sua politica di cancellazione

### Creare un gruppo tariffario

1. Dal Menu principale vai a Impostazioni > Tariffe 
2.  Clicca Gruppi tariffari
3. Clicca il bottone +
4. Scegli come regolare le tariffe di questo gruppo
5. Inserisci tutti gli altri dettagli del gruppo tariffario
6. Clicca Crea

#### Dettaglio dei campi di un gruppo tariffario

* Nome: Inserisci un nome per il gruppo tariffario
* Nome abbreviato: Inserisci un nome abbreviato per i posti dove lo spazio è limitato
* Descrizione: Inserisci una breve descrizione del gruppo tariffario per uso interno
* Regolamento (liquidazione): 
    * Automatico: Seleziona per addebitare automaticamente i pagamenti quando le informazioni della carta sono disponibili
    * Manuale: Seleziona se desideri che i dipendenti elaborino e liquidino manualmente i pagamenti
* Azione regolamento (azione di liquidazione):
    * Addebito carta di credito: Seleziona se desideri che la liquidazione sulla carta di credito inserita a sistema sia automatica
    * Crea preautorizzazione: Seleziona desideri chiedere una preautorizzazione sulla carta di credito inserita a sistema quando la liquidazione è automatica. N.B. non verrà effettuato alcun addebito sulla carta fino a quando la transazione non verrà elaborata manualmente da un dipendente
* Regolamento trigger (attivazione della liquidazione): Seleziona il momento in cui il sistema deve effettuare la liquidazione (in caso di liquidazione automatica), o creare una finestra di utilizzo per la liquidazione effettuata dai dipendenti (in caso di liquidazione manuale) N.B. per la creazione di una finestra di utilizzo per la liquidazione è necessario prima selezionare  Crea compito di liquidazione nel campo Opzioni
* Regolamento Offset (Compensazione della liquidazione): Inserisci un lasso di tempo opzionale per regolare l’attivazione della liquidazione (es. Inserendo “+1 giorno”, la liquidazione avverrebbe 1 giorno dopo rispetto alla data di liquidazione prevista). Disponibile solo per la liquidazione automatica
* Valore regolamento (valore della liquidazione): Inserisci la percentuale del prezzo totale che desideri venga addebitata al momento della liquidazione (disponibile solo per la liquidazione automatica). Se necessiti la creazione di pre autorizzazioni per spese extra in caso di danni, puoi inserire come valore anche più del 100%.  In fase di check-out, sarà possibile addebitare un importo pari alla somma richiesta nella pre autorizzazione.
* Valuta di regolamento (valuta della liquidazione): Inserisci la valuta in cui vuoi che le liquidazioni siano gestite (in caso di liquidazione automatica). 
* Numero massimo di notti per il regolamento (notti massime per la liquidazione): Inserisci il numero massimo di notti che possono essere addebitate automaticamente (in caso di liquidazione automatica)
* Estensione: Seleziona quali spese devono essere incluse nel sistema di liquidazione automatica
* Opzioni:
    * Liquidazione automatica del deposito: 
        * I depositi verranno automaticamente inseriti sui conti dei clienti
        * Il conto su cui sono inseriti verrà chiuso al momento della liquidazione. In caso fossi legalmente obbligato a pagare le tasse al momento del pagamento, seleziona questa opzione
    * Crea un modulo di liquidazione: crea automaticamente un modulo (per il dipendente o il suo responsabile) per procedere con il pagamento al momento della liquidazione (se la liquidazione è manuale) o quando la liquidazione non va a buon fine (se la liquidazione è manuale)
* Ordinamento: Scegli l’ordine in cui volete che i vostri gruppi tariffari siano elencati
* Aggiungi traduzione: Inserisci la lingua per il quale inserire la traduzione dei campi visibili agli ospiti

### Modifica un gruppo tariffario

1. Dal Menu principale vai a Impostazioni > Tariffe
2. Clicca sul gruppo tariffario che desideri modificare 
3. Aggiorna i dettagli del gruppo tariffario
4. Clicca salva

## Crea, cancella o modifica una tariffa

<iframe width="560" height="315" src="https://www.youtube.com/embed/fL_gTdj1c_4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Prima di poter creare una tariffa, è necessaria la creazione di un gruppo tariffario

### Crea una tariffa

1. Dal Menu principale vai a Impostazioni > Tariffe
2. Clicca su Tariffa
3. Clicca il bottone +
4. Spunta la casella E’ abilitato per rendere disponibile questa tariffa
5. Scegli se la tariffa debba essere pubblica o privata 
    * Le tariffe pubbliche sono visibili a chiunque e possono essere prenotate da qualsiasi canale collegato
    * Le tariffe private non possono essere prenotate tramite Quadro o il booking engine, a meno che non siano connesse a un voucher. Le tariffe private possono anche essere prenotate attraverso alcuni canali di distribuzione a patto che siano integrate con un channel manager
6. Inserisci i dettagli della tariffa
7. Clicca Salva

#### Dettaglio dei campi di una tariffa

* Data inizio: imposta la data di inizio di validità della tariffa
* Data fine: imposta la data della fine di validità della tariffa
* Nome: Inserisci un nome per uso interno
* Nome abbreviato: Inserisci un nome abbreviato che verrà utilizzato nei posti con spazio limitato
* Descrizione: Inserisci qualsiasi informazione rilevante di questa tariffa che verranno visualizzate nel booking engine
* Nome esterno: Inserisci un nome che verrà visualizzato dai clienti nelle mail e nel booking engine
* Gruppo tariffario: Seleziona il gruppo tariffario di cui fa parte questa tariffa
* Tipo: Scegli se la tariffa deve essere pubblica o privata. Nota: le tariffe private non possono essere prenotate tramite il Comandante o il Distributore a meno che non siano collegate a un voucher
* Tariffa base: Se vuoi creare una tariffa sulla base di una già esistente, seleziona la tariffa di riferimento. Se stai creando invece una tariffa indipendente, ignora questo campo
* Categoria account (categoria di contabilità): seleziona una categoria di contabilità per questa tariffa
* Segmento: Seleziona il segmento che verrà assegnato automaticamente ai clienti che utilizzano questa tariffa
* Politica di cancellazione: Seleziona la politica di cancellazione per questa tariffa
* Ordinamento: Scegli la posizione che vuoi che questa tariffa occupi in un elenco di tutte le tariffe
* Aggiungi traduzione: Inserisci la lingua per il quale inserire la traduzione dei campi visibili agli ospiti

### Assegna il valore a una tariffa

Dopo aver creato il tariffa, è possibile modificare il valore utilizzando alcuni campi aggiuntivi:

1. Aggiorna i nuovi campi per determinare il prezzo della tariffa.
2. Clicca Salva.

#### Se la tariffa non è collegata ad una tariffa di base

Vedrai i seguenti campi:

* Valuta: Scegli in quale valuta verrà addebitato questa tariffa. 
* Prezzo: Inserisci il prezzo che verrà addebitato ogni notte.  
* Aliquota fiscale: Seleziona l'aliquota fiscale che verrà applicata. 
* Modifica per il letto vuoto: Applica un adeguamento del prezzo per i pernottamenti quando lo spazio prenotato con questa tariffa non è del tutto esaurito.  
* Modifica per il letto supplementare: Applica un adeguamento del prezzo per i pernottamenti quando lo spazio prenotato con questa tariffa supera la capienza. 

#### Se la tariffa è collegata ad una tariffa di base

Vedrai i seguenti campi:

* Modifica relativa: Inserisci un importo percentuale la tariffa di base, che determinerà il prezzo notturno di questa tariffa. Per esempio: Se il prezzo notturno della tua tariffa di base è 100, e inserisci "-10", il prezzo notturno della tua tariffa sarà 90. 
* Modifica assoluta: Inserisci un importo, che verrà aggiunto o sottratto al prezzo notturno della tariffa di base per determinare il prezzo notturno di questa tariffa. Ad esempio, se il prezzo notturno della tua tariffa di base è 90 e inserite "-10", il prezzo notturno della tua tariffa sarà 80.

### Modifica una tariffa

1. Dal menu principale vai a Impostazioni > Tariffe
2. Clicca su Tariffa
3. Clicca sulla tariffa che vuoi aggiornare
4. Nella scheda Generale, aggiorna i dettagli della tariffa
5. Clicca su Salva

### Cancella una tariffa

Se non si desidera cancellare definitivamente una tariffa, è possibile solamente disattivarla, per renderla non disponibile ai clienti che effettuano una prenotazione

1. Dal menu principale vai a Impostazioni > Tariffe 
2. Clicca su Tariffa
3. Clicca l’icona “” sulla tariffa che desideri rimuovere
    * Per disattivare la tariffa e renderla temporaneamente non disponibile ai clienti, clicca su Modifica e successivamente deseleziona la casella di controllo Abilita e fai clic su Salva
    * Per cancellare definitivamente una tariffa invece, clicca su Elimina e conferma cliccando nuovamente su Elimina
