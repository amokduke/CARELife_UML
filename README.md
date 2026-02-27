# CARE-LIFE Architecture (D4GX)

## Purpose

This folder contains the current structural baseline for the CARE-LIFE operating model.

These artefacts define:

- System behaviour (Use Cases)
- Core data relationships (Entity Relationship Diagrams)
- Implementation schema (Data Dictionary)

This represents the working architecture ahead of **Meeting 3**, where the objective is to align and lock the core data model structure.

---

## Files in This Folder

### 1. UML File  
**File:** `CaringSG_D4GX_CARE-Life_UML_drawio.xml`

**Contains:**
- Use Case Diagram (actors and workflows)
- Entity Relationship Diagrams (core data model)

**How to open:**
1. Go to https://app.diagrams.net  
2. Click **Open Existing Diagram**  
3. Upload the XML file  
4. Navigate between diagram tabs (Use Case / ERD)

draw.io is free and web-based. No installation required.

---

### 2. Data Dictionary  
**File:** `CaringSG_D4GX_CARE-Life_DataDictionary.xlsx`

**Defines:**
- Table names
- Field names
- Field types
- Relationships
- Descriptions

The schema is structured for **Airtable implementation**.

Field types follow Airtable conventions such as:
- Single line text  
- Linked record  
- Single select  
- Multi-select  
- Checkbox  
- Date  
- Formula  

Each row represents one field within a table.

---

## Scope and Current Status

This architecture reflects current baseline thinking, including:

- Stable **Person** object
- **FamilyUnit** structure
- Caregiver–Recipient relationships
- Continuity / succession support concepts

The Signals / Domains / Indicators framework is still under discussion and not yet finalised.

---