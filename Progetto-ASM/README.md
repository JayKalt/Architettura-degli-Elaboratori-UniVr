# README
# Architettura degli Elaboratori - Progetto Assembly - 2024
Repository del progetto del corso di Architettura degli Elaboratori, dipartimento di Informatica dell'Università di Verona (UniVR) nell'anno accademico 2024. Questo progetto si concentra sulla creazione di un pianificatore per la produzione di prodotti.

## Struttura della Repository
- **bin/**: directory contenente il file binario (solo dopo aver eseguito ```make```)
- **obj/**: directory contenente i file oggetto
- **src/**: directory contenente i file sorgente
- **Ordini/**: directory contenente i .txt per il testing
- **Makefile**: file di creazione automatica
- **Relazione**: relazione del progetto
- **ASM2024.pdf**: consegna del progetto

## Istruzioni per l'Esecuzione:
1. Assicurarsi di avere un ambiente di sviluppo Assembly GNU, Linker LD, Linux Kernel 2.2, configurato
2. Aprire il terminale nella direcotry principale
3. Digitare ```make``` per compilare automaticamente i file sorgente tramite GAS (GNU Assembler) e assemblarli tramite il LD (GNU linker)
4. Digitare  ```path/to/bin path/to/input_file.extension path/to/output_file.extension``` per avviare il programma
5. Premere ```3``` per terminare l'esecuzione del programma
6. Una volta terminato l'utilizzo del programma, se si desidera, utilizzare il comando ```make clean``` dalla direcotry principale per ripulire il contenuto delle cartelle ```bin/``` e ```obj/``` 


## Crediti:
JayKalt<br>
Samy El Ansari
