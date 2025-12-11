DDL completo:
Qui trovi l'intero codice SQL per creare il database da zero. Include:
Definizione delle tabelle con colonne, tipi di dato e chiavi primarie/esterne.
Script di INSERT per i dati di esempio e di test.
Vincoli di integrità (CHECK, UNIQUE, NOT NULL).
Trigger per automazioni (es. controlli su modifiche, sequenze automatiche).
Eventuali viste, indici e procedure PL/SQL.
Per usarlo: Esegui gli script in sequenza su Oracle SQL Developer o tool simile.

DMP:
Contiene il file di dump completo del database (formato Oracle DMP).
Questo permette un restore rapido dell'intero schema con dati, vincoli e oggetti.
Per usarlo: Importa con impdp o Data Pump in Oracle (impdp C##gestione/GEST0025@localhost:1521/xe directory=DATA_PUMP_DIR dumpfile=ORACLE_DB_GESTIONE.dmp).

Schermate_TEST_DB:
Cartella con screenshot e immagini dei test eseguiti.
Mostra query di verifica, risultati di SELECT complessi, esecuzione di trigger e controlli di integrità con i dati inseriti.
Utile per validare il funzionamento del database e riprodurre i test.

Modelli del Database:
ModelloER (Entità-Relazioni): Diagramma concettuale che mostra entità, attributi e relazioni 
ModelloRelazionale: Rappresentazione logica in 3NF, con tabelle, chiavi primarie/esterne e vincoli di integrità.

