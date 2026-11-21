# ClipNova Admin Dashboard upgrade

## Install
1. Open your existing `clipnova` GitHub repository.
2. Choose **Add file → Upload files**.
3. Upload this `index.html`, replacing the existing root `index.html`.
4. Commit the change. GitHub Pages redeploys automatically.

## Included
- Admin dashboard navigation
- Video count, approximate browser-storage usage, category count
- Searchable local video library
- Delete controls

## Security and data limitation
This is a local demonstration dashboard, not a secure production admin system. It has no authentication and only sees videos saved in the current visitor's browser. GitHub Pages is static hosting; a public platform needs a backend with server-side authentication, authorization, shared storage, and moderation. Never put admin passwords or secret API keys in this HTML file.
