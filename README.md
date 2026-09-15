# DoLP v0.778 · Aoki Utage + Mysterious · ModLoader v2.101.1

This repository publishes a directly playable iPhone/Safari build of **DoLP v0.778** with the **Aoki Utage + Mysterious** image package and **ModLoader v2.101.1**.

## Play

https://yfei2304-dotcom.github.io/775/

The repository name and public URL remain `775`, but all published game files are v0.778.

## Sources

Game and image package:

`https://dolp.download/DoLP_aoki_utage_mys/v0.778/DoLP_aoki_utage_mys_v0.778.zip`

Pinned ModLoader companion:

`https://github.com/Lyoko-Jeremie/DoLModLoaderBuild/releases/download/v2.101.1-dol-0.5.12.11-240b837588c6f6ee6b07df0b161aa28f844834b0/DoL-ModLoader-2.101.1-dol-0.5.12.11-240b837588c6f6ee6b07df0b161aa28f844834b0.zip`

The workflow verifies the official archive SHA-256 (`5f02311487aa0acbaa834f1c8a284328861c9e464a4d39a8ea56efe2cefddfdc`), extracts the ModLoader runtime built specifically for DoL core `0.5.12.11`, and installs those blocks into the genuine DoLP v0.778 SugarCube startup sequence. It does not replace the v0.778 game core or its Aoki Utage + Mysterious assets.

The game is published directly as `index.html`. It does not depend on the obsolete v0.775 Service Worker, compressed web payload, or redirect launcher that caused the blank page on iOS.

Generated provenance, hashes, and ModLoader installation details are available at:

https://yfei2304-dotcom.github.io/775/build-info.json
