<div align="center">
  <img width="615" height="206" alt="numislib-logo" src="https://github.com/user-attachments/assets/c8ff7214-a370-4977-9fa0-67dcdf1dc6a1" />
</div>

**Systematic Numismatic Archive & Relational Currency Database**

NumisLib is a private project dedicated to documenting global currency systems using a strictly relational approach. Unlike traditional flat lists, this archive focuses on the historical and territorial connections between countries, eras, and their respective currencies.

## Core Principles

* **Relational Integrity:** Every entry is linked to its historical predecessor or successor to map the evolution of currency areas.
* **Manual Curation:** Data is researched and entered manually via SQL scripts. No automated scraping is used, ensuring high data validity and verified technical specifications (material, weight, dimensions).
* **Open Data:** All researched datasets are made available as raw SQL or SQLite files for integration into other projects.

## Technical Stack

**Database**:  SQLite <br>
**Frontend**:  Next.js, TypeScript, Tailwind CSS

## Database Schema Overview

The database is structured to maintain strict referential integrity across several core entities:

* **Territories:** Historical and modern sovereign states, dependencies, and currency unions.
* **Currencies:** Chronological currency phases including `era_since` and `era_until` constraints.
* **Denominations:** Physical specifications of coins and banknotes (material, mass, diameter).
* **Production:** Minting statistics, mint marks, and designer metadata.

Look at a visual schema of the db [here](https://numislib.com/database/schema)

## Data Access

The project follows an Open Data approach. The following resources are updated periodically:

* **SQLite Dumps:** The production-ready database file.
* **SQL Scripts:** DDL and DML scripts (Schema & Inserts) for PostgreSQL/MariaDB compatibility.
* **API:** Programmatic access to the curated datasets via npm-package (Coming soon).

## About

NumisLib is maintained by <a href="https://github.com/lpj-app">Luca-Pascal Junge</a>

---

**Resources:**

* [Project Website](https://numislib.com)
* [Developer Portfolio](https://portfolio.lpj.app)
* [Contact](https://lpj.app/contact)

---

<p align="center">
since 2025. © <a href="https://github.com/NumisLib">NumisLib</a>, All rights reserved. Independent Research & Archiving
</p>
