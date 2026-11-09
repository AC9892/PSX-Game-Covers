# PSX Game Covers

Flat front-cover artwork for PlayStation 1, PlayStation 2, and PlayStation 3 games. The covers are named by disc serial or PS3 title ID so [PSX Disc File Compressor](https://github.com/AC9892/PSX-Disc-File-Compressor) can match them to information read from a disc. Filenames of disc dumps are not used to identify games. No 3D covers, disc images, or game archives are included.

## Use with PSX Disc File Compressor

Download this repository as a ZIP and extract it, or clone it with Git. In the compressor's **Settings** tab, set **Artwork Directory** to the folder containing `ps1`, `ps2`, `ps3`, and `thumbnails` (the root of this repository). Keep the directory structure intact. Artwork remains separate from the compressor EXE and from compressed disc files. You can also use the collection offline.

## What's included

| Platform | Full covers | Matching thumbnails | Location |
| --- | ---: | ---: | --- |
| PS1 | 9,118 | 9,118 | `ps1/default/` |
| PS2 | 10,430 | 10,430 | `ps2/default/`, plus two unmatched images in `ps2/unmatched/default/` |
| PS3 | 3,810 | 3,810 | `ps3/library/covers/`, plus one individually cached cover in `ps3/covers/` |

Thumbnails follow the same paths under `thumbnails/`. All images are WebP. The converted covers use quality 85; thumbnails are at most 160 × 160 pixels and were not upscaled. A cover appears only when its serial or title ID matches the game's detected ID. The two unmatched PS2 images have filenames that cannot safely be treated as serials, so they are retained without automatic matching.

## Artwork sources and credits

| Platform | Source | Source revision or snapshot |
| --- | --- | --- |
| PS1 | [xlenore/psx-covers](https://github.com/xlenore/psx-covers) | `2cf4ba0b378f0f18e09783e7e48eb26f0bb6f0fd` |
| PS2 | [xlenore/ps2-covers](https://github.com/xlenore/ps2-covers) | `08a8734ee31aca74a7471425f73384f16e29ecbc` |
| PS3 | [GameTDB PS3 front-cover packs](https://www.gametdb.com/PS3/Downloads) | 21 regional packs dated 2026-10-28, plus one individually cached GameTDB cover |

The PS1 source credits PSX Data Center and DuckStation. The PS2 source credits PCSX2, PSX Data Center, gvcover.top, imkira3, and waifu2x. Visit the original projects and [GameTDB](https://www.gametdb.com/PS3) for their full credits, updates, and corrections.

## Artwork rights

Game cover art, trademarks, and related imagery remain the property of their respective rights holders. Conversion to WebP does not transfer ownership. This is an unofficial community collection and is not affiliated with Sony, PlayStation, or game publishers. The original source repositories do not state an artwork license, and this repository does not grant a blanket license to reuse third-party artwork. Attribution alone does not grant redistribution rights.

