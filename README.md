<pre>
██      ██   ██  ██████   ██████
██      ██   ██  ██   ██  ██   ██
██      ██   ██  ██████   ██████
██      ██   ██  ██   ██  ██   ██
███████  █████   ██████   ██████
                C L I
</pre>

# The LUBB Ecosystem: A Family of Applications for Quranic Data

This document outlines the family of applications and technologies that form the LUBB ecosystem. The central goal is to solve the fragmentation and lack of standardization in the digital Quranic content space.

[cite_start]The current ecosystem consists of siloed projects with incompatible data structures (e.g., Ayah-based vs. Word-based) [cite: 119, 123, 144, 148] [cite_start]and various non-standard schemas from different publishers[cite: 158, 162]. [cite_start]This fragmentation forces developers to build complex, custom logic to map and unify data [cite: 186, 189][cite_start], which hinders innovation, performance, and compatibility[cite: 191, 192]. [cite_start]This problem is exponentially more complex when trying to manage multiple Qira'at (Recitations)[cite: 198].

[cite_start]The LUBB project provides a unified, open, and extensible "reactor-like core system" [cite: 21] [cite_start]to act as the backbone for all future Quranic technology, applications, and research[cite: 22].

---

## The LUBB Family of Applications

The ecosystem is comprised of several specialized, integrated applications that each handle a critical part of the data lifecycle. All applications and products are built to integrate with LUBB as the central core.

### LUBB (لب) - The Core

[cite_start]LUBB is the central engine and unified data lakehouse[cite: 314]. It is the deep technology for storing, processing, linking, structuring, and exporting Quranic data in real-time. [cite_start]It contains the unified database that maps all layers of Quranic content [cite: 323][cite_start]—from the character (الحرف) [cite: 355] [cite_start]and word (الكلمة) [cite: 363] [cite_start]up to the Ayah (الآية) [cite: 369][cite_start], Surah (السورة) [cite: 371][cite_start], and Mushaf (المصحف)[cite: 373].

### MARQOUM (مرقوم) - The Standard

MARQOUM is the unified system of technical and Quranic standards. [cite_start]It acts as a data inspector [cite: 265] [cite_start]and validation machine for all data inputs [cite: 264][cite_start], ensuring that all content ingested into the ecosystem is compliant, categorized [cite: 267][cite_start], and standardized[cite: 268]. [cite_start]This component is essential for solving the core problem of varying and contradictory schemas[cite: 158, 198].

### MUNAJAM (منجَّم) - The Ingestor

[cite_start]MUNAJAM is the data analysis and ETL (Extract, Load, Transform) machine[cite: 248, 249]. It is responsible for:
* [cite_start]**Analyzing** disparate Quranic datasets (both audio and written)[cite: 246].
* [cite_start]**Schema Matching** to map data from various publishers to the MARQOOM standard[cite: 247].
* [cite_start]**Data Ingestion** and layering to feed standardized data into the LUBB core[cite: 250, 252].

### JAMIEE (جامع) - The Processor

[cite_start]JAMIEE is the data processing and indexing engine[cite: 255]. After data is ingested by MUNAJAM and validated by MARQOUM, JAMIEE handles the complex backend tasks of:
* [cite_start]Initializing reference frames[cite: 256].
* [cite_start]Running data processing units[cite: 260].
* [cite_start]Generating the mappings and indices that create the interconnected layers within the LUBB unified database[cite: 261, 262].

### RAQIEB (رقيب) - The Guardian

[cite_start]RAQIEB is the community and digital rights management system[cite: 271]. [cite_start]A key objective of LUBB is to be a community-driven project[cite: 15, 29]. RAQIEB manages this by:
* [cite_start]Handling community-generated content from editors, authors, and contributors[cite: 272, 273, 274].
* [cite_start]Managing copyrights [cite: 283] [cite_start]and digital asset licenses (e.g., ITQAN IP License [cite: 280][cite_start], MIT/GPL [cite: 288]).
* [cite_start]Creating a "Chain of Rights" that is blockchain-ready [cite: 286] to ensure transparency and proper attribution for all contributions.

---

## Ecosystem Integration Flow

All products and applications in this family are designed to work together, with **LUBB** as the central integration point.

1.  [cite_start]**MUNAJAM** ingests raw data (e.g., CSVs, audio files, text) from various publishers[cite: 249, 296, 302, 309].
2.  [cite_start]**MARQOUM** validates this data against the unified standards[cite: 264].
3.  [cite_start]**JAMIEE** processes, maps, and indexes the validated data[cite: 260, 261].
4.  [cite_start]**LUBB** stores and orchestrates this data in its unified data lakehouse[cite: 313, 314, 322].
5.  [cite_start]**RAQIEB** manages all community contributions and associated digital rights for content entering the ecosystem[cite: 271, 283].

[cite_start]External applications, developer tools, and other community projects (like those in the ITQAN community) [cite: 40] [cite_start]then connect directly to **LUBB** to access the standardized, unified Quranic data[cite: 322].

---

## LUBB Core Demos

You can find demo videos of the early version of the LUBB core on Google Drive.

* **Demo 1:** [Link to Part 1 on Google Drive](https://drive.google.com/file/d/1EKb-QPKtETU5VlEkw-aOlCBdqekIPFVf/view?usp=drive_link)
* **Demo 2:** [Link to Part 2 on Google Drive](https://drive.google.com/file/d/1K6-YJM1NVFv4P-vHNFKSu80Sw4k3327u/view?usp=drive_link)
* **Demo 3:** Upcoming
