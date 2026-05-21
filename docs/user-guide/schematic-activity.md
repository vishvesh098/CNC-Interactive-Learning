# Schematic Exploration Activity

A **Schematic Exploration Activity** presents a technical diagram (e.g. a machine component, assembly, or process flow) with interactive hotspots. Your goal is to click on every hotspot and read the information about each part.

---

## The 3-Panel Layout

The schematic activity screen is divided into three areas:

```
┌─────────────────────────────────┬──────────────────┐
│                                 │                  │
│      SVG Schematic Viewer       │   Side Panel     │
│         (Main Diagram)          │   (Info HUD)     │
│                                 │                  │
├─────────────────────────────────┴──────────────────┤
│              Hotspot Grid (Bottom Rail)             │
└─────────────────────────────────────────────────────┘
```

### 1. SVG Schematic Viewer (Main Diagram)

The large central panel displays the technical diagram. Coloured circular markers — **hotspots** — are overlaid on key parts of the image.

- Each hotspot has a unique colour based on its index in the activity.
- Hovering over a hotspot highlights it with a glow effect.
- **Click a hotspot** to select it and reveal its details in the Side Panel.
- **Pan and Zoom:** You can pan the diagram by clicking and dragging, and zoom using the mouse scroll wheel or pinch gesture. This allows you to examine details of large schematics.

### Keyboard Navigation

| Key | Action |
|---|---|
| **Tab** | Move between hotspot markers |
| **Enter / Space** | Select the focused hotspot |
| **Arrow Keys** | Navigate the hotspot grid in the bottom panel |
| **Escape** | Deselect the current hotspot |
- **Pan and Zoom:** You can pan the diagram by clicking and dragging, and zoom using the mouse scroll wheel or pinch gesture. This allows you to examine details of large schematics.

### Keyboard Navigation

| Key | Action |
|---|---|
| **Tab** | Move between hotspot markers |
| **Enter / Space** | Select the focused hotspot |
| **Arrow Keys** | Navigate the hotspot grid in the bottom panel |
| **Escape** | Deselect the current hotspot |

### 2. Side Panel (Info HUD)

When a hotspot is selected, the right panel updates to display:

| Field | Description |
|---|---|
| **Label** | The name or identifier of the selected part |
| **Detailed Description** | A full explanation of what that component is and what it does |

The side panel border glows amber when a hotspot is actively selected.

### 3. Hotspot Grid (Bottom Rail)

The bottom strip provides a visual overview of all hotspots in the activity:

- Each hotspot is represented as a colour-coded card.
- **Unvisited** hotspots appear dimmed.
- **Visited** hotspots appear fully lit with their colour.
- Clicking a card in the grid is equivalent to clicking the hotspot on the diagram — it works both ways.

---

## Exploring the Schematic

1. Click on any coloured hotspot on the main diagram.
2. Read the label and description that appears in the Side Panel.
3. Continue clicking remaining hotspots until all have been visited.
4. The bottom grid tracks your progress — watch unvisited (dimmed) cards disappear as you explore.

> **Your progress is automatically saved.** If you close and reopen the activity, visited hotspots remain marked.

---

## Completing the Activity

Once **all hotspots have been visited**, the **Finish Exploration** button becomes active in the diagram panel.

- Click **Finish Exploration** to submit your completion.
- A ✅ **"Activity Completed!"** confirmation appears on screen.
- The app returns you to the **Student Dashboard** after a moment.

Completing a Schematic Activity awards a **score of 100%** — it is a fully exploration-based activity with no wrong answers.

---

## Error States

| Message | Cause |
|---|---|
| *"Unable to load activity"* | The schematic data or image could not be loaded. Return to Dashboard and try again. |
| *"Schematic data is corrupted or missing image"* | The admin needs to re-upload the schematic asset. |
