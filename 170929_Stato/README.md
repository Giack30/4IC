Nel file TestDataDownload all'interno del progetto � presente una classe Osservatore che implementa Runnable che possiede 2 propriet�: una variabile thread e una
variabile stato. Esse vengono definite nel costruttore e nel main assumono il valore di tn. Viene sovrascritto inoltre il metodo run() che consiste nel verificare 
che lo stato cambi in un for loop: questo viene controllato ogni 20 millisecondi. Se lo stato cambia viene stampata una frase adatta. Se lo stato rilevato � 
TERMINATED, si esce dal for e il programma termina.