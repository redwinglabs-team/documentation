# Point of sale

L’integrazione Point-of-Sale (POS) di Quadro aggiunge diverse proprietà per la gestione delle transazioni che vengono effettuate attraverso i propri outlet esterni, quali ristoranti o spa. Imposta i tuoi servizi, outlet e categorie di contabilità per connettere Quadro al POS di Staff App. 

Solamente le informazioni strettamente necessarie vengono scambiate tra Quadro e il POS, così da garantire la sicurezza dei dati degli ospiti.

## Servizi

Prima di poter connettere il sistema di POS a Quadro, devi prima creare i servizi relativi (come ad esempio Ristorante o Bar). 

Quando il POS invia gli articoli a Quadro per aggiungerli al conto di un ospite, li raggruppa per quel servizio, per la categoria di contabilità e li collega al conto e alle fatture dell’ospite, ma non sono strettamente connessi a prodotti specifici (quindi i prodotti presenti in POS non è necessario che corrispondano a quelli in Quadro).

## Outlets

Prima che il tuo servizio di POS si connetta a Quadro, devi creare degli outlet di riferimento. 

Gli outlet vengono utilizzati per registrare tutte le transazioni che avvengono all’esterno di Quadro; per esempio, se qualcuno ordina un drink al bar e lo paga immediatamente con contanti o carta, piuttosto che scegliere di addebitarlo sul conto, la transazione verrà riportata sotto l’outlet specifico alla voce Report di contabilità.

## Come vengono scambiate le informazioni tra Quadro e il POS

Lo scambio di informazioni tra il POS e Quadro è progettato in maniera tale da garantire la sicurezza dei dati trattati.

### Articoli venduti immediatamente

1. L’ospite ordina un articolo
2. Chiede di poter pagare immediatamente tramite contanti o carta
3. L’impiegato completa la transazione
4. Poi invia gli articoli a Quadro, secondo la propria categoria di contabilità
5. La transazione sarà elencata nel report di contabilità sotto l’outlet corrispondente

### Articoli addebitati sul conto dell’ospite

1. L’ospite ordina un articolo
2. Chiede che gli venga addebitato sul suo conto
3. L’impiegato si informa sul suo nome o numero di camera in modo da cercarlo sul POS
    - Solamente gli ospiti che fanno parte di una prenotazione in Quadro, o che possiedono un conto Paymaster intestato e aperto sono elencati all’interno del POS
4. Quadro conferma se l'ospite è in casa e se ha classificazioni che impedirebbero loro di avere addebiti aggiunti al conto
5. Gli articoli vengono inviati a Quadro con la loro categoria di contabilità associata
    - Se nessuna categoria di contabilità è associata ad un articolo, gli viene applicata la categoria associata al servizio. 
6. In Quadro, l’addebito sarà elencato nel profilo dell’ospite e nel report di contabilità
