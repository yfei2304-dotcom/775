# DoLP v0.778 · Aoki Utage + Mysterious · ModLoader v2.101.1

This repository publishes a directly playable iPhone/Safari build of **DoLP v0.778** with the **Aoki Utage + Mysterious** image package and **ModLoader v2.101.1**.

## Play

https://yfei2304-dotcom.github.io/775/

The repository name and public URL remain `775`, but all published game files are v0.778.

## Sources

Game and image package:

`https://dolp.download/DoLP_aoki_utage_mys/v0.778/DoLP_aoki_utage_mys_v0.778.zip`

Pinned ModLoader companion:

`https://raw.githubusercontent.com/yfei2304-dotcom/dolp-aoki-mys-modloader/4821046562cad9c3df692bbe7098df441e2fb8a7/payload/game-v0772.bundle`

The workflow extracts only the verified ModLoader runtime blocks from the existing v0.772 build and installs them into the genuine v0.778 SugarCube startup sequence. It does not replace the v0.778 game core or its Aoki Utage + Mysterious assets.

The game is published directly as `index.html`. It does not depend on the obsolete v0.775 Service Worker, compressed web payload, or redirect launcher that caused the blank page on iOS.

Generated provenance, hashes, and ModLoader installation details are available at:

https://yfei2304-dotcom.github.io/775/build-info.json
