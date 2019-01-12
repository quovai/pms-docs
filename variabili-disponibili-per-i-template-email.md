[Indice](index.md) / [Quovai PMS](quovai-pms-it.md) / Variabili disponibili per i template email

## Variabili disponibili per i template email

All'interno dei template messi a disposizione per inviare email ai propri clienti, è possibile usare **alcune variabili** che verranno sostituite dal sistema con i dati della prenotazione e del cliente. Tutte le variabili sono nel formato ## NOME_VARIABILE ##. Di seguito un elenco delle variabili disponibili.

| **Variabile** | **Descrizione** |**Esempio**|
|--|--||--|
|**## RESERVATION ID ##**  |Il codice della prenotazione |31345 |
|**## CUSTOMER FULL ##**  |Il nome completo del cliente (nome e cognome per privato, ragione sociale per azienda o agenzia...)|Paolo Rossi |
|**## PROPERTY NAME ##**  |Il nome della struttura ricettiva |Casa Vacanze Bellavista |
|**## PROPERTY ADDRESS ##**  |L'indirizzo della struttura ricettiva |via del Platano, 25 - Paperopoli |
|**## ACCOMMODATION CATEGORY ##**  |La descrizione della risorsa/della camera/dell'appartamento assegnata/o |Bilocale |
|**## CONTACT WWW ##**  |Il sito web della struttura ricettiva |www.bellavista.it |
|**## CONTACT PHONE ##** |Il telefono della struttura ricettiva |02 77766644 |
|**## CONTACT EMAIL ##** |L'email di contatto della struttura ricettiva |reception@bellavista.it |
|**## CHECK IN##** |Data di check-in |12/01/2019|
|**## CHECK OUT##** |Data di check-out |14/01/2019|
|**## TOTAL AMOUNT ##**|L'importo totale della prenotazione |2000€ |
|**## DEPOSIT DUE ##** |L'importo della caparra dovuta |560€ | 
|**## BALANCE DUE ##** |L'importo totale meno la caparra dovuta |1440€ | 
|**## BALANCE TO DATE ##** |Lo stato attuale del conto |1300€ |   
|**## ADDITIONAL NOTES ##** |Le note addizionali inserite per la mail che si sta inviando|Le abbiamo riservato un trilocale vista mare!|   
|**## RECEIVER ##** |Intestatario per il bonifico alla struttura |Casa Vacanze Quovai S.p.A |   
|**## BANK ##** |Banca per il bonifico alla struttura |Monte dei Paschi di Paperopoli filiale di Topolinia |   
|**## IBAN ##** |IBAN della struttura per il bonifico |PP43434343432899848849398 |   
|**## SWIFT ##** |IBAN della struttura per il bonifico (area fuori SEPA) |PPUUUIIEC |   
|**##OCCUPANCY ##** |Descrizione del tipo di occupazione della camera |**2 adulti** e **1 bambino** |   
|**## PLAN TYPE ##** |Tipo di trattamento (PLAN in Inglese) |Mezza pensione |   