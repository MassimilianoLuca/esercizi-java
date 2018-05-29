# Esercizio 1
Scrivere un programma che calcoli il risultato dell’esame di uno studente.
Il programma prenderà in ingresso:
* il voto ottenuto nella prova scritta (varia tra -8 e +8)
* il voto ottenuto nella prova pratica (varia tra 0 e 24)
Memorizzati questi dati procederà al calcolo del risultato finale in trentesimi procedendo come segue:
* Il risultato finale è la somma dei risultati.
* se il voto di teoria è minore (o uguale) di zero e la somma dei voti di teoria e pratica è maggiore di 18 lo studente è bocciato.
* se il voto di teoria è minore (o uguale) di zero e il voto di pratica è minore di 18 il programmalo studente è bocciato.
* se il voto di teoria è maggiore di zero e la somma dei voti di teoria e pratica è minore di 18 lo studente è bocciato.
* se la somma di teoria e pratica vale 31 o 32 il programma stampa: “congratulazioni: 30 e lode”
* in tutti gli altri casi lo studente è promosso e viene riportato il voto calcolato.
# Esercizio 2
Scrivere un programma che chieda agli utenti due stringhe in ingresso, le stringhe possono valere solo: “carta”, “forbice” o “sasso”. Il programma dovrà quindi effettuare i dovuti controlli e dichiarare il vincitore secondo le note regole della “morra cinese” (forbice vince su carta, carta vince su sasso, sasso vince su forbice).
# Esercizio 3
Scrivere una funzione per calcolare l’importo di una tassa secondo la seguente tabella:
* Fino a 10.000 €, l’importo della tassa è del 10%
* Fino a 20.000 €, l’importo della tassa è del 10% per i primi 10.000 €, del 7 % sul restante.
* Fino a 30.000 €, l’importo è ancora del 10% per i primi 10.000 €, poi del 7% fino a 20.000 ed infine il 5% sul restante.
* Oltre i 30.000 € ci si comporta come prima, aggiungendo un ulteriore 3% è sulla porzione oltre i 30.000 €.
* Per ogni importo non valido si ritorni -1 (qualunque importo che non sia un numero reale e positivo).
