# CNC Interactive Learning — Documentation

Welcome to the official user documentation for **CNC Interactive Learning**, a desktop application for teaching CNC machining concepts through interactive exercises.

---

## Table of Contents

| Section | Description |
|---|---|
| [Getting Started](user-guide/getting-started.md) | Launching the app, the Login screen, and role selection |
| [Student Dashboard](user-guide/student-dashboard.md) | Course overview, chapter timeline, and starting activities |
| [Text-Based Lesson Activity](user-guide/lesson-activity.md) | Reading rich educational content and recording offline progress |
| [CNC Practice Activity](user-guide/cnc-activity.md) | 2-phase exercise: coordinate input + G-Code programming |
| [Schematic Exploration](user-guide/schematic-activity.md) | Interactive diagram exploration with annotated hotspots |
| [Scientific Calculator](user-guide/calculator.md) | Built-in calculator with trig, memory, and history |
| [Reporting Questions](user-guide/reporting.md) | Flag issues with questions and content |
| [Attempt History](user-guide/history.md) | Reviewing past submissions and scores |
| [Admin Guide](user-guide/admin-guide.md) | Managing QBank, activities, schematics, courses, and reports |

---

## Quick Reference

### For Students

```
Launch App → Select "Student Access" → Dashboard → Pick a Chapter → Start Activity
```

1. **Text Lessons** — Read instructor-provided material with formatted text and embedded images.
2. **CNC Activities** — Enter X/Z coordinates, then write the G-Code program.
3. **Schematic Activities** — Click every hotspot on the diagram to complete the activity.
4. **Calculator** — Use the built-in scientific calculator for quick computations.
5. **Reporting** — Flag issues with questions or content for admin review.
6. **History** — Review your past attempts and scores from the sidebar.

### For Administrators

```
Launch App → Select "Admin Access" → Choose a tab from the left sidebar
```

| Tab | What You Can Do |
|---|---|
| **Course Structure** | Create courses, add chapters, link activities |
| **QBank Manager** | Import questions from JSON, flag/unflag, reset |
| **Test Generator** | Create Finite/Infinite CNC practice activities |
| **Asset Pool** | Upload schematic images & hotspots, and write Text-Based Lessons |
| **Reports** | Review and resolve flagged question reports |

---

## Key Concepts

| Term | Meaning |
|---|---|
| **Activity** | A single learning exercise (CNC, Schematic, or Text Lesson) |
| **Text Lesson** | Rich text content created using the integrated editor |
| **Chapter** | A group of related activities in a course |
| **Course** | The full learning programme, made up of chapters |
| **Finite Activity** | Fixed question pool — all questions must be completed |
| **Infinite Activity** | Random question pool — complete when score ≥ 60% |
| **Hotspot** | An interactive point on a schematic diagram |
| **QCode** | Unique identifier for a question in the QBank |
| **BankExport** | The JSON file format used to import questions into the QBank |
| **Unit Test** | A summative assessment at the end of a chapter or course |
| **Report** | A student-submitted issue flag for admin review |
| **Integrity Status** | Score verification status: verified, invalid, unsigned, or pending |
| **Unit Test** | A summative assessment at the end of a chapter or course |
| **Report** | A student-submitted issue flag for admin review |
| **Integrity Status** | Score verification status: verified, invalid, unsigned, or pending |

---

## Screenshots Overview

| Screen | File |
|---|---|
| Login | `user-guide/assets/01-login.png` |
| Admin – Course Structure | `user-guide/assets/06-admin-course-structure.png` |
| Admin – QBank | `user-guide/assets/03-admin-qbank.png` |
| Admin – Test Generator | `user-guide/assets/04-admin-tests.png` |
| Admin – Asset Pool | `user-guide/assets/05-admin-schematics.png` |
| Admin – Reports | `user-guide/assets/07-admin-reports.png` |
| Student Dashboard | `user-guide/assets/08-student-dashboard.png` |
| Chapter Selected | `user-guide/assets/09-student-chapter.png` |
| CNC Activity (Phase 1) | `user-guide/assets/10-cnc-activity.png` |
| G-Code Editor (Phase 2) | `user-guide/assets/11-gcode-editor.png` |
| History List | `user-guide/assets/14-history-list.png` |
| History Detail | `user-guide/assets/15-history-detail.png` |
