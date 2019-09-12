

[Indice](index.md) / [Quovai PMS](quovai-pms-it.md) / **PSD2 e SCA - adempimenti**

# **PSD2 e SCA - adempimenti**

Il 14 settembre 2019 entrerà in vigore una direttiva* (valida nei Paesi dello Spazio Economico Europeo – EU 28 ed Islanda, Liechtenstein e Norvegia) che cambierà il modo di lavorare delle strutture ricettive, in particolare per quanto riguarda i pagamenti elettronici: le carte di credito.

Si tratta della direttiva [PSD2 (Payment Services Directive)](https://eur-lex.europa.eu/legal-content/IT/TXT/PDF/?uri=CELEX:32015L2366&from=EN) che introduce importanti novità in termini di sicurezza per gli utenti europei che utilizzano i canali online per l’operatività bancaria.

**In cosa consiste la normativa?**  
Una delle principali novità della direttiva PSD2 è la SCA (**Strong Customer Authentication**) che è un’autenticazione forte del cliente basata su due o più elementi:

1. “**Conoscenza**”, ad esempio la password personale o il PIN che solo l’utente conosce,  
2. “**Possesso**”, una password temporanea (c.d. One Time Password) generata tramite token mobile (una APP su smartphone) o token fisico (ad esempio una “chiavetta”), e valida per un solo utilizzo  
3. “**Inerenza**”, qualcosa di univoco che contraddistingue l’utente come ad esempio la sua impronta digitale, il riconoscimento vocale, i dati comportamentali.

Un esempio che avrete sicuramente visto in passato è la cosiddetta 3D Secure 1 (3DS1) authentication, ovvero il caso in cui dopo aver fornito il numero della carta di credito per un acquisto venite re-indirizzati ad un sito di Visa o Mastercard per ricevere un codice via SMS e confermare la vostra identità. Molte più transazioni, che oggi richiedono solo il numero della carta di credito, richiederanno un tipo di autenticazione che si chiama 3D Secure 2 (3DS2) che migliora l'esperienza di acquisto in paragone del 3DS1.

**Cosa cambia praticamente?**  
Gli enti emittenti le carte di credito rifiuteranno le transazioni fatte con carta non presente (come quanto si addebita a un cliente un no-show oppure una penale utilizzando la carta fornita in prenotazione o un booking online) se tale carta non è stata raccolta nelle modalità indicate dalla normativa PSD2/SCA, cioè per esempio fornendo, oltre al numero di carta di credito, anche un codice ricevuto via SMS, o tramite gli altre elementi sopracitati (1, 2, 3).

Questo potrebbe significare che una carta raccolta a garanzia di una prenotazione non sarà utilizzabile in fase di addebito di una penale o no show o una tariffa non rimborsabile. In pratica sarà inutile.

**Come risolviamo il problema?**  
QUOVAI risolve il problema adattando la propria modalità di check-out al sistema integrato **Stripe** per le transazioni online in modalità SCA. Questo significa che un sistema molto sofisticato potrebbe richiedere un'autenticazione aggiuntiva (sms, codice biometrico, password, etc...) in fase di completamento della prenotazione, tutto questo nel modo più trasparente per il cliente (detto 3DS2).

In questo modo le carte di credito registrate sul PMS QUOVAI verranno salvate in una modalità che vi consentirà l'utilizzo **entro 90 giorni**. Dopo 90 giorni (questo limite è insito nella direttiva PSD2), Quovai vi fornirà un sistema per chiedere al cliente un rinnovo del permesso ad utilizzare la carta di credito nei casi eccezionali in cui trascorrano più di 90 giorni tra la prenotazione e il check-in.

**Esistono esenzioni alla SCA?**  
Certo, ecco alcune transazioni che non hanno l’obbligo di usare la SCA:

• **Transazioni MOTO (Mail Order Telephone Order)**: Tutti gli ordini fatti tramite mail o telefono saranno esenti dalla SCA (almeno per il momento), poiché non vengono considerati come pagamenti elettronici (elaborazione manuale).  
• **Transazioni inter-regionali**: Tutti i pagamenti dove issuer o acquirer risiedono fuori dall’Europa sono esenti dalla SCA.  
• **Bonifici bancari.**

**Praticamente cosa dovrete fare?**  
a) Le strutture ricettive che **vorranno** usare la nuova modalità nel modo più flessibile dovranno aprire con noi un utenza **Stripe** (se non ce l'hanno già). E' gratis ed è molto utile. Facciamo praticamente tutto noi, dovrete solo fornirci alcuni dati. L'unico costo di Stripe [2019 è la commissione di 1,4% + 0,26 a transazione in caso di utilizzo della carta di credito a garanzia.

b) Per le strutture che **non vorranno** aprire un'utenza Stripe, Quovai utilizzerà la propria, salvando la carta di credito del cliente sul proprio conto Stripe. In caso di no-show o di penale, Quovai addebiterà la carta di credito del cliente, retrocedendo la somma dovuta alla struttura meno un piccolo costo amministrativo Quovai.
