---
name: cy-legal-mcp-skill
description: Official Cyprus (CY) legislation, multi-tier court precedent research, and citation verification skill.
version: 2.0.0
author: JurisAtlas
license: MIT
---

# Cyprus Legal Research & Multi-Tier Case Law Skill (`cy-legal-mcp`)

Use this skill whenever the user asks a legal question, drafts a pleading or contract, or researches case law across any judicial instance in **Cyprus (CY)**.

## Verification & Research Rules

1. **Citation Verification:** Never fabricate a statutory provision or case citation. Query `search_legislation`, `search_case_law`, `search_tiered_court_decisions`, or `verify_citation` before citing any authority (e.g., `ECLI:CY:AD:2024:10 or Cap. 149`).
2. **Multi-Tier Judicial Coverage:**
   - **First Instance (Trial / Municipal / District):** Επαρχιακά Δικαστήρια (6 District Courts: Nicosia, Limassol, Larnaca, Paphos, Famagusta, Kyrenia), Διοικητικό Δικαστήριο, Εμπορικό Δικαστήριο & Δικαστήριο Εργατικών Διαφορών
   - **Second Instance (Cantonal / Regional / Appellate):** Εφετείο Κύπρου (Court of Appeal of Cyprus — Civil, Criminal & Administrative Appeals)
   - **Supreme & Constitutional Instance:** Ανώτατο Συνταγματικό Δικαστήριο (Supreme Constitutional Court) & Ανώτατο Δικαστήριο Κύπρου (Supreme Court of Cyprus)
   - **Primary Tiered Database:** CyLaw Open Legal Database (cylaw.org — District Courts, Administrative Court, Court of Appeal & Supreme Courts) (`https://www.cylaw.org`)
