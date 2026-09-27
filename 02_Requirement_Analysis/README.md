# Requirement Analysis

Project: Implement Client Script & UI Policy (Incident)

## Functional Requirements

The system should satisfy the following requirements:

1. Detect High Impact Incidents using a UI Policy.
2. Make the Assignment Group field mandatory for High Impact Incidents.
3. Restrict editing of the Urgency field when Impact is High.
4. Automatically assign High Urgency when Impact is set to High.
5. Validate the Assigned To field before saving a High Impact Incident.
6. Block direct State modification through list editing.
7. Permit State modification through the Incident form.

## Platform Requirements

- ServiceNow Developer Instance
- Incident Management module
- UI Policies
- UI Policy Actions
- Client Scripts

## Validation Requirements

The configured rules should be tested under different Incident conditions to ensure that the expected behavior occurs.
