# ChronoBear 0.0.46

Release date: 2026-11-25
Source commit: fb234c24b4609d22c0c2b566f5def9e388554073

Approved ProjOps entries display locks and prevent edits/deletion. Calendar context menus open the source record, download its latest details and approval status, or delete an editable entry. Missing DevOps metadata falls back through the linked ProjOps task and project.

The entry sidebar has wrapping project/task names, a source-tinted header, a full-height description editor, equal-width action buttons, and version/status indicators below the small calendar. Settings provides a confirmed local reset that preserves server time entries and projects.

Updates can be disabled in Settings. Enabled updates download into a separate staged release while the app stays usable and apply on restart; a spinner beside the version reports background activity. Executable replacement retains startup confirmation and rollback.

Only the latest versioned executable and update ZIP are retained. Legacy 0.0.24 web assets and version.json fields remain compatible; new desktop updates use update.json.