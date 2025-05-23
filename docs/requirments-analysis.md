# 📋 Requirements Analysis – Salesforce CRM QA Project

## 🔍 Objective
Analyze testable requirements from sprint tickets and available documentation to define valid test conditions and expected results.

## 🧾 Requirement Sources
- Simulated Jira sprint tasks
- Excel test case scenarios
- Salesforce Trailhead modules
- Functional descriptions from screenshots

---

## 🧩 Functional Requirements Extracted

### ✅ CRM-2437: Recruitment Strategy Template
- User must be able to select and insert a predefined template into a notes field
- Pop-up modal should appear
- Data should populate without overwriting existing text

### ✅ Certification Reminders
- Employees should be notified between 7–180 days before cert expiration
- Proxy functionality must simulate reminders correctly
- Notifications appear in Workday (simulated)

> 📸 Screenshot: `Certification_Reminders_TestCases.jpeg`

---

## 🔄 Non-Functional Requirements (Simulated)
- Responsiveness of pop-ups
- Proper user role simulation (RCM user, FT, PT, Proxy)
- No crashing or data loss during insertion or navigation

---

## 🔎 Traceability Matrix (Optional for GitHub Portfolio)
- Could be added to map test cases to requirements
