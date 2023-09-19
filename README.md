# PCTO-IISVE-2023-2024

GIORNO 1
Durante il nostro primo giorno ci siamo subito cimentati nell'M5CoreS3, cercando di capire il funzionamento e il possibile utilizzo della sua interfaccia SD. L'obbiettivo stava nel riuscire a scrivere e leggere un file di testo 
contenuto nella scheda SD tramite l'ambiente di programmazione Arduino. Siamo partiti sfruttando l'esempio di codice fornito sul sito dal quale poter acquistare e visualizzare le caratteristiche del dispositivo. Per poter 
utilizzare il codice è stato necessario cercare e successivamente installare la scheda adatta, vale a dire quella dell'M5CoreS3. Oltre questo è stato necessario implementare alcune librerie che han reso possibile il corretto 
funzionamento del programma. Nell'utilizzo del programma sono state riscontrate diverse difficoltà, in primis la non conoscenza di parti del codice. Dopo aver effettuato diverse ricerche e soprattutto prove, abbiamo 
iniziato a comprendere ciò che il programma svolgeva senza interruzioni nell'esecuzione del programma. L'intento successivo è quello di riuscire a sostituire una semplice parola o frase con un clock. Cercheremo anche 
di approfondire meglio il codice per testare le diverse dinamiche, ad esempio in caso la scheda SD non fosse inserita o che non esista un file al suo interno nel quale scrivere. 

GIORNO 2
Oggi abbiamo cominciato a capire il funzionamento del dispositivo M5Stamp S3, l'obiettivo principale è riuscire a utilizzarlo per raccogliere valori analogici e trascriverli su una scheda SD. Prima di poter raccogliere i valori, però, abbiamo iniziato a concentrarci sulla prima sfida: riuscire a creare un canale di comunicazione tra l'M5Stamp S3 e il MicroSD Module, che consiste praticamente nel creare un collegamento tra i due. La prima difficoltà riscontrata è stata quella di lavorare su un dispositivo presente sul mercato da relativamente poco tempo, e questo fa sì che si riescano a trovare altrettante poche informazioni su di esso e sul suo funzionamento, a maggior ragione se si considera un collegamento con scheda SD. Abbiamo provato a utilizzare il codice che avevamo usato il giorno 1 per la scrittura e lettura di un file di testo su scheda SD con l'M5CoreS3, ma non ha funzionato, restituendoci diversi errori. Quest'ultimi sono stati attribuiti al fatto che probabilmente tra i due disposiivi la sintassi da utilizzare non è la stessa. 
