# 🛡 Test Strategy – Salesforce CRM Manual QA

## 🧭 Purpose
Define the overall strategy for testing CRM features in a simulated Salesforce sprint environment using manual QA practices.

---

## 🧪 Test Types
| Type              | Description |
|------------------|-------------|
| Functional Testing | Validate field behavior, buttons, and template actions |
| UI Testing        | Verify pop-up visibility, layout, text box behavior |
| Regression Testing | Simulate testing of repeated fields across user flows |
| Smoke Testing     | High-level test for major flows like reminders and templates |

---

## 🧰 Tools & Environment
| Item         | Description |
|--------------|-------------|
| Test Management | Excel + Markdown |
| Reference System | Trailhead |
| Bug Reporting | Markdown Bug Reports |
| Screenshots | Jira sprint + Excel test table |

---

## 🧑‍💻 Roles Simulated
| Role | Description |
|------|-------------|
| QA Tester | Authoring and executing manual tests |
| Proxy Users | Simulated actions for employee certification reminder flow |

---

## 📜 Test Data Strategy
- Static data scenarios (pre-filled picklists, template text)
- Simulated user roles (RCM, FT, PT)
- Certification expiration dates (7–180 days range)

---

## 🟩 Entry Criteria
- Sprint task is defined
- Testable scenario documented
- Assumptions clarified via Trailhead

## 🟥 Exit Criteria
- All defined test cases executed
- High priority bugs resolved
- Test report documented in GitHub repo
