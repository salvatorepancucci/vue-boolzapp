## Passaggi logici dello script

### Milestone 1
1. **Replica della grafica**
   - Impostare il layout di base con contatti a sinistra e chat a destra.
   - Creare due classi CSS diverse per i messaggi scritti dall'utente (verdi) e dall'interlocutore (bianchi).

2. **Visualizzazione dinamica della lista contatti**
   - Utilizzare `v-for` per visualizzare nome e immagine di ogni contatto.
   - Dichiarare variabili nel data per `contacts`.

### Milestone 2
3. **Visualizzazione dinamica dei messaggi**
   - Utilizzare `v-for` per visualizzare tutti i messaggi relativi al contatto attivo.
   - Dichiarare variabili nel data per `activeIndex` e computed property per `activeContact`.

4. **Click sul contatto mostra la conversazione del contatto cliccato**
   - Creare il metodo `setActiveContact(index)` per impostare il contatto attivo in base all'indice passato.

### Milestone 3
5. **Aggiunta di un messaggio**
   - Dichiarare una variabile `newMessage` per il testo del messaggio.
   - Creare il metodo `sendMessage()` per aggiungere un nuovo messaggio all'elenco dei messaggi del contatto attivo.

6. **Risposta dall’interlocutore**
   - Aggiungere una risposta automatica "Ok" dopo 1 secondo dall'invio del messaggio.

### Milestone 4
7. **Ricerca utenti**
   - Dichiarare una variabile `searchQuery` per il testo di ricerca.
   - Creare la computed property `filteredContacts` per filtrare i contatti in base alla query di ricerca.

### Milestone 5 (Opzionale)
8. **Cancella messaggio**
   - Creare un menu a tendina che permette di cancellare il messaggio selezionato.

9. **Visualizzazione ora e ultimo messaggio inviato/ricevuto nella lista dei contatti**
   - Creare il metodo `getLastMessage(messages)` per ottenere l'ultimo messaggio di una lista di messaggi.
