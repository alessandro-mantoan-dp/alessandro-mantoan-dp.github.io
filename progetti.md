---
layout: single
title: PERSONAL PROJECTS
permalink: /progetti/
author_profile: true
---

## DIGITAL FILM ARCHIVING SYSTEM AND ONLINE-ACCESSIBLE RELATIONAL DATABASE

I have independently developed a digital film archiving system, based on the OAIS preservation model and on relational databases accessible online through a web interface.
The project involves the use of Python scripts for renaming and ingesting audiovisual material in digital format within the archive structure (three information packages, SIP/AIP/DIP), the generation of descriptive and preservation XML metadata for the film and its constituent scenes (MODS/PREMIS/DC), and the construction of an accessible and queryable database.

In detail, the workflow involves:

- Creation of a digital archive following the SIP/AIP/DIP structure, compliant with the OAIS model
- Segmentation of the film into its individual constituent scenes (using DaVinci Resolve)
- Python scripts for renaming and ingesting the complete film and reference scenes/frames into the digital archive
- Python scripts for creating and managing descriptive and preservation metadata, following the MODS and PREMIS model for the complete film / DC for individual scenes
- Creation of a relational database including technical data related to the film and individual scenes
- Web search interface with filters, viewing player, and XML metadata
- FastAPI backend
- Python scripts for automatic data synchronization and updating

The project, still under continuous development, is accessible at the following link

<https://felix-archive.onrender.com/>