<pre>
██      ██   ██  ██████   ██████
██      ██   ██  ██   ██  ██   ██
██      ██   ██  ██████   ██████
██      ██   ██  ██   ██  ██   ██
███████  █████   ██████   ██████
                C L I
</pre>

<p align="center">
  <a href="#lubb-products-range-and-application-suite">Products Range</a> •
  <a href="#ecosystem-integration-flow">Integration Flow</a> •
  <a href="#lubb-core-demos">Demos</a>
</p>

# The LUBB Ecosystem: A Family of Applications for Quranic Data

This document outlines the family of applications and technologies that form the LUBB ecosystem. The central goal is to solve the fragmentation and lack of standardization in the digital Quranic content space.

The current ecosystem consists of siloed projects with incompatible data structures (e.g., Ayah-based vs. Word-based) and various non-standard schemas from different publishers. This fragmentation forces developers to build complex, custom logic to map and unify data, which hinders innovation, performance, and compatibility. This problem is exponentially more complex when trying to manage multiple Qira'at (Recitations).

The LUBB project provides a unified, open, and extensible "reactor-like core system" to act as the backbone for all future Quranic technology, applications, and research.

---

## LUBB Products Range and application suite

The ecosystem is comprised of several specialized, integrated applications that each handle a critical part of the data lifecycle. All applications and products are built to integrate with LUBB as the central core.

### LUBB (لب) - The Core

The deep technology for storing, processing, linking, structuring, and exporting Quranic data in a real-time, unified manner, compliant with Quranic and technical standards.

### MARQOOM (مرقوم) - The Standard

The unified system of technical and Quranic standards that acts as a machine to validate all data inputs.
* **Status:** First version released in writing; content for the second version is in preparation.

### MUNAJAM (منجَّم) - The Ingestor

An analysis machine for segmenting and tagging audio and written Quranic data. It inputs this data into LUBB, links and tags it according to the standards defined in MARQOOM, and passes it all to the unified database.

### MODMAJ (مُدمج) - The Unified Database

The unified database that connects all dimensions and layers of Quranic data in a standardized way. This includes Qira'at (readings) and Riwayat (narrations) across the different levels and dimensions of Quranic data: written, pronounced, and recited.

### NASEEJ (نسيج) - The Data Language

The unified standard technical data language for exchanging informational outputs between LUBB technologies and the family of applications built on the same ecosystem. This covers the entire lifecycle, from the initial creation of Quranic resources and their preparation for developers, all the way to their delivery to the end-user.

### JAMIEE (جامع) - The Processor

The data processing and indexing engine. After data is ingested by MUNAJAM and validated by MARQOOM, JAMIEE handles the complex backend tasks of initializing reference frames, running data processing units, and generating the mappings and indices that create the interconnected layers within MODMAJ.

### RAQIEB (رقيب) - The Guardian

The community and digital rights management system. RAQIEB manages community-generated content, copyrights, and digital asset licenses (e.g., ITQAN IP License, MIT/GPL). It is designed to create a "Chain of Rights" that is blockchain-ready to ensure transparency and proper attribution for all contributions.

---

## Ecosystem Integration Flow

All products and applications in this family are designed to work together, with **LUBB** as the central integration point.

1.  **MUNAJAM** ingests raw data (e.g., CSVs, audio files, text) from various publishers.
2.  **MARQOOM** validates this data against the unified standards.
3.  **JAMIEE** processes, maps, and indexes the validated data.
4.  **LUBB** orchestrates this data, which is stored in **MODMAJ**, the unified database.
5.  **RAQIEB** manages all community contributions and associated digital rights for content entering the ecosystem.
6.  **NASEEJ** provides the standard data language for external applications, developers, and other community projects to consume this unified data.

---

## LUBB Core Demos

You can find demo videos of the early version of the LUBB core on Google Drive.

* **Demo 1:** [Link to Part 1 on Google Drive]
* **Demo 2:** [Link to Part 2 on Google Drive]
* **Demo 3:** Upcoming
