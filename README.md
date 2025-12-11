# Faculty Publication Management Prototype

This repository contains a prototype workflow and documentation for managing faculty publication data from messy, heterogeneous sources into a clean, deduplicated, and citation ready corpus.

The project focuses on:

- Designing a sustainable architecture for collecting, cleaning, validating, and storing publication records.

- Combining rule-based methods, authoritative external services (e.g., Crossref), and carefully scoped AI assistance.

- Supporting downstream use cases such as reporting, trend analysis, and Bluebook-style bibliographies.

  
## Key Objectives

Ingest publication data from multiple sources (databases, CVs, web pages, self-reporting forms).

Assess and profile the quality of the collected data.

Standardize and validate core fields (names, titles, dates, types, identifiers).

Deduplicate records and enrich them with missing identifiers (DOI, ISSN, ISBN, URLs).

Separate staging data (raw + semi-processed) from a validated repository of authoritative records.

Enable search, filtering, and (optionally) semantic discovery over the validated corpus.

