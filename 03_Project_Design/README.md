# Project Design

Project: Implement Client Script & UI Policy (Incident)

## Design Overview

The project uses ServiceNow Incident Management to control incident form behavior based on the Impact field.

## Main Components

1. UI Policy – High Impact Control
2. UI Policy Action – Assignment Group
3. UI Policy Action – Urgency
4. onChange Client Script – Automatically sets Urgency to High
5. onSubmit Client Script – Prevents saving when Assigned To is empty
6. onCellEdit Client Script – Prevents State changes through list editing

## Working Flow

Impact = High
        ↓
UI Policy is triggered
        ↓
Assignment Group becomes mandatory
        ↓
Urgency becomes read-only
        ↓
Urgency is automatically set to High
        ↓
Assigned To is checked before saving
        ↓
Incident is saved only when the required condition is satisfied
