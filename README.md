# StepStack Walk Trainer – Changelog

## v1.2.0 – April 23, 2025

### 🚧 Week Layout & Progress Graph
- Introduced a **weekday-style layout** for each week’s goals, giving a calendar-like view.
- Added an **overall progress graph** (horizontal bar chart) to visualize total walk progress.
- **Fixed current week highlighting** so the active week is correctly displayed.
- Updated UI styling for cleaner layout and improved user experience.

---

## v1.1.0 – April 23, 2025

### ✨ Visual Redesign & UX Improvements
- **UI Overhaul:** Major redesign of the weekly tracker interface. Improved readability and aesthetics with rounded elements and better use of space.  
- **Calendar-Inspired Layout:** Replaced the checklist layout with a more intuitive "week day" style, making it feel like a calendar.  
- **Progress Bar:** Implemented a cleaner progress bar with more accessible visual cues (including percentage labels).  
- **Week Reset Buttons:** Added small icons for resetting weekly progress, making it easy to clear progress for each week individually.  
- **Title Update:** Updated the title from "StepStack: 80K Walk Training" to a more modern, catchy "StepStack Walk Trainer."  
- **Week Label:** Changed the "This is calendar week 17" text to a more compact and design-friendly format (e.g., "WK17" in a boxed style).  
- **Checkbox Tweaks:** Removed redundant checkboxes and replaced them with buttons displaying distance targets (e.g., "5K"), providing a more intuitive interaction.  
- **Graph Implementation (Phase 1):** Added the groundwork for a progress graph to track overall distance walked. A simple bar chart or similar visual representation will be coming in future updates.  

---

## v1.0.1 – April 22, 2025

### 🔧 Fixes and Improvements
- Moved `Date.prototype.getWeek()` helper function *above* its usage to ensure correct behavior.
- Removed accidentally duplicated helper function at the bottom of the script.
- Cleaned up and double-checked formatting and indentation throughout the code.
- Verified and validated all logic related to percent completion and checkbox saving.

---

## v1.0.0 – April 22, 2025

### ✨ Initial Release
- Created a training tracker for an 80K walk with:
  - Weekly goals based on the number of short and long walks.
  - Dynamic progress bar and percent calculation.
  - LocalStorage saving for walk progress.
  - Highlights the current calendar week.
- Base styling with clean UI and responsive elements.
