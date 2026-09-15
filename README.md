# DoLP v0.778 · Aoki Utage + Mysterious · ModLoader v2.101.1

This repository publishes a directly playable iPhone/Safari build of **DoLP v0.778** with the **Aoki Utage + Mysterious** image package and **ModLoader v2.101.1**.

## Play

https://yfei2304-dotcom.github.io/775/

The published game is v0.778. The repository URL remains `775` until the GitHub repository itself is renamed in Settings.

## Sources

Game and image package:

`https://dolp.download/DoLP_aoki_utage_mys/v0.778/DoLP_aoki_utage_mys_v0.778.zip`

Pinned ModLoader companion:

`https://github.com/Lyoko-Jeremie/DoLModLoaderBuild/releases/download/v2.101.1-dol-0.5.12.11-240b837588c6f6ee6b07df0b161aa28f844834b0/DoL-ModLoader-2.101.1-dol-0.5.12.11-240b837588c6f6ee6b07df0b161aa28f844834b0.zip`

The workflow verifies the official archive SHA-256 (`5f02311487aa0acbaa834f1c8a284328861c9e464a4d39a8ea56efe2cefddfdc`), extracts the ModLoader runtime built specifically for DoL core `0.5.12.11`, and installs those blocks into the genuine DoLP v0.778 SugarCube startup sequence. It does not replace the v0.778 game core or its Aoki Utage + Mysterious assets.

The game is published directly as `index.html`. It does not depend on the obsolete Service Worker, compressed web payload, or redirect launcher that caused the blank page on iOS.

Generated provenance and ModLoader installation details:

https://yfei2304-dotcom.github.io/775/build-info.json

The full content audit verifies that the Twine story data and all 31,349 images are byte-identical to the pinned official v0.778 package, and that the two ModLoader blocks match the official core 0.5.12.11 build:

https://yfei2304-dotcom.github.io/775/content-audit.json
