# AlgoPortAI
Il progetto di tesi consiste nella realizzazione di un algoritmo che risolve un problema di ricerca operativa.
Questo algoritmo serve all’ottimizzazione della logistica portuale relativa all’ingresso e uscita delle navi in porto. Tale algoritmo prende un numero N di navi che sono in rada fuori dal porto o comunque devono essere schedulate negli ingressi. 
Tale navi ha come constrain: la banchina di attracco, e il giorno di arrivo.
L’obiettivo di tale algoritmo è quello di restituire all’ingresso di N navi e le condimeteo delle successive 48 ore, un output di contenente data e ora, ordine di ingresso di ciascuna nave e il tempo consigliato di attracco per ogni singolo mezzo. Così facendo è possibile ottimizzare notevolmente l’afflusso delle navi in porto incrementando quindi il numero di navi annue e di conseguenza gli incassi di ADSP sui diritti di attracco.
Inoltre tale sistema avrà come secondo obiettivo la riduzione delle navi in rada, in quanto punta a ottenere il minor tempo possibile della singola nave sulle acquee Tirreniche, cercando di ridurre notevolmente il tempo di attesa fuori dal porto. 
Così facendo viene in gioco un secondo obiettivo, quello della riduzione delle emissioni inquinanti nelle acquee Livornesi, date dalle lunghe attese delle imbarcazioni all’ingresso del porto e del tempo passato attraccate a banchina, rientrando così in un progetto finanziabile come riduzione dell’impatto ambientale del porto.

I possibili utilizzi di questo algoritmo non si fermano puramente all’ottimizzazione degli ingressi in porto delle navi sia da cargo che da crociera.
 
Infatti tale algoritmo a fronte di un periodo di training in situazione reale di almeno 6 mesi, è integrabile con un’algoritmo di intelligenza artificiale, per poter effettuare analisi predittive sui periodi migliori per effettuare lavorazioni nelle zone portuali, causando così una riduzione più bassa possibile della logistica in porto.
Oltre ad una previsione temporale per l’ottimizzazione dei lavori in porto è possibile anche eseguire stime tramite predizioni sui costi ed i possibili budget per l’anno successivo delle lavorazioni di competenza di ADSP.

Al momento in italia Non esistono algoritmi del genere applicati ad una ADSP, e anche a livello europeo non ho riscontrato grandi similitudini, pertanto ADSP MTS potrebbe essere la prima autorità di sistema portuale ad utilizzare un sistema di ottimizzazione del genere.

Per la realizzazione dell’algoritmo è richiesta una tempistica di più o meno 3 Mesi, dopodichè sarà possibile integrarlo all’interno di un server che processerà tutti i dati automaticamente per poter restituire un risultato sui client mobile presenti nei telefoni e se richiesto anche sui desktop di ADSP.
Passato il periodo di sviluppo di 3 mesi, seguirà un periodo di 6 mesi di training dell’algoritmo, dove verranno affinati i parametri in ingresso e le costanti per poter ottenere risultati ottimali in tutte le condizioni reali.
A seguito del periodo di training dove verranno distribuite le credenziali ad un numero ridotto di tester interni di ADSP, verrà eseguita la pubblicazione finale dell’algoritmo con tutto il software e relativa distribuzione degli accessi a tutti i dipendenti ADSP.

L’azienda sviluppatrice del progetto resterà a disposizione anche a seguito della distribuzione del sistema al fine di effettuare un bug fixing generale del software e per continui aggiornamenti e evoluzioni dell’algoritmo, che si propone di entrare nella quotidianità delle ADSP Italiane e a seguito Europee.
