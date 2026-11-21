# ClipNova

A responsive video-sharing-style website starter.

## Run it
1. Unzip the folder.
2. Open `index.html` in a modern browser (Chrome, Edge, Firefox, Safari).
3. Click **Upload** and select a video from your device.

## Important: what this version does
This is a front-end demo. Uploaded videos are stored in IndexedDB in the browser on the device where they were uploaded. They are not uploaded to a server, visible to other visitors, or shared across devices. Clearing browser site data can remove them. Browser storage limits vary, so very large videos may not save.

## Publish the site free
You can host the static site on GitHub Pages:
1. Create a GitHub account and a new public repository named `clipnova`.
2. Upload `index.html` to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. GitHub Pages will provide a public website address.

Publishing the page does not make local uploads public. For a real YouTube-like site where visitors can upload and everyone can watch, ClipNova needs a backend, user accounts, moderation, and video storage/streaming. Free tiers may have storage and bandwidth limits.
