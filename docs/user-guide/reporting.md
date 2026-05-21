# Reporting Questions

The reporting system allows students to flag issues with questions, activities, or content. Reports are reviewed by administrators who can resolve, fix, or reject them.

---

## When to Report a Question

Submit a report if you encounter:

- **Incorrect answer** — The expected coordinates or G-Code appear wrong
- **Unclear question** — The instructions or diagram are confusing
- **Missing information** — Required data is absent from the question
- **Technical issue** — The SVG diagram, G-Code editor, or other component is not working correctly
- **Typographical error** — Spelling mistakes or formatting issues

---

## How to Submit a Report

### From Within an Activity

1. Open the **Side Panel** by clicking the sidebar tab
2. Select the **Report** tab (flag icon)
3. Fill out the report form:

| Field | Description | Required |
|---|---|---|
| **Report Type** | Category of the issue (bug, incorrect answer, unclear, etc.) | Yes |
| **Point ID** | The specific point/coordinate affected (for CNC activities) | Optional |
| **Description** | Detailed explanation of the issue | Yes |

4. Click **Submit Report**
5. A confirmation message appears when the report is successfully submitted

### Report Types

| Type | When to Use |
|---|---|
| **Bug** | Technical malfunction (editor not working, diagram not loading) |
| **Incorrect Answer** | The expected solution appears wrong |
| **Unclear Question** | Instructions or diagram are confusing |
| **Missing Information** | Required data is absent |
| **Typographical Error** | Spelling or formatting mistakes |
| **Other** | Any issue not covered above |

---

## Report Status

After submission, your report goes through a review process:

| Status | Meaning |
|---|---|
| **Pending** | Report submitted, awaiting admin review |
| **Reviewed** | Admin has read the report and is investigating |
| **Fixed** | The issue has been resolved by the admin |
| **Rejected** | The report was reviewed and no issue was found |

---

## What Happens After You Report

1. The report is stored in the system with a unique ID
2. Administrators see pending reports in the **Reports** tab of the Admin Dashboard
3. An admin reviews the report, investigates the question, and takes action:
   - **Fix** — Corrects the question in the QBank
   - **Reject** — Marks the report as not a valid issue (with an optional resolution note)
4. The report status updates accordingly

---

## Tips for Effective Reports

- **Be specific** — Describe exactly what you expected vs. what you observed
- **Include the QCode** — If visible, note the question code for faster identification
- **Specify the point** — For coordinate issues, mention which point (e.g., "Point B") is affected
- **Describe the context** — Note what phase (Coordinates or G-Code) the issue occurred in

---

## Admin Side

Administrators review and resolve reports through the **Reports** tab in the Admin Dashboard. See the [Admin Guide](admin-guide.md) for details on managing reports.

---

[Back to Student Dashboard](student-dashboard.md) | [CNC Practice Activity](cnc-activity.md)
