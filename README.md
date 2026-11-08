# ptgh.github.io

Files that have to live at the root of `ptgh.github.io`, which only this repo can serve.

- `.well-known/apple-app-site-association` lets links to `https://ptgh.github.io/cairn/share` open the Cairn app on iPhone. Apple fetches it by domain. The cairns themselves travel after the `#` in the link and never reach this site.
- `.nojekyll` stops GitHub Pages skipping the `.well-known` folder.

Cairn's own pages (support, privacy, and the page a shared link falls back to) live in [ptgh/cairn](https://github.com/ptgh/cairn), served at `https://ptgh.github.io/cairn/`.

`mac-backup/` is the home and privacy page Google requires before the private "Mac backup (rclone)" sign-in (Cloud project mac-backup-514110) can be published; without it Google's grant expires every 7 days. Added 8 Nov 2026.
