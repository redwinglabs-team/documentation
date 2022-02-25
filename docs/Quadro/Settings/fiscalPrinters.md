# Configurazione stampanti fiscali

Configura i profili della stampante in Quadro per ogni stampante fisica all'interno della tua struttura (ad es. Stampanti per ricevute, fiscali, da cucina o da bar). Se hai quattro unità attive, dovresti avere quattro corrispondenti configurazioni in Quadro Pms.

Tieni presente che l'aggiunta di una stampante fisica in Quadro richiede anche alcune impostazioni hardware e configurazioni di rete.

## Aggiungere una stampante fiscale

1. Vai a Menu principale > Impostazioni > Avanzate
2. Clicca sul bottone +
3. Spunta la casella "Abilita"
4. Inserisci l'indirizzo IP e il seriale della stampante di riferimento
5. Associa un Contatore. Il contatore in questione, ogni qualvolta verrà utilizzato per la chiusura di un conto, invierà la richiesta di stampa scontrino alla stampante
5. Clicca Salva

### Trovare indirizzo IP di una stampante fiscale

#### Recuperare l'indirizzo IP della stampante:

1. Accendi la stampante e collegala alla rete che utilizzi per i tuoi dispositivi.
2. Per garantire che l'indirizzo IP della stampante non cambi, è necessario assegnare alla stampante un indirizzo IP statico (riservato) nelle impostazioni del router.
3. Spegnere la stampante.
4. Tenendo premuto il pulsante di avanzamento, accendere la stampante e continuare a premere il pulsante di avanzamento per circa 7 secondi. L'indirizzo IP viene visualizzato sulla ricevuta stampata.
5. Copiare la seguente stringa subito dopo l'indirizzo IP trovato: "/cgi-bin/fpmate.cgi?devid=local_printer&timeout=10000"