# DoLP v0.778 · Aoki Utage + Mysterious · 繁體中文 · ModLoader v2.101.1

This repository publishes a directly playable iPhone/Safari build of **DoLP v0.778** with the **Aoki Utage + Mysterious** image package, **ModLoader v2.101.1**, and an automatically loaded **Traditional Chinese (`zh-TW`) ModI18N**.

## Play

https://yfei2304-dotcom.github.io/778/

The repository and public URL use `778`, matching the published game version.

The Traditional Chinese Mod is loaded automatically. It can also be downloaded separately:

https://yfei2304-dotcom.github.io/778/mods/ModI18N-0.5.12.11-zhtw.mod.zip

## Sources

Game and image package:

`https://dolp.download/DoLP_aoki_utage_mys/v0.778/DoLP_aoki_utage_mys_v0.778.zip`

Pinned ModLoader companion:

`https://github.com/Lyoko-Jeremie/DoLModLoaderBuild/releases/download/v2.101.1-dol-0.5.12.11-240b837588c6f6ee6b07df0b161aa28f844834b0/DoL-ModLoader-2.101.1-dol-0.5.12.11-240b837588c6f6ee6b07df0b161aa28f844834b0.zip`

Pinned community Chinese localization for core `0.5.12.11`:

`https://github.com/NumberSir/DoL-I18n-Build/releases/download/0.5.12.11-chs-auto-nightly-auto--d230276d3f0390986e385a5b924c286769bcab1a/ModI18N-0.5.12.11-chs-auto-nightly.mod.zip`

The source localization archive is verified against SHA-256 `e43a5c79847b20854cd1181ed8b010ee96ea2609167e5f927c442ba8cbdd7124`. Its translated text is converted with OpenCC `s2twp`; the English match fields, Twine macros, program identifiers, entry order, and exact `0.5.12.11` dependency remain unchanged. Attribution and modification details are included inside the generated Mod archive.

The Traditional Chinese adaptation is distributed under the source project's [CC BY-NC-SA 4.0 license](https://github.com/Eltirosto/Degrees-of-Lewdity-Chinese-Localization/blob/main/LICENSE). It is an unofficial adaptation and does not imply endorsement by the localization team.

The workflow verifies the official archive SHA-256 (`5f02311487aa0acbaa834f1c8a284328861c9e464a4d39a8ea56efe2cefddfdc`), extracts the ModLoader runtime built specifically for DoL core `0.5.12.11`, and installs those blocks into the genuine DoLP v0.778 SugarCube startup sequence. It does not replace the v0.778 game core or its Aoki Utage + Mysterious assets.

The game is published directly as `index.html`. It does not depend on the obsolete Service Worker, compressed web payload, or redirect launcher that caused the blank page on iOS.

Generated provenance and ModLoader installation details:

https://yfei2304-dotcom.github.io/778/build-info.json

The full content audit verifies that the Twine story data and all 31,349 images are byte-identical to the pinned official v0.778 package, that the two ModLoader blocks match the official core 0.5.12.11 build, and that the pinned Traditional Chinese Mod is the only automatically loaded external Mod:

https://yfei2304-dotcom.github.io/778/content-audit.json
