# Prepared ChronoBear 0.0.49

This checkout contains the new landing page, versioned executable, full update ZIP, and update.json. It has not been committed or pushed by the staging script.

The old 0.0.24 application assets remain compatible with their original wrapper and now show a download notice. version.json retains the legacy web version fields; desktopVersion and desktopDownloadUrl identify the new executable. New desktop versions use update.json instead.

The update package checksum was verified before copying. Publish the package and executable before exposing the new manifest. The new executable checks https://ctrlaltdeluxe.github.io/chronobear-app/update.json; that URL will remain unchanged until this checkout is published.