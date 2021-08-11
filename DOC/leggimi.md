Srt Sottotitoli da testo
========================

Questa applicazione serve per ottenere rapidamente un file di sottotitoli da un file di testo che contiene la trascrizione di un file video o audio.

Il tempo necessario per creare il file è praticamente uguale alla durata del file video o audio in riproduzione.

Avvia la riproduzione e segui, scorrendo con il mouse il discorso sul testo, quando percepisci una pausa, ad esempio alla fine della frase, clicca sull'ultima parola pronunciata.  
Questa azione inserisce l'ora corrente nel testo.  

Ad esempio se clicchi sulla parola _Corona_ nella riga seguente

 

_Die Berliner Familie Burgdorff nach einem Jahr Corona:Alle sind zu Hause, alle beschäftigt am Computer - okay, fast alle. Leandro kämpft mit Mathematik._

la linea viene spezzata così:

 

_Die Berliner Familie Burgdorff nach einem Jahr Corona:  
:)00:00:09,531 = 9.531916(: Alle sind zu Hause, alle beschäftigt am Computer - okay, fast alle._

  
e poi se clicchi sulla parola _Computer_ , la riga originale diventa:

 

Die Berliner Familie Burgdorff nach einem Jahr Corona:  
:)00:00:09,531 = 9.531916(: Alle sind zu Hause, alle beschäftigt am Computer  
:)00:00:13,837 = 13.837164(: - va bene, veloce alle.

  

Nota che se non ci sono correzioni da fare non è necessario fermare la riproduzione che può continuare senza fermarsi fino alla fine.  
  
Al termine della riproduzione, premendo il pulsante **Scarica file** , viene scaricato un file di sottotitoli di tipo **srt** .  
  
Questo è l'output dell'esempio precedente:

 

1  
00:00:00.000 -> 00:00:09,531  
Die Berliner Familie Burgdorff nach einem Jahr Corona:  
         
2  
00:00:09,531 -> 00:00:13,837  
All sind zu Hause, alle beschäftigt am Computer  
         
3  
00:00:13,837 -> 00:00:16,379  
\- ok, veloce alle.  
 

Se una parola è stata cliccata nel momento sbagliato, puoi correggere:

 

ferma la riproduzione,  
sposta il cursore della linea di controllo video/audio indietro di alcuni secondi,  
riavvia la riproduzione e  
nell'esatto momento clicca di nuovo sulla stessa parola di prima.

in questo modo il nuovo timestamp andrà a sostituire quello precedente.

  
Se hai cliccato sulla parola sbagliata,

 

fai doppio click su questa parola,  
l'ora inserita verrà eliminata e la riga successiva verrà spostata nella posizione precedente.  
Ad esempio:  
:)00:00:09,531 = 9.531916(: Alle sind zu Hause, alle beschäftigt am Computer  
:)00:00:13,837 = 13.837164(: - va bene, veloce alle.

  
Se fai doppio click su _Computer_ ottieni:

 

00:00:09,531 = 9.531916(: Alle sind zu Hause, alle beschäftigt am Computer - okay, fast alle.