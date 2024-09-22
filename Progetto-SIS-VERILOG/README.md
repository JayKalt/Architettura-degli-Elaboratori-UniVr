# README
# Architettura degli Elaboratori - Progetto SIS, Verilog - 2024

Repository del progetto del corso di Architettura degli Elaboratori, dipartimento di Informatica dell'Università di Verona (UniVR) nell'anno accademico 2024. Questo progetto si concentra sulla creazione di un sistema per il gioco della Morra Cinese.
## Struttura della Repository

```
main/
├── sis/
│   ├── non_ottimizzato/
│   │   ├── file_non_ottimizzato1.blif
│   │   ├── file_non_ottimizzato2.blif
│   │   └── ...
│   ├── FSMD.blif
│   ├── output_sis.txt
│   └── testbench.script
├── verilog/
│   ├── design.sv
|   ├── output_verliog.txt
|   └── testbench.sv
├── README.md
├── SIS2024.blif
├── Relazione.pdf
├── Relazione.tex
└── datapath.circ
```

- **design.sv**: Contiene la descrizione in linguaggio hardware Verilog del sistema FSMD per il gioco della Morra Cinese.
- **testbench.sv**: Include il testbench per la verifica del sistema FSMD.
- **Moduli .blif**: I moduli .blif relativi alla progettazione a livello di gate in SiS sono disponibili nella directory `sis/non_ottimizzato`.
- **Relazione**: La relazione è disponibile in formato PDF all'interno della direcotry `main/`.

## Istruzioni per l'Esecuzione

1. Assicurati di avere un ambiente di sviluppo Verilog/SiS configurato.
2. Esegui il file `design.sv` per sintetizzare il sistema FSMD.
3. Utilizza il file `testbench.sv` per eseguire test approfonditi e verificare il corretto funzionamento del sistema.

## Crediti
JayKalt<br>
@diegoarroyocamara (github.com/diegoarroyocamara)
