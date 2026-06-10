# Export Individual Permit Document

**Location:** Project Homepage > Reports > Export Individual Permit Document

---

## Functional Description

The Export Individual Permit Document feature allows an authorized user to generate a document for a selected chainsaw registration record. The exported document includes relevant owner information, chainsaw details, registration information, permit dates, and inspection images when available. This feature helps users prepare a record-based permit document for documentation and reporting purposes.

---

## Use Case Scenario

| Field          | Description                                                                                                                                                                                                                                                                                                                                  |
| -------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Use Case ID    | UC-EXP-01                                                                                                                                                                                                                                                                                                                                    |
| Use Case Name  | Export Individual Permit Document                                                                                                                                                                                                                                                                                                            |
| Actor          | Authorized User                                                                                                                                                                                                                                                                                                                              |
| Precondition   | The user is logged in and at least one chainsaw registration record exists in the system.                                                                                                                                                                                                                                                    |
| Trigger        | The user selects a record and clicks the export document action.                                                                                                                                                                                                                                                                             |
| Main Flow      | 1. The user opens the Chainsaw Records page or record details. <br> 2. The user selects a specific chainsaw record. <br> 3. The user clicks the export document action. <br> 4. The system retrieves the selected record information. <br> 5. The system generates a document containing the record details and available inspection images. |
| Alternate Flow | If the document cannot be generated or the selected record is unavailable, the system displays an error message.                                                                                                                                                                                                                             |
| Postcondition  | An individual permit document is generated for the selected chainsaw record.                                                                                                                                                                                                                                                                 |

## Navigation

[Back to Project Homepage](project-homepage.md)
