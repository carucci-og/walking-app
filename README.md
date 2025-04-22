# StepStack Walk Trainer – Changelog

## v1.0.0 – April 22, 2025

### ✨ Initial Release
- Created a training tracker for an 80K walk with:
  - Weekly goals based on number of short and long walks.
  - Dynamic progress bar and percent calculation.
  - LocalStorage saving for walk progress.
  - Highlights the current calendar week.
- Base styling with clean UI and responsive elements.

---

## v1.0.1 – April 22, 2025

### 🔧 Fixes and Improvements
- Moved `Date.prototype.getWeek()` helper function *above* its usage to ensure correct behavior.
- Removed accidentally duplicated helper function at the bottom of the script.
- Cleaned up and double-checked formatting and indentation throughout the code.
- Verified and validated all logic related to percent completion and checkbox saving.
