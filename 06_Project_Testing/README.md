# Project Testing

Project: Implement Client Script & UI Policy (Incident)

## Testing Activities

### Test 1: Mandatory Enforcement
An Incident was created with Impact set to High and Assigned To left empty.

Result:
The Incident was prevented from being saved and the validation message was displayed.

### Test 2: Successful Save
The Assigned To field was filled for a High Impact Incident and the record was submitted.

Result:
The Incident was saved successfully and the configured field behaviors continued to work.

### Test 3: Reverse Condition
The Impact of an existing Incident was changed from High to Medium.

Result:
Assigned To was no longer mandatory and the Urgency field became editable.

### Test 4: List Edit Blocking
An attempt was made to edit the State field directly from the Incident list.

Result:
The alert message was displayed and the State value remained unchanged.

### Test 5: Form-Based Update
The State of an Incident was changed through the Incident form and the record was updated.

Result:
The State change was saved successfully.

## Testing Outcome

The configured UI Policies and Client Scripts were tested for field validation, automatic updates, reverse conditions, list-edit restrictions, and form-based updates.
