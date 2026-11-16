---
layout: single
title: PERSONAL PROJECTS
permalink: /progetti/
author_profile: true
---

## VIDEO GAME DIGITAL PRESERVATION PIPELINE

I independently designed and developed an end-to-end, modular Python infrastructure compliant with the OAIS reference model (ISO 14721) for the long-term preservation of DRM-free video games. The pipeline automates forensic metadata extraction from Windows binaries (PE Headers) and original offline installers (SIP), translating technical attributes into XSD-validated XML records adhering to international archival standards (Dublin Core, MODS, and PREMIS). To ensure ongoing data integrity and accessibility, the system integrates a relational SQLite database, automated SHA-256 cryptographic fixity auditing to prevent bit-rot alongside historical Condition Reporting, self-contained BagIt archival packaging, and an interactive web dashboard deployed on Streamlit Cloud.

**Explore the Live Demo:** [https://game-preservation-pipeline.streamlit.app/]

**View Source Code on GitHub:** [https://github.com/alessandro-mantoan-dp/Game_Preservation_Pipeline]