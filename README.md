# AI Workshop - OpenEdge ABL Project

This project demonstrates the Business Entity architectural pattern for OpenEdge ABL applications.

## Overview

The project showcases:
- **Business Entity Pattern** — Layered architecture separating UI from database access
- **Singleton Factory** — Centralized entity lifecycle management
- **Dataset-based Data Transfer** — Temp-tables and datasets for UI/business layer communication
- **Validation Pattern** — Business rules encapsulated in entity classes

## Project Structure

```
src/
  business/
    CustomerEntity.cls    - Business entity for Customer table
    EntityFactory.cls     - Singleton factory for entity management
    CustomerDataset.i     - Dataset definition for Customer
  CustomerWin.w           - Refactored UI using business entity pattern
  ItemWin.w               - Legacy UI (candidate for refactoring)
doc/
  business-entity-pattern.md - Architecture documentation
dump/
  sports2000.df           - Database schema definition
```

## Prerequisites

- OpenEdge 12.8+
- Sports2000 sample database

## Getting Started

1. Clone this repository
2. Create the Sports2000 database: `ant db`
3. Open in PDSOE or your preferred ABL IDE
