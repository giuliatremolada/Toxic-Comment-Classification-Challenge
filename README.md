# AML Toxic Comments Kaggle Challenge

Frigerio Riccardo - 852226
Napoli Mattia - 852239
Tremolada Giulia - 861144

## Istruzioni

Quando la cartella viene condivisa via Drive appare nella sezione 'Condivisi con me'.
Per poter eseguire i notebook al suo interno e garantire che i path verso i file di train e test rimangano validi e' necessario creare una scorciatoia a quela cartella all'interno di 'Mio drive'.

La procedura e' la seguente:
* nella sezione `Condivisi con Me` selezionare la cartella `AML-Project-Frigerio-Napoli-Tremolada`
* cliccare con il tasto destro e selezionare `Organizza` > `Aggiungi scorciatoia` e infine selezionare il `Mio drive`
Questo aggiungera' la scorciatoria con il path corretto per consentire l'esecuzione dei notebook

## Struttura della Cartella

Il file `data_analysis.ipynb` contiene il codice utilizzato per testare il preprocessing del dataset, analizzarne il contenuto e tentare la data augmentation.

I rimanenti file hanno invece il compito di applicare il preprocessing al dataset, creare i modelli e testarli, calcolando infine le metrice di valutazione.

I dettagli dei file sono i seguenti:
* `transformers.ipynb`: si occupa di testare il modello basato su transformer contro embedding standard di keras, embedding con glove e fine tuning di glove
* `rnn.ipynb`: si occupa di testare la Bi-LSTM contro embedding standard di keras, embedding con glove e fine tuning di glove
* `cnn.ipynb`: si occupa di testare la CNN contro embedding standard di keras, embedding con glove e fine tuning di glove
* `fasttext.ipynb`: si occupa di testare il transformer, la Bi-LSTM e la CNN contro embedding con fasttext e fine tuning di fasttext

Ognuno di questi file e' autocontenuto e puo' essere eseguito in autonomia.
