# Obiettivi

1. Parole più frequenti per ogni sentimento

2. Valutare quale soluzione tra MySQL o MongoDB sia la migliore per svolgere questo task.
   - **Utilizzazione Map-Reduce su MongoDB**

# Dubbi

- Come fare tutta la parte di lemming stemming cazzi e mazzi (slide sulle linee-guida)
- Come fare quello che ci sta di seguito

```**Includere:**
1. **il flusso delle operazioni svolte,** 
2. **la struttura dati adottata** 
3. **uno schema delle classi software sviluppate o utilizzate con:** 

***\*l'indicazione delle operazioni di cui si occupano\** \**le interfacce I/O con il resto del progetto.\**
 \4. \**i risultati ottenuti, in termini di:\**\**statistiche di uso delle risorse lessicali (percentuali delle parole di ciascuna risorsa presenti anche nei tweets)\** \**le word clouds per gli 8 sentimenti di annotazione dei Tweets (Anger,  Anticipation, Disgust, Joy, Fear, Sadness, Surprise, Trust)\**** ```   
```

1. Fare delle word cloud dove si mostrano le parole maggiormente gioiose e maggiormente sadness
2. Confronto in maniera visuale delle 2 word_cloud.

Ci sono 8 emozioni differenti:

- Joy
- Sadness
- Anger
- Disgust
- Fear
- Surprise
- Trust
- Anticipation

Obiettivo 2: Valutare quanto sono ancora attendibili i tesauri utilizzati per la ricerca. 

- Se non si trovano parole (soprattutto quelle di tipo gergale), si devono calcolare delle percentuali che evidenziano il fenomeno secondo il quale i tesauri non sono più attendibili per le finalità della ricerca.
  **Per ogni tesauro dire in che percentuale le parole presenti all'interno dei tesauri sono presenti anche nei tweets**

Alcuni studi associano le parole a una polarità (positiva o negativa), altre invece possono negare le parole successive (come rather - piuttosto che), o che aumentano l'importanza di quello che segue. - **TRASCURABILE**
