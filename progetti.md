---
layout: single
title: PROGETTI PERSONALI
permalink: /progetti/
author_profile: true
---

## SISTEMA DI ARCHIVIAZIONE DIGITALE DEL FILM E DATABASE RELAZIONALE ACCESSIBILE ONLINE

Ho sviluppato autonomamente un sistema  di archiviazione digitale del film, basato sul modello di preservazione OAIS e su database relazionali accessibili online tramite interfaccia web.
Il progetto prevede l'utilizzo di script Python per le operazione di rinomina e ingestione del materiale audiovisivo in formato digitale all'interno della struttura dell'archivio (tre pacchetti informativi SIP/AIP/DIP), la generazione di metadatazione XML descrittiva e conservativa del film e delle scene costituenti (MODS/PREMIS/DC) e la costruzione di un database accessibile e interrogabile.

Nel dettaglio, il workflow prevede:

- Creazione di un archivio digitale secondo la struttura SIP/AIP/DIP conforme al modello OAIS
- Segmentazione del film nelle singole scene costituenti (tramite DaVinci Resolve)
- Script Python per la rinomina e l'ingestione del film completo e delle scene/frames di riferimento all'interno dell'archivio digitale
- Scrypt Python per la creazione e gestione dei metadati descrittivi e conservativi, secondo il modello MODS e PREMIS per il film completo / DC per le singole scene
- Creazione di un database relazionale comprensivo dei dati tecnici relativi al film e alle singole scene
- Interfaccia di ricerca web con filtri, player di visualizzazione e metadatazione XML
- Backend FastAPI
- Script Python per sincronizzazione e aggiornamento automatica dei dati

Il progetto, in continua fase di lavorazione, è accessibile al seguente link

<https://felix-archive.onrender.com/>