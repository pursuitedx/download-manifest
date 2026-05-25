# download-manifest

Private source-of-truth manifest for application download URLs.

Do not ship a GitHub token in the desktop app. Use this repo for controlled editing/build-time sync, or publish a sanitized manifest through a small backend/proxy when runtime updates are needed.