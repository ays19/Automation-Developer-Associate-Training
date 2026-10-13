# 🤖 UiPath Automation Developer Associate — Training & Portfolio

[![UiPath](https://img.shields.io/badge/UiPath-Studio%202026-FA4616?style=for-the-badge&logo=uipath&logoColor=white)](https://www.uipath.com/)
[![Framework](https://img.shields.io/badge/Platform-Windows%20.NET-0078D6?style=for-the-badge&logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/)
[![Language](https://img.shields.io/badge/Language-Visual%20Basic-2B579A?style=for-the-badge&logo=visualstudio&logoColor=white)](https://learn.microsoft.com/en-us/dotnet/visual-basic/)
[![License](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)](https://github.com/ays19/Automation-Developer-Associate-Training)

> A production-grade, structured curriculum and project repository aligning with the **UiPath Certified Professional Automation Developer Associate** track. This portfolio showcases hands-on automations ranging from foundational RPA concepts to modern UI Automation, high-performance Excel/DataTable workflows, collection structures, regular expressions, and event-driven exception handling.

---

## 🎯 Executive Summary for Recruiters & Hiring Managers

This repository serves as a verifiable demonstration of end-to-end Robotic Process Automation (RPA) engineering skills built using **UiPath Studio (Modern Experience)**. Key competencies demonstrated across these 40+ workflow implementations include:

- **Enterprise Flow Control & Modularity:** Clean separation of concerns with sub-workflows, standardized argument directionality (`in_`, `out_`, `io_`), and global constants/variables.
- **Modern UI Automation & Reliability:** Leveraging Unified Targeting, Object Repository, Multi-anchor selectors, Fuzzy/Strict Selectors, Computer Vision fallbacks, and runtime UI state verification (`Check Application State`, `Verify Execution`).
- **Data Engineering & Business Logic:** Regular Expression parsing, string transformations, advanced collections (`List(Of T)`, `Dictionary(Of TKey, TValue)`), and multi-criteria sorting/filtering.
- **Excel & DataTable Automation:** Enterprise workbook processing, batch record consolidation, automated web table scraping via Table Extraction, and high-volume data transformation without requiring local Excel installation.
- **Resilience & Asynchronous Patterns:** Event-driven architecture using `Pick` / `Pick Branch`, parallel task execution (`Parallel`), and defensive exception management (`Managing Difficult Situations`).

---

## 🗂️ Curriculum & Project Architecture

The projects are organized into two primary progressive tiers:

```
Process/
├── Automation Explorer/                        # Tier 1: Foundations, Workflows & Data
│   ├── Arguments/                              # Modularity and argument passing
│   ├── ArrayPractice/ & Arrays/                # Sequential collections & indexing
│   ├── build and run UI automation project/    # End-to-end basic UI bot
│   ├── Excel Activities practice/              # Modern Excel operations
│   ├── Excel Data Consolidation 1 & 2/         # Multi-source ledger consolidation
│   ├── Excel Report Consolidation/             # Cross-store daily reports compiler
│   ├── ForEachLoop/ & forEachandIfPractice/    # Iterative processing & branching
│   ├── Identify UI element/ & Challenge/       # Deep selector inspection & anchoring
│   ├── Input methods and activities/           # Hardware Events, Chromium API, Simulate
│   ├── Invoke Workflow Practice/               # Parametric sub-routine invocations
│   ├── Leap Year using if/                     # Flowchart vs. Sequence branching
│   ├── Managing Variables/ & Variable/         # Variable scopes and data types
│   ├── Output Activities and Method/           # Screen scraping, Get Text, OCR
│   ├── StudioInterface/ & UiPath first Run/    # Studio lifecycle & environment setup
│   ├── SwitchAndForEach/ & Practice/           # Pattern switching & invoice dispatch
│   ├── Use excel Extraction/                   # Modern Excel design & range extraction
│   ├── Using App_web recorder/                 # Modern Recorder actions & validation
│   ├── UsingGlobalConstantsAndVariables/       # Global session-level context
│   ├── UsingTableExtractionPractice/           # Automated web table & pagination extraction
│   ├── WhileAndIfPractice/                     # Iterative logic with break conditions
│   ├── Workbook_and_Datatable_Practice/        # Headless DataTable manipulation
│   └── Workbook_Datatable_Automation/          # HR report reconciliation workflow
│
└── Automation Developer Associate Training/    # Tier 2: Associate Certification Track
    ├── Check Application State/               # Modern conditional UI wait & branching
    ├── extract email address with RegEx/       # Pattern parsing from unformatted text
    ├── ForEachUIElements/                      # Modern dynamic UI collections iteration
    ├── Managing Difficult Situations_Project/  # Exception strategies & UI fault recovery
    ├── Phase one_Supplier Claims Processing/   # Enterprise supplier claims & testing flow
    ├── Phase three - Supplier claims processing/ # Post-healing agent claims processing
    ├── Phase 5 - Supplier claims processing/    # Phase 5 ScreenPlay claims automation
    ├── PickAndPickBranch/                      # Non-deterministic event-driven monitoring
    ├── Regex Addresses Demo/                   # Multi-line street & address extraction
    ├── String Bookstore Demo/                  # String methods (Split, Substring, Replace)
    ├── StringActivities/ & Practice/           # Enterprise string cleansing & text pipelines
    ├── Task2/                                  # Capstone: Multi-screen end-to-end workflow
    ├── Types of Selector/                      # Strict, Fuzzy, Image, Anchor descriptors
    ├── using dictionaries and integers/        # Key-Value hashing & numerical counters
    ├── using listsPractice/ & Work with Lists/ # Generic lists, sorting algorithms
    ├── UsingParralalActivity/                  # Concurrency & asynchronous evaluation
    ├── Verify execution feature/               # Visual feedback & verification assertions
    ├── Work with List and Dictionaries/        # Complex data structures & lookups
    └── Working with dictionaries/              # Dynamic key assignment & iteration
```

---

## 📚 Detailed Project Catalog

### Tier 1: Automation Explorer (Foundational & Intermediate)

| Module / Practice | Path | Core Concepts & Activities |
| :--- | :--- | :--- |
| **Studio & Variables** | `Automation Explorer/UiPath first Run` <br> `Automation Explorer/StudioInterface` <br> `Automation Explorer/Managing Variables` | Variable types (`Int32`, `String`, `Boolean`), variable scopes, execution tracing, studio panels. |
| **Workflow Modularity** | `Automation Explorer/Arguments` <br> `Automation Explorer/Invoke Workflow Practice` <br> `Automation Explorer/UsingGlobalConstantsAndVariables` | `in_`, `out_`, `io_` parameters, workflow reusability, global constants, passing parameters across nested workflows. |
| **Control Flow & Decision** | `Automation Explorer/WhileAndIfPractice` <br> `Automation Explorer/SwitchAndForEach` <br> `Automation Explorer/Leap Year using if` | `If / Else`, `Flowchart`, `Switch` on string company codes, conditional branching, and `While` loop bounds. |
| **Data Collections** | `Automation Explorer/Arrays` <br> `Automation Explorer/ArrayPractice` <br> `Automation Explorer/ForEachLoop` | Array indexing, element iteration with `For Each`, in-memory string search, and text file output. |
| **Excel & Report Consolidation**| `Automation Explorer/Excel Data Consolidation 1 & 2` <br> `Automation Explorer/Excel Report Consolidation` | Modern `Use Excel File`, `For Each Excel Row`, aggregating multiple daily store spreadsheets into unified reports. |
| **DataTables & Web Scraping** | `Automation Explorer/UsingTableExtractionPractice` <br> `Automation Explorer/Workbook_Datatable_Automation` <br> `Automation Explorer/Workbook_and_Datatable_Practice` | `Table Extraction`, multi-page pagination, headless workbook operations (`Read Range`, `Build Data Table`, `Filter Data Table`, `Write Range`). |
| **UI Automation & Recorders** | `Automation Explorer/Using App_web recorder` <br> `Automation Explorer/Identify UI element Challenge` <br> `Automation Explorer/Input methods and activities` | Modern recorder, input methods (`Chromium API`, `Simulate`, `Hardware Events`), strict selectors, visual anchors. |

---

### Tier 2: Developer Associate (Advanced & Certification Ready)

| Module / Practice | Path | Core Concepts & Activities |
| :--- | :--- | :--- |
| **Regular Expressions (RegEx)** | `Automation Developer Associate Training/extract email address with RegEx Practice` <br> `Automation Developer Associate Training/Regex Addresses Demo` | RegEx Builder, pattern matching (`\b[A-Za-z0-9._%+-]+@[A-Za-z0-9.-]+\.[A-Z|a-z]{2,}\b`), group captures. |
| **String Manipulation** | `Automation Developer Associate Training/StringActivities` <br> `Automation Developer Associate Training/StringActivitiesPractice` <br> `Automation Developer Associate Training/String Bookstore Demo` | `.Split()`, `.Substring()`, `.IndexOf()`, `.Trim()`, `.Replace()`, formatting multiline raw text into structured schemas. |
| **Collections & Dictionaries** | `Automation Developer Associate Training/Work with Lists` <br> `Automation Developer Associate Training/using listsPractice` <br> `Automation Developer Associate Training/Working with dictionaries` <br> `Automation Developer Associate Training/Work with List and Dictionaries` | `System.Collections.Generic.List(Of T)`, `Dictionary(Of TKey, TValue)`, custom list sorting (`List.Sort()`), iterating key-value pairs. |
| **Modern Selectors & UI Iteration** | `Automation Developer Associate Training/Types of Selector` <br> `Automation Developer Associate Training/ForEachUIElements` <br> `Automation Developer Associate Training/Check Application State` | Unified Targeting (Fuzzy, Strict, Image, Computer Vision), looping across dynamic UI grids with `For Each UI Element`. |
| **Verification & Assertions** | `Automation Developer Associate Training/Verify execution feature` | Modern verification checks, confirming field changes and UI transitions prior to advancing workflows. |
| **Event-Driven & Concurrency** | `Automation Developer Associate Training/PickAndPickBranch` <br> `Automation Developer Associate Training/UsingParralalActivity` | Asynchronous branches with `Pick` and `PickBranch` for non-deterministic dialogs; parallel concurrent executions. |
| **Fault Handling & Recovery** | `Automation Developer Associate Training/Managing Difficult Situations_Project` | Graceful UI recovery, Find Children, Visual Tree navigation, unexpected pop-up handling. |
| **Enterprise Use Case & Testing** | `Automation Developer Associate Training/Phase one_Supplier Claims Processing` <br> `Automation Developer Associate Training/Phase three - Supplier claims processing` <br> `Automation Developer Associate Training/Phase 5 - Supplier claims processing` | End-to-end supplier claims automation across phases (Phase 1, Phase 3 PHA, Phase 5 ScreenPlay), Mail & Excel automation, Testing framework. |
| **Capstone Automation** | `Automation Developer Associate Training/Task2` | Multi-screen end-to-end automation with input validation, transaction processing, and audit outputs. |

---

## 🛠️ Technology Stack & Standards

- **RPA Platform:** UiPath Studio 2026 (Enterprise / Community Edition)
- **Target Framework:** `.NET 8` / `Windows`
- **Expression Language:** Visual Basic for Applications / .NET (`VB.NET`)
- **Key Package Dependencies:**
  - `UiPath.System.Activities` (v26.2+)
  - `UiPath.UIAutomation.Activities` (v26.10+)
  - `UiPath.Excel.Activities`
  - `UiPath.Mail.Activities`
  - `UiPath.Testing.Activities`
- **Architecture Guidelines Applied:**
  - **Naming Conventions:** Descriptive activity labels; PascalCase variables; direction-prefixed arguments (`in_ConfigFile`, `out_TransactionID`).
  - **Modern UI Design:** Universal targeting enabled with automatic selector fallbacks.
  - **Clean Version Control:** Tailored `.gitignore` suppressing studio-generated runtime metadata (`.local/`, `.tmh/`, `.screenshots/`, `.storage/`).

---

## 🚀 How to Open and Run These Projects

### Prerequisites
1. Install [UiPath Studio](https://www.uipath.com/product/studio) (v2024+ or v2026 recommended).
2. Ensure desktop browser extensions (Chrome, Edge) are installed and enabled via UiPath Studio -> **Tools** -> **UiPath Extensions**.

### Opening Any Project
1. Clone this repository:
   ```bash
   git clone https://github.com/ays19/Automation-Developer-Associate-Training.git
   ```
2. Open **UiPath Studio**.
3. Click **Open Project** and navigate to any subfolder under `Process/` containing a `project.json` file (e.g., `Process/Automation Developer Associate Training/Task2/project.json`).
4. Studio will automatically restore required NuGet packages listed in `project.json`.
5. Press <kbd>F5</kbd> or click **Run File** to execute `Main.xaml`.

---

## 👤 Author & Contact

**Ahsan Yasir Sharar**
- **GitHub:** [@ays19](https://github.com/ays19)
- **Portfolio Repository:** [Automation-Developer-Associate-Training](https://github.com/ays19/Automation-Developer-Associate-Training)

*Contributions, feedback, and recruiter inquiries are always welcome!*