# Consegna chat madre — Correzioni sulla prova 1.7.0.P08 (04/11/2026)

**Modello per la chat madre:** Sonnet 5.5 (coordinamento). Opus 5.5 solo per le figlie che cambiano la struttura.

## Stato
- Prova **1.7.0.P08** = P07 + pannello laterale uniforme + app in esercizio 1.6.0.051 unita.
- Zip `Urbanistica_1.7.0.P08_prova.zip` (348 voci), SHA-256 `196ca0d923d3ffd0e34f2cc7cd99ab3f4de4a36cc4c3354aec8937f4e658711f`.
- L'app sul server resta la 1.6.0.045/051: non cambia finché non si installa la versione finale.
- Collaudo P08: falliscono 6, 10, 17, 25, 29, 30, 63, 64, 66, 71, 79, 80, 81, 82, 100, 102 (la 71 da sola passa).

## Decisioni sul pannello (già applicate nella P08)
Linguette: Istruttoria (solo edilizia) · In redazione · Cartella · Note · Emessi. Word · PDF · Stacca · Nascondi sempre in questo ordine. Emessi = solo atti firmati e protocollati.

## Correzioni da fare (file `correzioni_04.11.26.docx`)

### Chat A — Opus 5.5 — Pratiche edilizie (PdC, SCIA, SCIA alternativa, CILA)
1. Sezione Documenti: se si flagga «sismica necessaria» e/o «paesaggistica necessaria», si attiva il flag in «Atti propedeutici». Il flag paesaggistica attiva anche «Soggetto a vincolo paesaggistico» in «Immobile e vincoli».
2. «Soggetti» e «Dati pratica» spostati nel punto 1 «Protocollo».
3. Cancellare «Vincoli e pareri necessari» al punto 5 «Conformità».
4. Punto 7 «Contributo di costruzione»: tolto dall'istruttoria e messo, con nome «Contributo di costruzione», al posto di «Attestazione di versamento del contributo di costruzione» in «Atti propedeutici».
5. Riquadro «Procedimento (Ordinario art. 146 / Semplificato D.P.R. 31/2017 all. B / Sanatoria artt. 167 e 181) + Per i seguenti interventi»: spostato (eliminandolo da dove sta) sotto «Autorizzazione paesaggistica» in «Atti propedeutici», solo se flaggata. Eliminare il messaggio azzurro. Messaggio giallo («Mancano gli estremi della precedente autorizzazione paesaggistica…»): **da confermare con Milvio**.
6. «Atti presupposti necessari»: pulsante «+» per aggiungere «n» atti non previsti.

### Chat B — Sonnet 5.5 — Suolo e Agente SUEDI
1. Suolo: Passi carrai e Anditi sono 2 procedimenti distinti → cronologici distinti, nessuna visualizzazione unica nell'elenco, ognuno con il suo elenco; resta il filtro «Tutti».
2. Agente SUEDI: colonna «Nome cartella», se non è una nuova pratica, aggiungere il nome del richiedente preso dal modulo 00.

## Chat aperte
- P09-A (Opus 5.5): `session_01TSedbgLvroUq3T4googZXE`
- P09-B (Sonnet 5.5): `session_01TSedbkKHG8rFZttYWrdiRj`
Ognuna aspetta da Milvio: zip P08, `consegna_1.7.0.P08_prova.md`, `riepilogo_2026-11-04_P08.md` (la A anche il docx delle correzioni).

## Dopo
Unire gli zip P09 (A) e P08b (B) in un'unica prova, poi collaudo completo con dati veri e zip 1.7.0 da installare sul server.

## Metodo
Dire sempre con quale modello fare i passi; costi bassi. A fine sessione: riepilogo.md nella cartella Drive «claude code» e decisioni durevoli in MYREE.
