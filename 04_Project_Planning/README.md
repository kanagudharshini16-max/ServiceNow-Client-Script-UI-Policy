# Project Planning

Project: Implement Client Script & UI Policy (Incident)

## Project Plan

The project is planned in the following stages:

1. Create the High Impact Control UI Policy.
2. Configure the Assignment Group as mandatory when Impact is High.
3. Configure the Urgency field as read-only for High Impact incidents.
4. Create an onChange Client Script to automatically set Urgency to High.
5. Create an onSubmit Client Script to prevent saving when Assigned To is empty for High Impact incidents.
6. Create an onCellEdit Client Script to prevent State changes through list editing.
7. Test all configured UI Policies and Client Scripts.
8. Verify successful form-based updates and reverse conditions.
9. Capture screenshots of the configuration and testing results.
10. Organize the project evidence phase-wise in the GitHub repository.

## Testing Plan

The configuration will be tested for:

- Mandatory field enforcement
- Successful Incident save
- Reverse condition when Impact changes from High to Medium
- Blocking State changes through list editing
- Allowing State changes through the Incident form

## Expected Outcome

The project should provide dynamic field control, automatic field updates, validation during submission, and controlled State updates in the ServiceNow Incident module.
