# Gmail Compose - Manual Test Cases

Manual test cases for the **Gmail Compose** feature, written as part of the Incubyte QA assessment.

The primary scenario covered is sending an email with subject **"Incubyte"** and body **"QA test for Incubyte"**, along with related positive and negative cases.

---

## Contents

| File | Description |
|---|---|
| `test-cases.xlsx` → sheet `Traditional` | Traditional-style test cases |
| `test-cases.xlsx` → sheet `BDD` | BDD-style (Given / When / Then) test cases |
| `README.md` | This file |

---

## Coverage

- 20 traditional + 20 BDD test cases (mirrored for traceability)
- Positive and negative scenarios
- Areas: Compose window, To/CC/BCC fields, Subject, Body, Send, Attachments, Drafts, offline behavior

---

## Test Environment

- **Application:** Gmail web (https://mail.google.com)
- **Browser:** Chrome (latest)
- **Execution:** Manual

---

## How to Use

1. Open `test-cases.xlsx`.
2. Pick a test case and set up the preconditions.
3. Execute the steps with the given test data.
4. Compare actual vs. expected result and mark **Pass / Fail**.
