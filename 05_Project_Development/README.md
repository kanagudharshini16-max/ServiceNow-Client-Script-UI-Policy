# # Project Development

Project: Implement Client Script & UI Policy (Incident)

## Development Activities

### UI Policy Configuration

A UI Policy named "High Impact Control" was configured for the Incident table.

The policy is triggered when:

Impact = 1 - High

The Assignment Group field is controlled through the associated UI Policy Action.

### Urgency Field Control

A UI Policy Action was configured for the Urgency field.

The field is made read-only when the High Impact condition is active.

### Automatic Urgency Update

An onChange Client Script was configured for the Impact field.

When Impact is changed to High, the script sets Urgency to High automatically.

### Submission Validation

An onSubmit Client Script was created to check whether Assigned To has been provided for a High Impact Incident.

If the required value is missing, submission is prevented.

### State List Editing Control

An onCellEdit Client Script was configured for the State field.

It prevents users from changing the State directly through list editing and instructs them to open the Incident form.

## Development Outcome

The required UI Policies and Client Scripts were configured and integrated with the ServiceNow Incident module.
