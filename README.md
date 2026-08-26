# 25CS044_WDFW_Even

**Web Design Fundamentals with Web (WDFW)** — Even Semester Internal Practical Exam Submissions

**Enrollment No.:** 25CS044
**Student Name:** Shubham Arunbhai Mendpara
**Subject:** WDFW (Web Design Fundamentals with Web)
**Semester:** Even

---

## About

This repository contains my internal practical exam submissions for the WDFW course, focused on identifying and fixing HTML, CSS, JavaScript, and DOM errors in a supplied buggy web application.

## Task 3: Product Order and Bill Generation Debugging

An online store's Product Order and Bill Generation webpage was supplied with 15 intentional bugs across three difficulty levels. Each bug was identified, corrected, and documented.

### Files
| File | Description |
|---|---|
| `25CS044_Shubham_Task3.html` | Corrected HTML/CSS/JavaScript file with all 15 bugs fixed |
| `25CS044_Shubham_Task3_BugReport.txt` | Bug report detailing each problem, correction, and reasoning |

### Bug Summary

| Level | Count | Marks |
|---|---|---|
| Simple | 5 | 10 |
| Medium | 5 | 15 |
| Difficult | 5 | 25 |
| **Total** | **15** | **50** |

**Simple:** CSS syntax errors (missing colon, missing `#` selector, missing padding unit), `onclick` function mismatch, DOM method casing (`getElementByID` → `getElementById`).

**Medium:** Product `id` mismatch, HTML5 `type="number"` quantity control, incorrect product price, bill output DOM target, missing field validation.

**Difficult:** Total calculation logic (`price * quantity`), full quantity validation (empty/zero/negative/invalid), `prompt()` customer-type validation, `confirm()` order flow, and complete execution-order restructuring (Read Input → Validate → Calculate → Confirm → Generate Bill).

## Notes
- Original buggy file preserved separately for reference and comparison.
- All corrections were made incrementally and can be explained individually during viva/evaluation.
