# Monitor Permit Status

**Location:** Project Homepage > Permit Monitoring > Monitor Permit Status

---

## Functional Description

The Monitor Permit Status feature allows an authorized user to check the status of chainsaw registration records. The system displays whether a permit record is active or expired based on the stored permit information and expiry date. This feature helps users monitor permit validity and identify records that may need renewal or review.

---

## Use Case Scenario

| Field          | Description                                                                                                                                                                                                                                                                                        |
| -------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Use Case ID    | UC-STAT-01                                                                                                                                                                                                                                                                                         |
| Use Case Name  | Monitor Permit Status                                                                                                                                                                                                                                                                              |
| Actor          | Authorized User                                                                                                                                                                                                                                                                                    |
| Precondition   | The user is logged in and chainsaw records are available in the system.                                                                                                                                                                                                                            |
| Trigger        | The user opens the dashboard, reports page, or chainsaw records page.                                                                                                                                                                                                                              |
| Main Flow      | 1. The user opens a page that displays permit records or status information. <br> 2. The system retrieves the saved chainsaw registration records. <br> 3. The system displays the permit status, such as active or expired. <br> 4. The user reviews the records that need monitoring or renewal. |
| Alternate Flow | If no records are available, the system displays zero records or an empty list.                                                                                                                                                                                                                    |
| Postcondition  | The user can identify the current status of chainsaw permit records.                                                                                                                                                                                                                               |

