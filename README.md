Carosello Array di Oggetti
===
Dato un array di oggetti letterali con:
 - url dell’immagine
 - titolo
 - descrizione
Creare un carosello come nella foto allegata o come il vostro già realizzato.

**Milestone 0:**
Come nel primo carosello realizzato, focalizziamoci prima sulla creazione del markup statico: costruiamo il container e inseriamo l’immagine grande in modo da poter stilare lo slider.

**Milestone 1:**
Ora rimuoviamo i contenuti statici e usiamo l’array di oggetti letterali per popolare dinamicamente il carosello.
Al click dell’utente sulle frecce verso sinistra o destra, l’immagine attiva diventerà visibile e dovremo aggiungervi titolo e testo.

**Milestone 2:**
Aggiungere il **ciclo infinito** del carosello.** Ovvero se la miniatura attiva è la prima e l’utente clicca la freccia verso destra, la miniatura che deve attivarsi sarà l’ultima e viceversa per l’ultima miniatura se l’utente clicca la freccia verso sinistra.

**BONUS 1:**
Aggiungere le thumbnails (sottoforma di miniatura) ed al click attivare l’immagine corrispondente.

**BONUS 2:**
Aggiungere funzionalità di autoplay: dopo un certo periodo di tempo (3 secondi) l’immagine attiva dovrà cambiare alla successiva.

**BONUS 3:**
Aggiungere bottoni di start/stop e di inversione del meccanismo di autoplay.

## Svolgimento
1. Creare il markup statico del carosello
2. Svuotare il contenuto del markup statico (slider e thumbnails)
3. Creare un array di oggetti e, tramite un ciclo forEach, popolare dinamicamente il carosello
4. Inserire in una collection tutti gli elementi creati e rendere attivo il primo elemento
5. Creare la logica per lo scorrimento al click con ciclo infinito
6. Aggiungere con setInterval la funzionalità autoplay ogni 3000ms
7. Aggiungere bottone di start/stop della funzionalità autoplay
8. Aggiungere bottone di inversione dell'autoplay

