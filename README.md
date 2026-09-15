# DoLP v0.778 · Aoki Utage + Mysterious

This repository publishes a directly playable iPhone/Safari build of **DoLP v0.778** with the **Aoki Utage + Mysterious** image package.

## Play

https://yfei2304-dotcom.github.io/775/

The repository name and public URL remain `775`, but all published game files are replaced by v0.778.

## Deployment

The workflow downloads:

`https://dolp.download/DoLP_aoki_utage_mys/v0.778/DoLP_aoki_utage_mys_v0.778.zip`

It verifies the archive, locates the packaged game HTML and full `img/` tree, adds iPhone home-screen metadata, and replaces the contents of the `gh-pages` branch.

The game is published directly as `index.html`. It does not depend on the old v0.775 Service Worker, compressed payload, or redirect launcher that could leave iOS Safari on a blank page.

Generated provenance and hashes are available at:

https://yfei2304-dotcom.github.io/775/build-info.json
