# Monkey Makes Money — media

Public hosting for finished videos so they can be posted through the Buffer API,
which takes a media URL rather than a file upload. Served over GitHub Pages
because it returns `video/mp4` from a direct URL with no redirect, which is what
Buffer requires; `raw.githubusercontent.com` forces `application/octet-stream`
and release assets 302-redirect, so neither works.

Nothing here is authored. Everything is rendered output from the main project.
