---
type: library
title: "Preset - Modello finanziario"
tags: ["preset", "finanza"]
related: ["preset-analisi-di-mercato-e-test", "preset-business-plan", "indice-manuale-operativo-founder"]
created: 2026-10-24
updated: 2026-10-24
---

# Preset - Modello finanziario

## Scopo
Far tornare i conti prima di spenderli. E' la sorgente unica dei numeri di business plan e pitch: i tre documenti devono raccontare le stesse cifre.

## Quando attivarlo
- Dopo un dossier di analisi di mercato e test con decisione "continua" o "cambia", per trasformare prove in numeri. Se la decisione del dossier e' "ferma", non attivare questo preset.
- Prima di ogni pitch, richiesta di finanziamento o impegno di spesa.

## Input necessari
Prezzi, volumi attesi, costi fissi e variabili, ipotesi di crescita. Ognuna con una fonte datata oppure marcata esplicitamente come ipotesi da validare. Le stime del dossier mercato e test hanno la precedenza su numeri presi altrove.

## Procedura
1. **Foglio delle ipotesi separato dai conti.** Prezzi, volumi, costi, tassi di crescita: ogni ipotesi ha fonte o e' marcata da validare.
2. **Ricavi = clienti x ricavo medio, mese per mese.** La crescita nasce dai driver (nuovi clienti, prezzo), non da una percentuale scritta a mano.
3. **Costi fissi e variabili**, poi margine di contribuzione per linea di ricavo.
4. **Conto economico riclassificato** fino all'EBITDA.
5. **Cash flow mensile**: quando entra e quando esce la cassa, non solo l'utile. Distingui il flusso di cassa del mese dal saldo cumulato ed etichetta ogni numero come flusso o saldo: i due non sono intercambiabili.
6. **Tre scenari**: prudente, base, ottimista.

## Output atteso
Un foglio di calcolo in cui cambiando un'ipotesi si aggiornano insieme margine, EBITDA e previsionale, cosi' business plan e pitch restano coerenti. Include data di revisione. Il foglio vive come file di calcolo (es. Google Sheets o Excel) collegato dalla pagina di progetto (fuori dal pacchetto): la pagina riporta solo sintesi, link e data di revisione. Se il foglio non esiste ancora, segnala al titolare che la sorgente unica manca: una tabella markdown vale come bozza temporanea marcata, non come sorgente unica.

## Controlli di qualita'
- Le cifre in numeri sono uguali alle cifre in lettere nei documenti derivati.
- La crescita dei ricavi torna moltiplicando i driver, senza eccezioni.
- Clienti x ricavo medio = fatturato, sempre.
- Gli indicatori sono calcolati sulle basi corrette: ROE = utile netto / patrimonio netto; margini = grandezza / fatturato del periodo corrispondente.
- Flussi di cassa mensili e saldi cumulati sono etichettati come tali e non scambiati.
- Nessun numero senza fonte passa come fatto: resta marcato come ipotesi.

## Perimetro
Non sostituisce il commercialista su forma giuridica, fiscalita' e adempimenti. Non e' una previsione certa: i risultati dei test lo aggiornano, non lo confermano per definizione.

## Collegamenti
- Alimentato da: [preset-analisi-di-mercato-e-test](preset-analisi-di-mercato-e-test.md).
- Alimenta: [preset-business-plan](preset-business-plan.md) (fase 2) e il futuro preset pitch deck.
- Indice: [indice-manuale-operativo-founder](indice-manuale-operativo-founder.md)

## Note per gli agenti
- Non inventare fonti o numeri di mercato: se un dato manca, marcalo "da validare" e segnalalo.
- Mantieni il foglio delle ipotesi separato: non scrivere numeri direttamente nelle formule.
- Ogni modifica a un'ipotesi va annunciata con motivazione e data.
- Se un numero del dossier mercato e uno del modello divergono, fermati e segnala la divergenza: il dossier ha la precedenza finche' il titolare non decide, e la correzione va registrata con motivazione e data.
