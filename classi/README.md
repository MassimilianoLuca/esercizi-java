# Esercizio no.1
Crea un programma dotato di una classe 'potenza' che implementa la potenza del 2 dei numeri (interi) associati agli oggetti istanziati della classe .
La classe deve essere dotata di costruttore, di un metodo pow() che stampi a video la potenza del numero associato all'oggetto, e di un metodo cambiobase() che deve permettere di cambiare base alla potenza da calcolare.
# Esercizio no.2
Crea un programma per la gestione di un controcorrente gestito dalla classe CC.
Il programma deve essere in grado di effettuare versamenti, prelievi, di restituire il saldo e di effettuare la lista degli ultimi 5 movimenti .
# Esercizio no.3
Realizza un programma per gestire una pila di interi di max 5 elementi attraverso una classe pila che deve prevedere dei metodi per l'inserimento e per l'estrazione di un elemento.
# Esercizio no.4
Realizza un programma per gestire una coda di interi di max 5 elementi attraverso una classe Coda che deve prevedere dei metodi per l'inserimento e per l'estrazione di un elemento.            
# Esercizio no.5
Scrivi una classe T che contenga un orario valido. Deve essere possibile impostare un orario in ore,minuti,secondi; la classe deve prevedere un metodo per la validazione di un orario, un metodo per aggiungere un orario ad un altro e un metodo per sottrarre due orari .
# Esercizio no.6
Scrivi una classe che dati due numeri complessi in ingresso, sia in grado di stampare in output la loro somma, la loro differenza, il loro prodotto e il loro rapporto.
# Esercizio no.7
Un trapano verticale si può muovere lungo le direzioni x,y di un piano per poi fermarsi ed eseguire un foro.
L'operazione di foratura e di traslazione lungo gli assi xy è subordinata al fatto che il motore del trapano sia acceso o spento.
Realizza una classe 'Motore' che gestisca lo spegnimento e l'accensione del motore.
Estendi la classe precedente con la classe 'Punta' che invece si occupa di muovere il trapano sui tre assi.
# Esercizio no.8
Definisci una classe Parallelogramma (P) con i seguenti attributi: diagonale maggiore (D) diagonale minore (d) e angolo (p) che la diagonale maggiore forma rispetto l'orizzontale.
Deve essere possibile calcolare, i lati, l'area e perimetro del parallelogramma.
Costruisci, quindi la classe Rombo [R] estendendo la precedente e Quadrato (Q)
estendendo Rombo .
# Esercizio no.9
Un oggetto della classe InsiemeDiStringhe consente di rappresentare un qualunque insieme finito di stringhe.
La classe InsiemeDiStringhe ha il seguente scheletro:
1. class InsiemeDiStringhe {..} variabile che rappresenta l'insieme di stringhe considerato dall'oggetto.
2. InsiemeDiStringhe(..) costruttore che permette di creare un oggetto che rappresenta l'insieme di stringhe contenute in un array T.
3. public String stringaLunga() restituisce la stringa di lunghezza massima, se vi sono più stringhe di lunghezza max ne restituisce una arbitrariamente.
4. public String spaziStringa() restituisce la stringa contenente più spazi
5. public String preStringa() visualizza tutte le stringhe che hanno il prefisso specificato .
# Esercizio no.10
Si realizzi una applicazione java per la gestione di un garage secondo le specifiche:
il garage ha al max 15 posti ognuno dei quali è identificato da un num a partire da 0
e per motivi di capienza può ospitare solo auto moto e furgoni partendo dalla classe base veicolo a motore V; la si estenda, realizzando anche le classi che modellano le entità furgone (F) auto (A) e moto (M).
Ridefinire il metodo toString in modo che ogni entità possa esternalizzare in forma di stringa tutte le informazioni che la riguardano.
Si implementi una classe che modelli il garage sopradescritto offrendo le seguenti operazioni di gestione
1. immissione di un nuovo veicolo
2. estrazione dal garage del veicolo che occupa un determinato posto (ritornare l'istanza del veicolo stesso)
3. stampa della situazione corrente dei posti nel garage veicolo:
marca,anno,cilindrata;
auto:porte, alimentazione (diesel/benzina)
moto:tempi
furgone:capacità
# Esercizio no.11
E' necessario scrivere una applicazione che simula il funzionamento di un frammento del sistema informativo di un operatore di telefonia cellulare.
Si devono quindi rappresentare i dati relativi ad una carta SIM ed in particolare:
* il numero di telefono
* il credito disponibile in euro
* la lista delle telefonate effettuate
Per ciascuna telefonata deve essere rappresentata la durata in minuti
La classe SIM dovrà fornire le seguenti funzionalità:
* un costruttore parametrizzato che crea una SIM con numero di telefono, un credito e la lista delle
   telefonate vuota
* un metodo per l'inserimento di una telefonata con i dati forniti dall'utente.
* una funzione per il calcolo dei minuti totali di conversazione.
* una funzione per il calcolo delle telefonate effettuate verso un certo numero
* una procedura per la stampa dei dati della SIM e l'elenco delle telefonate.
# Esercizio no.12 
All'aggiusteria agricola possono essere riparati tre tipi di apparecchiature: motozappe, decespugliatori, tosaerba. Ciascuna di queste macchine, ha dei dati comuni
Un numero intero che costituisce il numero d'ordine della lavorazione, ogni volta che una macchina viene consegnata all'aggiusteria acquisisce un nuovo numero d'ordine, anche se quella macchina è già stata lì in precedenza. Deve essere specificata la marca dell'apparecchio. Ad ogni macchina deve essere associato il totale del costo di riparazione.
Per i tosaerba e le motozappe va specificato il numero di ruote della macchina.
Per i decespugliatori bisogna specificare se l'accensione è elettronica oppure no.
Costruire una opportuna gerarchia di classi, strutturando correttamente la base dei dati. Il massimo numero di macchine che possonono essere simultaneamente in lavorazione è 10 perché questi sono i posti in officina. Ad ogni macchina riparata, deve essere associata una lista delle lavorazioni effettuate e del loro costo, la cui somma costituisce il totale del costo della riparazione .
