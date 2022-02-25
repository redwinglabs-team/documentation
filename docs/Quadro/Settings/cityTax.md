# Tassa di soggiorno

## Settare la Tassa di soggiorno

Ci sono due modi per applicare automaticamente la tassa di soggiorno alle prenotazioni in arrivo.

* Se la tassa di soggiorno è semplice, ad esempio, se esiste un'aliquota fiscale per tutti gli ospiti, puoi utilizzare le regole del prodotto.
* Se la tassa di soggiorno è più complicata, ad esempio, se ci sono aliquote diverse per adulti e bambini, è necessario utilizzare la tassa di soggiorno fissa.

Ti consigliamo di utilizzare le regole del prodotto quando possibile poiché sono molto più flessibili, quindi puoi modificarle facilmente in caso di modifiche alle leggi fiscali locali.

In questo articolo puoi scoprire come impostare la tua tassa di soggiorno:

- Utilizzando delle regole del prodotto
    - Per escludere la tassa di soggiorno dal costo della prenotazione
        - Passaggio 1: crea un prodotto fiscale comunale
        - Passaggio 2: crea la regola del prodotto
    - Per includere la tassa di soggiorno nel costo della prenotazione
        - Passaggio 1: crea un prodotto fiscale comunale
        - Passaggio 2: crea un prodotto di adeguamento dell'alloggio
        - Passaggio 3: crea la regola del prodotto
- Utilizzo della funzione di tassa comunale fissa
- Tassa di soggiorno e channel manager
    - Tassa di soggiorno fissa

## Utilizzare le regole di prodotto

Imposta la tassa di soggiorno come prodotto e applicala automaticamente alle prenotazioni in arrivo con le regole del prodotto.

!!! Nota 
    il modo in cui imposti la tassa di soggiorno dipende dal fatto che desideri includere o escludere la tassa di soggiorno dal prezzo della prenotazione. Se non sei sicuro, controlla con l'autorità fiscale locale.

### Escludere la tassa di soggiorno dal prezzo della prenotazione

#### Step 1: Crea il prodotto tassa di soggiorno

1. Vai al menu principale > Impostazioni > Servizio Prenotabile
2. Seleziona il tuo servizio prenotabile.
3. Fare clic su Prodotti.
4. Fare clic sul pulsante +, quindi su + Prodotto.
5. In Nome, inserisci "Tassa di soggiorno".
6. Inserisci l'importo e l'aliquota fiscale per la tua tassa di soggiorno.
    - Se la tassa di soggiorno è un valore assoluto, ad esempio 2,50 €, seleziona l'opzione Fissa e inseriscila in Importo. Quando inserisci un importo, devi anche scegliere una valuta.
    - Se la tassa di soggiorno è relativa al costo del soggiorno, ad esempio il 2%, seleziona l'opzione Relativa e inserisci la percentuale in Valore percentuale. Scegli i campi pertinenti.
7. In Opzioni prodotto, assicurati di selezionare l'opzione Escludi prezzo dall'offerta.
8. Fare clic su Crea.

#### Step 2: Crea la regola del prodotto

1. Vai al menu principale > Impostazioni > Servizio Prenotabile
2. Clicca sul tuo servizio prenotabile.
3. Dal menu Impostazioni, fai clic su Regole del prodotto.
4. Fare clic sul pulsante +.
5. Nel campo Priorità, inserisci un numero inferiore a tutte le altre regole del tuo prodotto, per assicurarti che Quadro lo applichi a ogni prenotazione in arrivo. 

!!! Nota 
    Puoi inserire un valore negativo per assicurarti che sia la regola del prodotto con la priorità più alta.

6. Inserisci altri dettagli rilevanti e fai clic su Crea.
7. In Azione regola, seleziona Aggiungi.
8. In Prodotto, scegli il prodotto dell'imposta comunale.
9. Fare clic su Crea e quindi su Salva.

### Includere la tassa di soggiorno nel prezzo della prenotazione

#### Step 1: Crea il prodotto tassa di soggiorno

1. Vai al menu principale > Impostazioni > Servizi.
2. Seleziona il tuo servizio prenotabile.
3. Fare clic su Prodotti.
4. Fare clic sul pulsante +, quindi su + Prodotto.
5. In Nome, inserisci "Tassa di soggiorno".
6. Inserisci l'importo e l'aliquota fiscale per la tua tassa di soggiorno.
    - Se la tassa di soggiorno è un valore assoluto, ad esempio 2,50 €, seleziona l'opzione Fissa e inseriscila in Importo. Quando inserisci l'importo, devi anche scegliere una valuta.
    - Se la tassa di soggiorno è relativa al costo del soggiorno, ad esempio il 2%, seleziona l'opzione Relativa e inserisci la percentuale in Valore percentuale. Scegli i campi pertinenti.
7. In Opzioni prodotto, assicurati che Escludi prezzo dall'offerta sia deselezionato.
8. Fare clic su Crea.

#### Step 2: Crea un prodotto di compensazione del pernotto

1. Vai al menu principale > Impostazioni > Servizi.
2. Seleziona il tuo servizio prenotabile.
3. Fare clic su Prodotti.
4. Fare clic sul pulsante +, quindi su + Prodotto.
5. In Nome, inserisci "Adeguamento dell'alloggio".
6. Inserisci l'importo per il prodotto, l'importo dovrebbe essere uguale alla tua tassa di soggiorno, ma con un valore negativo. L'adeguamento dell'alloggio annulla il costo della tassa di soggiorno.
- Se la tassa di soggiorno è un valore assoluto, ad esempio -€2,50, seleziona l'opzione Fissa e inseriscila sotto l'importo. Quando inserisci l'importo, devi anche scegliere una valuta.
- Se la tassa di soggiorno è relativa al costo del soggiorno, ad esempio -2%, scegli Relativa e inserisci l'adeguamento in Valore percentuale.
7. Immettere la categoria Aliquota fiscale e Contabilità del prodotto di rettifica. Questi dovrebbero corrispondere all'aliquota fiscale e alla categoria Contabilità impostate nel servizio di soggiorno.
8. In Opzioni prodotto, seleziona Escludi prezzo dall'offerta e Fattura come pacchetto.
9. Fare clic su Crea.

#### Step 3: Crea la regola del prodotto

1. Vai al menu principale > Impostazioni > Servizi.
2. Clicca sul tuo servizio prenotabile.
3. Dal menu Impostazioni, fai clic su Regole del prodotto.
4. Fare clic sul pulsante +.
5. Nel campo Priorità, inserisci un numero inferiore a tutte le altre regole del prodotto per assicurarti che Quadro lo applichi a ogni prenotazione in arrivo. 

!!! Nota 
    Puoi inserire un valore negativo per assicurarti che sia la regola del prodotto con la priorità più alta.

6. Inserisci altri dettagli rilevanti e fai clic su Crea.
7. In Azione regola, seleziona Aggiungi.
8. In Prodotto, scegli il prodotto dell'imposta comunale.
9. Fare clic su Crea.
10. Ripeti i passaggi precedenti, ma seleziona Adeguamento alloggio in Prodotto.

### Utilizza la Tassa di soggiorno fissa

Se stai già utilizzando una regola di prodotto per aggiungere la tassa di soggiorno alle prenotazioni, devi aggiornare la regola di prodotto prima di attivare una tassa di soggiorno automatica.

1. Vai al menu principale > Impostazioni > Servizi.
2. Seleziona il tuo servizio prenotabile.
3. Nelle tue Impostazioni generali, trova il campo Tassa di soggiorno e seleziona la tua città. Se non riesci a trovare la tua città, potrebbe non essere ancora supportata.
4. In Modalità tassa di soggiorno, scegli se vuoi includere o escludere la tassa di soggiorno dal prezzo della prenotazione. Se escludi la tassa di soggiorno, Quadro la addebita in aggiunta al prezzo della prenotazione. Ad esempio: se la tua tassa di soggiorno è di € 2 e un ospite effettua una prenotazione per una notte a una tariffa di € 10 a notte, l'ospite paga € 12.
5. Nella sezione Opzioni, nel campo Opzioni, dal menu a tendina selezionare Fattura come pacchetto. Nota: deseleziona le voci Ha ampliato la fattura se l'hai selezionata.
6. Fare clic su Salva.

!!! Nota 
    La tassa comunale fissa è meno flessibile delle regole sui prodotti, quindi se la tua tassa comunale è dovuta a modifiche è importante comunicarcelo in modo che possiamo iniziare ad aggiornarla in anticipo.