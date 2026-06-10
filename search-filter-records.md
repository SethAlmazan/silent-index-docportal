# Search and Filter Records

**Location:** Project Homepage > Chainsaw Records Management > Search and Filter Records

---

## Functional Description

The Search and Filter Records feature allows an authorized user to quickly find specific chainsaw registration records from the records list. The user can search records using available information such as owner name, municipality, barangay, chainsaw brand, serial number, or permit status. This feature helps users locate records faster without manually checking the entire list.

---

## Use Case Scenario

| Field          | Description                                                                                                                                                                                                                                  |
| -------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Use Case ID    | UC-REC-02                                                                                                                                                                                                                                    |
| Use Case Name  | Search and Filter Records                                                                                                                                                                                                                    |
| Actor          | Authorized User                                                                                                                                                                                                                              |
| Precondition   | The user is logged in and chainsaw records are available in the system.                                                                                                                                                                      |
| Trigger        | The user enters a keyword or selects a filter option in the Chainsaw Records page.                                                                                                                                                           |
| Main Flow      | 1. The user opens the Chainsaw Records page. <br> 2. The user enters a search keyword or selects a filter. <br> 3. The system checks the records that match the search or filter criteria. <br> 4. The system displays the matching records. |
| Alternate Flow | If no records match the search or filter criteria, the system displays an empty result or no matching records.                                                                                                                               |
| Postcondition  | The user sees the filtered or searched list of chainsaw records.                                                                                                                                                                             |

