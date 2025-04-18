È stata realizzata una base di dati per la gestione dell’ufficio acquisti di un ente pubblico 
caratterizzato dal seguente insieme di requisiti: 

- L’ente sia organizzato in un certo insieme di dipartimenti, ciascuno identificato univocamente da un codice e caratterizzato da una breve descrizione e dal nominativo del responsabile (si assuma che ogni dipartimento abbia un unico responsabile e che una stessa persona possa essere responsabile di più dipartimenti);
- Ogni dipartimento possa formulare delle richieste d’acquisto; ogni richiesta di acquisto formulata da un dipartimento sia caratterizzata da un numero progressivo, 
che la identifica univocamente all’interno dell’insieme delle richieste del dipartimento (esempio, richiesta numero 32 formulata dal dipartimento D37), da una data (si 
assuma che uno stesso dipartimento possa effettuare più` richieste in una stessa data), dall’insieme degli articoli da ordinare, con l’indicazione, per ciascun articolo, 
della quantità richiesta, e dalla data prevista di consegna;
- Ogni articolo sia identificato univocamente da un codice articolo e sia caratterizzato da una breve descrizione, da una unità di misura e da una classe merceologica;
- Ogni fornitore sia identificato univocamente da un codice fornitore e sia caratterizzato dalla partita IVA, dall’indirizzo, da uno o più recapiti telefonici e da un 
indirizzo di posta elettronica; alcuni fornitori (non necessariamente tutti) possiedano un numero di fax;
- Ad ogni fornitore sia associato un listino, comprendente uno o più articoli; per ciascun articolo appartenente ad un dato listino siano specificati il codice articolo, il 
prezzo unitario, il quantitativo minimo d’ordine e lo sconto applicato;
- Per soddisfare le richieste provenienti dai vari dipartimenti, l’ufficio acquisti emetta  degli ordini; ogni ordine sia identificato univocamente da un codice ordine e sia 
caratterizzato dalla data di emissione, dal fornitore a cui viene inviato, dall’insieme degli articoli ordinati, con l’indicazione, per ciascuno di essi, della quantità` ordinata, 
e dalla data prevista di consegna (si assuma che un ordine possa fondere insieme più richieste d’acquisto dei dipartimenti).

Il database è stato realizzato con PostgreSQL ed è stata svolta una successiva analisi dei dati tramite R. 
