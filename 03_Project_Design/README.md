# Project Design

Project: Implement Client Script & UI Policy (Incident)

## Design Concept

The project is designed around the Impact field of an Incident. When the Impact value is High, specific field controls and validation rules are activated.

## Components Used

### 1. UI Policy
High Impact Control is used to apply conditional behavior to Incident fields.

### 2. UI Policy Actions
UI Policy Actions control the mandatory and read-only properties of selected fields.

### 3. onChange Client Script
This script responds when the Impact field is changed and automatically updates Urgency.

### 4. onSubmit Client Script
This script validates the Assigned To field before an Incident is submitted.

### 5. onCellEdit Client Script
This script prevents direct State modification from the Incident list.

## Basic Flow

Impact changed
↓
Condition is checked
↓
Field behavior is applied
↓
Urgency is updated when required
↓
Submission is validated
↓
Incident is saved or rejected according to the conditions
