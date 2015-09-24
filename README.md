# ooo-visualizer
Strumento per la visualizzazione delle verifiche dell'Indaba

## Installazione

ooo-visualizer è composto da un file html (index.html) e da
alcune risorse da questo riferite.

Per installare il visualizer

 * Copiare il contenuto della cartella (rispettando i path relativi)
 * ```cp config.js.sample config.js```
 * Modificare i parametri dentro ```config.js```
 * 
 
## Utilizzo

Per utilizzare il visualizer, dopo averlo configurato tramite
il file ```config.js```, basta indirizzare il browser
all'indirizzo del file ```index.html```.

Il flusso viene aggiornato in 3 possibili modi:
 * Periodicamente, secondo l'intervallo settato in ```config.js``` (default 20 secondi),
 * Trascinando (mouse click) la pagina verso il basso si ottengono gli aggiornamenti più recenti,
 * Scorrendo la pagina verso il basso si ottengono gli aggiornamenti più vecchi.