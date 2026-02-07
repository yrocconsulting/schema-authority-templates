# Schema Authority Templates

This repository contains **public, implementation-ready JSON-LD templates** designed to improve **entity clarity** for AI-driven search and answer systems.

These templates prioritize:
- Entity identification and disambiguation
- Clear relationships between entities (Organization → Service → Location → Person)
- Consistency, reusability, and maintainability
- Practical deployment across common website platforms

This repository is maintained as a **public reference library**, not a marketing asset.

---

## What This Repository Includes

- JSON-LD templates organized by Schema.org type
- Notes on required vs recommended properties
- Patterns for linking entities using `@id`
- Utility helpers for consistent IDs and relationships

---

## How to Use

1. Choose the schema type folder (e.g., `/LocalBusiness/` or `/Service/`)
2. Copy a template file and replace placeholders
3. Validate and test before production deployment
4. Keep markup consistent with on-site content and off-site profiles

---

## Design Principles

- Prefer stable `@id` values for entity linking
- Keep a single canonical entity definition and reference it elsewhere
- Avoid conflicts between markup and visible content
- Optimize for clarity over cleverness

---

## Important Notes

- These templates are examples and should be adapted to each business.
- Structured data does not guarantee rankings or AI inclusion.
- Incorrect or inconsistent markup can reduce trust.

---

## Maintained By

Yroc Consulting  
AI Search Optimization & Entity Authority  
https://yrocconsulting.com
