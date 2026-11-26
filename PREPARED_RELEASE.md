# ChronoBear 0.0.47

Release date: 2026-11-26
Source commit: fee3e8c40b55e3a19bd023a77799a2dc5df6b099

Daily requirements save when the field loses focus. ProjOps timestamp reads explicitly preserve UTC; creation and updates use the browser's local calendar date, including midnight and daylight-saving boundaries.

Calendar context menus offer five per-ticket colors, with separate DevOps and JIRA defaults in Settings. Box selection and Ctrl/Command-click support confirmed group moves and deletion with progress. Switch task lets users choose a destination from any sidebar source, including Recents and cross-system transfers. Approved entries remain protected. Long JIRA comments must be shortened explicitly before transfer to DevOps.

Transfers create the destination before removing the original, recheck the source for changes, and stop for review on partial or uncertain outcomes. Successful changes are retained without automatic retry or destructive compensation.

Release notes are bundled with the executable and available through the info button beside its version. Only the newest executable and update ZIP remain in the deployment root; legacy 0.0.24 assets and version.json fields retain their original contract.