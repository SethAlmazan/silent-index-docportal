# Attach and View Permit Images

**Location:** Project Homepage > Chainsaw Registration > Attach and View Permit Images

---

## Functional Description

The Attach and View Permit Images feature allows an authorized user to upload and view supporting images related to a chainsaw registration record. These images may include proof of ownership and inspection images. This feature helps provide visual documentation for each registered chainsaw record.

---

## Use Case Scenario

| Field          | Description                                                                                                                                                                                                                                                       |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Use Case ID    | UC-IMG-01                                                                                                                                                                                                                                                         |
| Use Case Name  | Attach and View Permit Images                                                                                                                                                                                                                                     |
| Actor          | Authorized User                                                                                                                                                                                                                                                   |
| Precondition   | The user is logged in and is creating or viewing a chainsaw registration record.                                                                                                                                                                                  |
| Trigger        | The user uploads images during registration or opens a record with uploaded images.                                                                                                                                                                               |
| Main Flow      | 1. The user opens the chainsaw registration form or record details. <br> 2. The user selects image files to upload as supporting documents. <br> 3. The system stores the uploaded images. <br> 4. The system displays the uploaded images in the related record. |
| Alternate Flow | If the image upload fails or the file is invalid, the system displays an error message and does not attach the image.                                                                                                                                             |
| Postcondition  | The selected permit or inspection images are attached to the chainsaw record and can be viewed by the user.                                                                                                                                                       |

