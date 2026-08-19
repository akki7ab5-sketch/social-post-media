# social-post-media

Media for published social posts. **Public by design** — Instagram and Facebook
fetch post media by URL at publish time, and a raw GitHub URL is permanent,
unlike a tunnel hostname.

Raw URL shape:

    https://raw.githubusercontent.com/akki7ab5-sketch/social-post-media/main/<brand>/<file>

## Rules

1. **Only publish-approved files.** Everything here is world-readable.
2. **Never** client work that has not been cleared, anything under NDA, drafts,
   test renders, or source files.
3. **A push is irreversible.** Git keeps history; deleting a file later does not
   remove it from earlier commits.
4. Small web-sized JPEGs only (1080x1350, ~300KB). Not a video host.
5. Wait for the push to finish before scheduling a post against the URL.
