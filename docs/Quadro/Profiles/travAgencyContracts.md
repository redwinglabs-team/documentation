# Settare un’Agenzia di viaggio

Dopo aver settato un’agenzia di viaggio creandone un profilo e un contratto, Quadro è capace di individuare automaticamente nuove prenotazioni in ingresso da quella determinata agenzia di viaggio e gestiscile esattamente come preferisci.

N.B. Alcuni channel manager inviano le prenotazioni sia alla compagnia (il luogo di lavoro dell’ospite) e l’Agenzia di viaggio ad esso collegata. Controlla prima se il tuo channel supporta questa funzione.

### Step 1: Crea un profilo per l’Agenzia di viaggio

1. Dal Menu principale vai a Profili > Agenzie di Viaggio
2. Clicca sul bottone +
3. Inserisci il nome dell’Agenzia di viaggio
4. Compila tutti gli altri campi rilevanti
5. Clicca su Salva

### Step 2: Mappa il profilo dell’Agenzia di viaggio

Se stai usando un channel manager, è importante mappare i profili delle agenzie di viaggio. Quadro rileverà automaticamente le prenotazioni effettuate dalle agenzie e ne applicherà le condizioni dettate dal contratto di collaborazione.

#### Metodo 1: Utilizza la dropdown del campo “Canale” (consigliato)

Consigliamo di provare questo metodo prima di passare ad un altro.

1. Apri il profilo dell’Agenzia di viaggio che hai appena creato
2. Alla voce “Canale” cerca l’OTA, il GDS o l’agenzia di viaggio a cui è destinato il profilo.  Se non la trovi, dovrai richiedere le informazioni sulla mappatura direttamente al tuo channel manager.
3. Clicca su Salva

Se non riesci a mappare l’agenzia di viaggio con la dropdown del campo “Canale”, richiedi le informazioni di mappatura al tuo channel manager e prova uno dei metodi riportati di seguito

#### Metodo 2: Utilizza l’ID del channel manager

1. Dal Menu principale vai su Marketplace > My Subscriptions
2. Trova l’integrazione del tuo channel manager e clicca su Impostazioni
3. Clicca su Channel manager companies
4. Clicca sul bottone +
5. Alla voce Channel manager ID inserisci il codice fornito dal proprio channel manager
6. Alla voce Company cerca il profilo dell'Agenzia di viaggio che desideri mappare
7. Clicca su Crea

#### Metodo 3: Utilizza il numero IATA

1. Apri il profilo dell’Agenzia di viaggio appena creata
2. Alla voce IATA inserisci il numero IATA fornito dal proprio channel manager
3. Clicca su Salva

#### Metodo 4: Utilizza il nome dell’Agenzia di viaggio

1. Apri il profilo dell’Agenzia di viaggio appena creata
2. Alla voce Nome, inserisci il nome dell’Agenzia di viaggio che stai cercando di mappare. Questo deve essere formattato esattamente come inviato dal channel manager, o non funzionerà. Quindi, effettua sempre un doppio controllo con il channel manager prima di procedere.
3. Clicca su Salva

### Step 3: Crea un Contratto per l’Agenzia di viaggio

Crea un contratto per le Agenzie di viaggio, così Quadro saprà sempre come gestire le prenotazioni fatte con una determinata Agenzia di viaggio ( come ad esempio commissioni e le regole della struttura)

1. Dal Menu principale vai a Profili > Travel Agency contracts
2. Clicca sul bottone +
3. Alla voce Company, cerca il profilo dell’Agenzia di viaggio appena creata
4. Scegli come le prenotazioni debbano essere effettuate attraverso una determinata Agenzia di viaggio. Le prenotazioni possono essere effettuate sia tramite l’ospite che l’agenzia di viaggio
5. Compila tutti gli altri campi rilevanti 
6. Clicca su Salva

#### Creare automaticamente i profili per le agenzie di viaggio

Abilita Quadro a creare automaticamente i profili per le compagnie e le agenzie di viaggio quando esse sono fornite dal channel manager ma non trovano alcuna corrispondenza in Quadro.

1. Dal Menu principale vai a Marketplace > My subscriptions
2. Trova l’integrazione con il tuo channel manager e clicca su Impostazioni
3. Alla voce Opzioni, abilita Crea profili Aziendali e profili per Agenzie di viaggio
4. Clicca su Salva

## Commissioni delle Agenzie di viaggio

Quando stai settando il Contratto dell’Agenzia di viaggio, può essere compilato anche un campo relativo alle commissioni.

Questo campo non è obbligatorio, dipende tutto da come vuoi visualizzare le commissioni.

Se il campo viene compilato, non influenzerà il prezzo di prenotazione e solo il report mostrerà l’importo pagato all’agenzia di viaggio.

Se vorresti avere prezzi differenti per una prenotazione, ovvero, se l’ospite ha già pagato le commissioni all’Agenzia di viaggio e deve solo pagare a voi il resto, allora è possibile aggiungere delle modifiche.

Puoi creare sia una Modifica Assoluta che una Modifica relativa.
Una Modifica assoluta avrà sempre lo stesso valore

 * Se la modifica corrisponde a 100, il prezzo della prenotazione sarà modificato di +100 (in qualsiasi valuta applicata ad esso)

Una Modifica relativa utilizzerà invece una percentuale del valore del prezzo della prenotazione nel calcolo

 * Se la modifica corrisponde al 12%, la commissione cambierà in base al totale del prezzo della prenotazione

N.B. se desideri modificare il prezzo al ribasso, dovrai aggiungere un “-” (meno) prima del numero

Le opzioni di contratto danno la possibilità di includere la cancellation fee nel preventivo della commissione e/o regolare manualmente le prenotazioni in arrivo dall’Agenzia di viaggio