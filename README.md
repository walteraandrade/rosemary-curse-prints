# rosemary-curse-prints

Screenshot host for pull request bodies of `rosemary-curse` (private repo).

GitHub renders PR images through the Camo proxy, which fetches URLs
server-side without credentials, so `raw.githubusercontent.com` paths in a
private repo always 404. This repo is public only so those images resolve.

Files are named `pr<number>-<antes|depois>-<slug>.png`.
