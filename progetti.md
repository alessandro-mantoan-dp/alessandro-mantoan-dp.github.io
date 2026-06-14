---
layout: single
title: PROGETTI
permalink: /progetti/
author_profile: true
---

## Sistema di archiviazione digitale e database relazionale accessibile online

Ho sviluppato autonomamente un sistema di archiviazione digitale applicando gli standard internazionali usati dalle istituzioni culturali di riferimento (OAIS, MODS, PREMIS) a corpus eterogenei di materiale storico-culturale contemporaneo.
Il progetto include la generazione automatica di metadati in formato XML tramite script Python e la costruzione di database relazionali accessibili online.

Nel dettaglio, il workflow prevede:

- Creazione di un archivio digitale secondo la struttura SIP/AIP/DIP conforme al modello OAIS
- Inventario e creazione di identificatori univoci per ogni oggetto archivistico
- Documentazione fotografica
- Script Python per l'ingest all'interno dell'archivio digitale
- Scrypt Python per la creazione e gestione dei metadati descrittivi e conservativi, secondo il modello MODS e PREMIS
- Creazione di un database relazionale
- Interfaccia di ricerca pubblica con filtri, paginazione ed export CSV
- Backend FastAPI per la gestione sicura delle credenziali
- Script Python per la sincronizzazione automatica dei dati

## Progetti in mostra

ARCHIVIO MTG
Sistema di catalogazione e preservazione digitale di una collezione privata di Magic: The Gathering, strutturato secondo il workflow precedente.
Il progetto intende fornire un esempio applicabile a diverse tipologie di oggetti archivistici.

<https://archivio-mtg.onrender.com/>