# Project Development

Project: Implement Client Script & UI Policy (Incident)

## Development Activities

### Task 1: Create UI Policy
A UI Policy named "High Impact Control" was created for the Incident table.

Condition:
Impact is 1 - High

The Assignment Group field was configured as mandatory when the condition is satisfied.

### Task 2: Configure UI Policy Action
A UI Policy Action was created for the Urgency field.

Configuration:
- Field: Urgency
- Read-only: True
- Visible: Unchanged

### Task 3: Create onChange Client Script
An onChange Client Script named "Auto set urgency for high impact" was created for the Impact field.

When Impact is changed to High, the Urgency field is automatically set to High.

### Task 4: Create onSubmit Client Script
An onSubmit Client Script named "Prevent save if Assigned To missing" was created.

For High Impact incidents, the script prevents submission when the Assigned To field is empty.

### Task 5: Create onCellEdit Client Script
An onCellEdit Client Script named "Prevent state change via list edit" was created for the State field.

It prevents direct State changes through list editing and asks the user to open the Incident record.

## Development Result

All required UI Policies and Client Scripts were configured in the ServiceNow Incident module according to the project requirements.
