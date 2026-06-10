# View Record Details

**Location:** Project Homepage > Chainsaw Records Management > View Record Details

---

## Functional Description

The View Record Details feature allows an authorized user to open and review the complete information of a selected chainsaw registration record. This includes owner details, chainsaw information, registration details, permit dates, status, and uploaded images. This feature helps users verify stored information without editing the record.

---

## Use Case Scenario

| Field          | Description                                                                                                                                                                                                                                                                                      |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Use Case ID    | UC-REC-03                                                                                                                                                                                                                                                                                        |
| Use Case Name  | View Record Details                                                                                                                                                                                                                                                                              |
| Actor          | Authorized User                                                                                                                                                                                                                                                                                  |
| Precondition   | The user is logged in and at least one chainsaw record exists in the system.                                                                                                                                                                                                                     |
| Trigger        | The user clicks the view/details action for a selected record.                                                                                                                                                                                                                                   |
| Main Flow      | 1. The user opens the Chainsaw Records page. <br> 2. The user selects a record and clicks the view/details action. <br> 3. The system retrieves the complete information of the selected record. <br> 4. The system displays the record details, including related uploaded images if available. |
| Alternate Flow | If the record details cannot be loaded, the system displays an error message.                                                                                                                                                                                                                    |
| Postcondition  | The user can review the complete information of the selected chainsaw record.                                                                                                                                                                                                                    |

