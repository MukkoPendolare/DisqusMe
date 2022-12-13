# DisqusMe

Buongiorno Mukki,  
qui potete scaricare i file necessari per riavvicinare l'interfaccia utente di disqus a quella precedente precedente al 12/12/22.

La lista delle modifiche al CSS che vengono attivate nelle pagine web disqus.com/embed, 

- elimina border radius dagli avatar e ne rimpicciolisce la dimensione
- cancella il piccolo orologio prima della data in cui è stato postato il commento 
- toglie i bordi arrotondati al rettangolo per scrivere un nuovo commento
- toglie i bordi arrotondati al pulsante di nuovo commento
- toglie i bordi arrotondati alla notifica dei nuovi commenti nella chat
- toglie i bordi arrotondati al pulsante finale di carica nuovi commenti
- modifica le dimensioni dei caratteri (attualmente disqus prende le dimensioni dei caratteri dalle impostazioni del browser, e mescolando le cose potrebbe funzionare male
- (DISATTIVATO DI DEFAULT perché brutto) inserisce una linea tra i post, 
- cambia l'icona dalla manina alla freccetta
- sostituisce lo sfondo della home di Google con la GIF di una mucca
- corregge l'errore di impaginazione nelle lunghe liste di upvote

## Come è e come sarà
<span><img src="https://github.com/MukkoPendolare/DisqusMe/raw/main/img/OLD.PNG" width="45%" /></span> 
<span><img src="https://github.com/MukkoPendolare/DisqusMe/raw/main/img/NEW.PNG" width="45%" /></span> 

## Installazione

### Browser Mozilla Firefox

1. Installare l'add-on [Stylus](https://addons.mozilla.org/it/firefox/addon/styl-us/)
2. Cliccare sull'icona dell'estensione in alto a destra
3. Cliccare manage
4. In backup importare il File [DisqusMeforstylus.json](https://github.com/MukkoPendolare/DisqusMe/raw/main/DisqusMeforstylus.json) e accettare il cambio di impostazioni 

### Browser Google Chrome

L'estensione [Sylus](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) esiste anche per Google Chrome, dovrebbe funzionare in modo del tutto simile ma io non l'ho provata.

Alternativamente:  

1. Scaricare il file [DisqusMe.zip](https://github.com/MukkoPendolare/DisqusMe/raw/main/DisqusMe.zip)
2. Estrarre l'archivio in una cartella 
3. Copiare chrome://extensions/ nella barra degli indirizzi
4. Abilitare le opzioni da sviluppatore
5. Cliccare su Carica estensione non pacchettizzata 
6. Scegliere la cartella in cui si è estratto il contenuto dell'archivio 

### Smanettoni

Potete modificare i file contenuti nel pacchetto o il file CSS da aggiungere a Stylus (esiste anche l'estensione per Chrome).  
Usando Stylus dovete però avere l'accortezza di abilitare l'opzione "Expose iframes via HTML[stylus-iframe]" altrimenti non funzionerà)  
