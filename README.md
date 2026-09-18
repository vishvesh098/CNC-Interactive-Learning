# CNC Interactive Learning App

Welcome to **CNC Interactive Learning**, a professional desktop application designed to teach and practice Computer Numerical Control (CNC) programming and machining workflows. It features an interactive coordinate verification system, a custom G-Code programming environment, and visual schematic inspections.

---

## 🚀 Download & Installation Guide

CNC Interactive Learning is distributed exclusively through the **Microsoft Store**, which handles the download, installation, and all future updates for you.

> ### **[🛍️ Get CNC Interactive Learning from the Microsoft Store](https://apps.microsoft.com/detail/9NKCJFQ0XQ60)**
> *Installs and updates are managed by the Microsoft Store.*

### Step-by-Step Installation Process:
1. **Open the Store page**: Use the link above, or open the Microsoft Store app on Windows and search for "CNC Interactive Learning".
2. **Click Get**: Press the **Get** button on the Store page. The Store may ask you to sign in with your Microsoft account first.
3. **Wait for the install**: The Store downloads and installs the application automatically — there are no setup prompts, installation paths, or shortcut options to choose.
4. **Launch the App**: Once installation finishes, open **CNC Interactive Learning** from the Start menu. Pin it to Start or the taskbar for quick access.

> [!TIP]
> **No Administrator Rights Needed**: Store apps install into a Windows-managed location for your user account, so no elevation prompt appears and nothing is added to Program Files.

### Keeping the App Updated:
- Updates are delivered automatically through the **Microsoft Store** and apply the next time the app restarts.
- To check for updates manually: open the **Microsoft Store** → **Library** → **Get updates**.
- The app also prompts you when a newer version is available, and choosing to update opens the Store's own update flow.

---

## 🖥️ System Requirements & Recommendations

To ensure optimal performance and visibility of technical schematics and editor panels, please review the requirements below:

| Component | Minimum Requirement | Recommended Specification |
| :--- | :--- | :--- |
| **Operating System** | Windows 10 version 17763.0 (1809) or higher, 64-bit | Windows 10 or Windows 11, 64-bit |
| **Processor** | 1 GHz or faster Dual-Core | 2 GHz or faster Quad-Core |
| **Memory (RAM)** | 4 GB | 8 GB or more |
| **Keyboard** | Integrated Keyboard | — |
| **Mouse** | Integrated Mouse | — |
| **Display/Screen Size** | 1280 × 800 resolution | **18 inches (18") or larger** physical display for an optimum experience |
| **Disk Space** | 200 MB free space | 500 MB free space |

> [!NOTE]
> **Microsoft Store Required**: The application is installed through the Microsoft Store, so the Store app must be available on your PC. Windows editions that omit it (such as Windows Server or LTSC images without the Store) cannot install the app.

> [!TIP]
> **Screen Size Recommendation**: The application runs in full-screen mode and renders detailed technical drawings alongside coordinates and G-Code input side-by-side. A screen size of **18 inches or larger** is highly recommended to comfortably view all elements without visual crowding.

---

## 🧠 State-of-the-Art (SOTA) Practice System

Unlike traditional CNC teaching methodologies, this application utilizes a complete, automated **Infinite Practice System** to generate virtually unlimited unique CNC problems:

* **Algorithmic Generated Questions**: Automatically creates technical drawings (with proper dimensions), coordinates, and corresponding G-Code using a custom-built Python system.
* **No Repetition / No Copying**: Each student gets a unique problem, eliminating answer copying and encouraging actual geometry comprehension.
* **Instant, Detailed Feedback**: Evaluates student inputs (both coordinate matrices and G-code execution paths) in real time and highlights mistakes immediately.
* **Industry-Aligned Workflow**: Guides students step-by-step through the standard engineering funnel: **Coordinates & Dimension Verification** $\rightarrow$ **G-Code Programming** $\rightarrow$ **Simulation/Machining**.
* **Progress Tracking & Difficulty Control**: Keeps records of student attempts locally and scales difficulty based on student advancement.

### 🎯 Key Limitations Addressed

The application is designed specifically to solve shortcomings in current CNC training methods:

* **Over-reliance on pen-and-paper practice**: Pen-and-paper drafting is fundamentally misaligned with real CNC programming workflows and modern industry practices.
* **Limited practice opportunities**: Exercises are typically restricted to only 1–2 static textbook problems per chapter or topic due to manual grading constraints.
* **Rote learning and answer copying**: Static questions encourage students to memorize code sequences or copy coordinates without understanding.
* **Delayed and non-specific feedback**: Instructors face bottlenecks grading papers, leading to delayed feedback that halts the student's learning cycle.

> [!NOTE]
> **A First-of-its-Kind Implementation in ITI Training**  
> This approach represents a first-of-its-kind implementation in the ITI training context and reflects a state-of-the-art (SOTA) methodology, combining algorithmic content generation with integrated CNC learning and evaluation. To the best of our knowledge, such a system is not currently in use in ITIs or similar training institutes.

---

## 🌟 Core Features

- **Double-Phase CNC Workflow**: Real-world CNC programming workflow. Verify X/Z coordinate points in Phase 1 before moving to G-Code writing in Phase 2.
- **Advanced G-Code Editor**: Native line numbers, automated uppercase formatting, syntax highlighting (Pink for codes, Teal for coordinates), and scroll line-snapping to prevent text clipping.
- **Interactive Technical Schematics**: Explore engineering drawings by locating and clicking highlighted hotspots to learn component functions.
- **Rich Text-Based Lessons**: Instructor-authored rich text guides with embedded images, lists, and reference tables.
- **Local Progress & Attempts History**: Work results and quiz history are saved locally on your device and are fully reviewable via the history log.
- **Admin Dashboard**: Manage QBank imports, generate tests, upload schematics, structure courses, and view flagged question reports.

---

## 📚 Application Documentation

Explore the comprehensive online user guide and administration documentation:

> ### **[🌐 Open Live Interactive Documentation](https://vishvesh098.github.io/CNC-Interactive-Learning/)**
> *Includes step-by-step guides for students and administrators, system requirements, and installation instructions.*

Or read the same content as markdown in the [obsidian-vault/User_Manual](obsidian-vault/User_Manual/) directory:

* [Getting Started](obsidian-vault/User_Manual/Getting_Started.md) — Store installation, first launch, login, and system requirements.
* [Student Dashboard](obsidian-vault/User_Manual/Student_Dashboard.md) — Courses, chapters, activities, lessons, and attempt history.
* [CNC Practice](obsidian-vault/User_Manual/CNC_Practice.md) — Coordinate verification, G-Code programming, schematics, calculators, and reporting.
* [Admin Console](obsidian-vault/User_Manual/Admin_Console.md) — Courses, QBank management, test generation, asset pool, and reports.
* [Reference](obsidian-vault/User_Manual/Reference.md) — Glossary, style guide, data storage & privacy, and troubleshooting.
