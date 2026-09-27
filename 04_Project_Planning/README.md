# # Project Planning

Project: Implement Client Script & UI Policy (Incident)

## Implementation Plan

The project will be completed through the following activities:

1. Configure the High Impact Control UI Policy.
2. Set Assignment Group as mandatory under the required condition.
3. Configure the Urgency UI Policy Action.
4. Develop the onChange Client Script for automatic Urgency assignment.
5. Develop the onSubmit Client Script for Assigned To validation.
6. Develop the onCellEdit Client Script for State control.
7. Perform functional testing on Incident records.
8. Verify the reverse condition for non-High Impact Incidents.
9. Verify both list-based and form-based State updates.
10. Capture screenshots of configuration and testing.

## Testing Approach

The implementation will be checked using:

- High Impact Incident with missing required information
- Valid High Impact Incident
- Change from High Impact to Medium Impact
- Direct State editing from the Incident list
- State modification through the Incident form

## Expected Result

The completed configuration should provide controlled field behavior and validation within the ServiceNow Incident module.
