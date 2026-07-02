# Lab 04 – User Stories and Acceptance Criteria

## User Story Format

As a **[user role]**, I want to **[goal/action]**, so that **[benefit/value]**.

---

## User Stories

| Story ID | Role | User Story | Related Requirement | Priority | Acceptance Criteria | Demo Evidence |
| --- | --- | --- | --- | --- | --- | --- |
| **US-01** | Student | As a student, I want to sign in using my RSU email so that only verified students can access the marketplace. | FR-01 | Must | Given I have a valid RSU email, when I register and log in, then I can access the marketplace. | Login/Register demo |
| **US-02** | Student | As a student, I want to post a resource, equipment, or student service so that other students can find and use it. | FR-02 | Must | Given I complete the listing form and submit it, then the listing appears in the marketplace. | Create listing demo |
| **US-03** | Student | As a student, I want to search and filter listings so that I can quickly find the resources or services I need. | FR-03 | Must | Given listings exist, when I search or filter by category or keyword, then matching results are displayed. | Search/filter demo |
| **US-04** | Student | As a student, I want to view detailed information about a resource or service before contacting the owner. | FR-04 | Should | Given I select a listing, when I open it, then I can view all relevant details. | Listing details demo |
| **US-05** | Student | As a student, I want to contact the owner of a resource or service so that I can arrange borrowing, requesting, or receiving help. | FR-05 | Must | Given I open a listing, when I send a request or message, then the owner receives it. | Contact/request demo |
| **US-06** | Student | As a student, I want to edit or remove my own listings so that my information stays accurate and up to date. | FR-06 | Could | Given I own a listing, when I edit or delete it, then the changes are saved. | Edit/Delete listing demo |

---

## Acceptance Criteria Checklist

A good acceptance criterion should be:

- Testable
- Observable in the final prototype
- Connected to a requirement
- Connected to user evidence
- Not too vague

---

## Rejected / Future User Stories

| Story ID | Reason for Postponing | Future Condition |
| --- | --- | --- |
| **FUS-01** | Full private real-time messaging is more complex than the current MVP scope. | Add after the core marketplace workflow is validated. |
| **FUS-02** | Online payment or service booking requires additional security and transaction management. | Add when the platform is expanded beyond the prototype stage. |
| **FUS-03** | Ratings and reviews are useful but not essential for demonstrating the first MVP. | Add after students actively use the platform. |
