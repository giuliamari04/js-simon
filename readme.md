Descrizione:
Visualizzare in pagina 5 numeri casuali. Da lì parte un timer di 30 secondi.[OK]
Dopo 30 secondi i numeri scompaiono e l'utente deve inserire, uno alla volta, i numeri che ha visto precedentemente, tramite il prompt().[~]
Dopo che sono stati inseriti i 5 numeri, il software dice quanti e quali dei numeri da indovinare sono stati individuati.[OK]

Consigli del giorno:
* Pensate prima in italiano.
* Dividete in piccoli problemi la consegna.
* Individuate gli elementi di cui avete bisogno per realizzare il programma.

Bonus :100: :
Realizzare l'esercizio con grafica e senza utilizzo di prompt ma con casella/e  di input[OK]

N.B. :avviso:
Attenzione che usando Google Chrome, il prompt può dare problemi con la visualizzazione dei numeri in pagina sui tempi di refresh del dom, lasciando i numeri visibili mentre il prompt è aperto.
Per ovviare a questo problema si può impostare 2 timeout differenti a distanza di 1 secondo: il primo nasconde i numeri dal dom (dopo 30 secondi) e il secondo chiede i numeri all'utente (dopo 31 secondi)

quindi a parole cosa faccio...

// const numeriDaGenerare = 5;
// const numeriUtente=[];
// const numerigenerati=[];

// const min = 1;
// const max = 100;

//controllo che numero non sia già presente nell'array sennò pusho dentro
// setTimeout(myFunction,3000);

// myFunction

//array numeri utente da prendere con prompt
//es.
// numerigenerati[5,3,6,23]
// numeriUtente[2,3,4,5]

//array numeri indovinati[] ----length di questo array dice quanti sono e quali sono

// ciclo sui numeriUtente e per ogni numero controllo se è incluso nell'aray dei numeri generati
//se lo trovo lo pusho ne numeri indovinati
