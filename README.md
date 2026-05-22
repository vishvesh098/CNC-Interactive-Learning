# CNC Interactive Learning App

Welcome to **CNC Interactive Learning**, a professional desktop application designed to teach and practice Computer Numerical Control (CNC) programming and machining workflows. It features an interactive coordinate verification system, a custom G-Code programming environment, and visual schematic inspections.

---

## 🚀 Download & Installation Guide

Get the latest stable release of the application using our permanent, static download link:

> ### **[📥 Download Latest Windows Release (ZIP)](https://github.com/vishvesh098/CNC-Interactive-Learning/releases/latest/download/CNC-Interactive-Learning-Latest.zip)**
> *This link always redirects to the most recent release installer.*

### Step-by-Step Installation Process:
1. **Download the ZIP**: Click the download link above to download `CNC-Interactive-Learning-Latest.zip`.
2. **Extract the Archive**: Right-click the downloaded ZIP file and select **Extract All...** to extract the files to a folder of your choice (e.g., your Desktop or Downloads folder).
3. **Run the Installer**:
   - Open the extracted folder and locate the installer executable (e.g., `CNC Interactive Learning_x.x.x_x64-setup.exe`).
   - Double-click the installer to start the setup process.
4. **Follow Setup Prompts**:
   - The application installs in **Current User** mode, meaning it runs in your local user space and does not require administrator privileges.
   - Choose the installation path or leave the default path.
   - Choose whether you want to create a desktop shortcut (recommended for easy access).
   - Click **Install** to complete the setup.
5. **Launch the App**: Once installation is complete, click **Finish** and open the app from the Start Menu or your desktop shortcut.

---

## 🖥️ System Requirements & Recommendations

To ensure optimal performance and visibility of technical schematics and editor panels, please review the requirements below:

| Component | Minimum Requirement | Recommended Specification |
| :--- | :--- | :--- |
| **Operating System** | Windows 10 (64-bit) | Windows 10 or Windows 11 (64-bit) |
| **Display/Screen Size** | 1280 × 800 resolution | **18 inches (18") or larger** physical display for an optimum experience |
| **Memory (RAM)** | 4 GB | 8 GB or more |
| **Disk Space** | 200 MB free space | 500 MB free space |
| **Processor** | Intel Core i3 / AMD Ryzen 3 | Intel Core i5 / AMD Ryzen 5 or better |

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

Or explore the detailed markdown files directly in our [docs](docs/) directory:

### For Students
* [Getting Started Guide](docs/user-guide/getting-started.md) — First-time launch, login, and dashboard navigation.
* [Student Dashboard Guide](docs/user-guide/student-dashboard.md) — Finding chapters, viewing timelines, and starting exercises.
* [CNC Practice Guide](docs/user-guide/cnc-activity.md) — Detailed instruction on entering coordinates and programming G-Code.
* [Schematics Guide](docs/user-guide/schematic-activity.md) — Navigating interactive drawings and clicking hotspots.
* [Lessons Guide](docs/user-guide/lesson-activity.md) — Viewing formatted reading lessons.
* [Scientific Calculator Guide](docs/user-guide/calculator.md) — Using the integrated scientific tool.
* [Attempt History Guide](docs/user-guide/history.md) — Reviewing your past scores and code submissions.

### For Administrators
* [Admin Panel Guide](docs/user-guide/admin-guide.md) — Comprehensive guide to creating courses, importing QBanks, configuring exercises, and handling student reports.
